# Stage 4 — Presentation

Use the Slides artifact type (quickstart intent "slides") by default; exports to
.pptx/PDF. Use the `pptx` skill only if the user asks for a PowerPoint file.

## Standard deck (adapt length to the project)
1. Cover — project name, client, date, hero render
2. Brief & goals — 3–5 bullets from `brief.md`
3. Site / existing — user photos or existing plan
4. Concept — chosen direction name, idea sentence, moodboard
5. Palette & materials — swatches + material board with codes
6. Plan — dimensioned layout from `previews/`
7. Key views — selected renders, one per slide, short caption
8. Details / joinery — close-ups, axo of key joinery
9. Lighting — evening renders + lighting points
10. FF&E & material schedule — generated from spec codes
11. Budget band & next steps (only if brief has budget; otherwise next steps)

Also export `schedule.xlsx` (code, item, material, supplier, qty, notes) with the
`xlsx` skill.

## Gate G4
Publish, then AskUserQuestion: Approve & export / Edit (free text) / Different tone
(more visual / more technical). On approve: export PDF + .pptx, commit, and give the
user the links — done.
