# spec.json — single source of truth

Everything downstream (SketchUp script, .dae, Blender scene, renders, schedule,
presentation captions) is generated from this file. Edit the spec, never the outputs.

Units: millimetres. Origin: bottom-left corner of the site/room at finished floor level.
Axes: x → right (width), y → back (depth), z → up.

```json
{
  "project": "kopitiam-ttdi",
  "units": "mm",
  "direction": "B",
  "spaces": [
    {
      "id": "dining",
      "polygon": [[0,0],[8000,0],[8000,6000],[0,6000]],
      "height": 3200,
      "floor": "mat.terrazzo", "walls": "mat.limewash", "ceiling": "mat.paint-white"
    }
  ],
  "openings": [
    {"id": "door-main", "wall": "dining:0", "offset": 1200, "width": 1800, "height": 2400, "type": "door"},
    {"id": "win-1",     "wall": "dining:1", "offset": 800,  "width": 2400, "height": 1500, "sill": 900, "type": "window"}
  ],
  "elements": [
    {"id": "counter", "kind": "box",  "at": [500,4500,0], "size": [3000,700,1050], "material": "mat.oak", "tag": "joinery"},
    {"id": "table-1", "kind": "asset","asset": "table-round-900", "at": [3000,2000,0], "rot": 0, "tag": "ffe"}
  ],
  "materials": {
    "mat.oak":       {"color": "#B08A5B", "roughness": 0.5, "texture": null, "supplier": null, "code": "J-01"},
    "mat.terrazzo":  {"color": "#D9D2C5", "roughness": 0.3, "texture": null, "code": "F-01"}
  },
  "lights": [
    {"id": "pendant-1", "kind": "point", "at": [3000,2000,2400], "watts": 60, "kelvin": 2700}
  ],
  "cameras": [
    {"id": "hero", "eye": [7500,500,1600], "target": [2000,5000,1000], "lens": 24, "time": "day"}
  ]
}
```

`direction` is the moodboard direction chosen at G1.

Rules:
- `kind: box | extrude | asset`. Assets are named parametric generators (tables,
  chairs, sofas, beds, cabinets) that the build scripts know how to make; add new ones
  to the generators rather than hand-placing geometry.
- Every material and FF&E element carries a schedule `code`; the presentation's
  schedule is generated from these.
- Validate before generating: polygons closed and non-self-intersecting, elements
  inside their space, door swings and 900 mm circulation clear. Fix silently, report
  in the G2 summary.
