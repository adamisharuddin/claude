# Stage 3 — Rendering

Two routes; pick automatically by what is available, state which was used.

## Route A — fully automatic (default)
1. Run `scene.py` in headless Blender (`pip install bpy` or a Blender binary),
   Cycles, from every `cameras` entry; day and evening variants via `time`.
2. Output 2–3 hero views + 3–5 supporting views at 1920px (finals at 3840px after G3).
3. Optional **AI enhance pass**: if an image-to-image render service is connected,
   send the clay/Cycles render + the chosen direction's palette and materials as the
   prompt to add photoreal texture, plants, people, styling. Always keep geometry from
   the original (low denoise / structure control) so the client sees what will be built.
   Ask for the API key with the credential tool the first time; never ask the user
   to paste keys in chat.

## Route B — user's own renderer (Enscape / D5 / V-Ray)
If the user prefers their renderer's quality, `build.rb` already created scenes per
camera with materials named for the renderer. The user's one action: open, batch-render
all scenes, drop the folder back. Claude does the selection, grading and captioning.

## Post
Consistent colour grade, crop to deck ratios (16:9 hero, 4:5 detail), filenames
`<camera>-<time>-v<n>.png`, captions drawn from the spec (space, key materials).

## Gate G3
Contact sheet (one Artifact). AskUserQuestion (multiSelect): which shots go in the deck.
Notes like "warmer", "less clutter" → re-render those only.
