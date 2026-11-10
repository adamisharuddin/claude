# Stage 1 — Moodboard

Goal: three genuinely different directions, so G1 is a real choice.

## Produce
For each direction A, B, C:
- **Name + one-sentence idea** ("Tropical Brutalist — raw concrete softened by shade and planting").
- **Palette**: 5–6 hex swatches with roles (base, secondary, accent, timber, metal).
- **Materials**: 5–8 named finishes (floor, wall, joinery, upholstery, metal, stone)
  with real-world references or supplier examples where found.
- **Imagery**: 8–12 reference images. Sources, in order of preference:
  1. images the user supplied (always used first),
  2. AI-generated mood images if an image-generation API is connected,
  3. web image references found with WebSearch (link and credit each; do not rehost
     copyrighted images in a client deck — use them only on the internal board).
- **Key pieces**: 4–6 furniture/lighting archetypes.
- **Why it fits the brief** (3 bullets) and **risk** (1 bullet: cost, maintenance, trend).

Lay each out as an HTML board (load `artifact-design` first; masonry grid, swatch strip,
material chips, short captions) and publish as one Artifact with A/B/C tabs.

## Gate G1
AskUserQuestion: "Which direction?" — A / B / C (recommended first). Accept blends
("A palette, C materials"): merge into `01-moodboard/chosen.md` and the spec's
`materials`, no second round unless asked.
