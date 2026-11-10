---
name: design-pipeline
description: Run the user's full spatial design process end to end — brief, moodboard, 3D model (SketchUp / Blender), rendering and client presentation — with the AI doing all production work and the user only making decisions at a few gates. Use whenever the user starts a new design project, says "new project", "start a design", "make a moodboard", "model this room", "render this", "build the presentation", "continue project X", or gives a site/brief and wants it designed.
---

# Design Pipeline

The user's rule: **the user only decides; the AI produces everything.** Never ask the
user to do work you can do (search, draw, model, render, lay out, rename files).
Ask only at the gates below, and make each gate answerable in one short reply.

## The pipeline

```
 BRIEF ──▶ G0 ──▶ MOODBOARD ──▶ G1 ──▶ MODEL ──▶ G2 ──▶ RENDER ──▶ G3 ──▶ PRESENTATION ──▶ G4
```

| Stage | AI produces | Gate: the user decides |
|---|---|---|
| 0 Brief | Structured brief from whatever the user gave (a sentence, photos, a plan, a voice note) with every gap filled by a stated assumption | **G0** confirm or correct assumptions |
| 1 Moodboard | 3 distinct design directions, each a full board | **G1** pick A / B / C (or "A but warmer") |
| 2 Model | Parametric spec → SketchUp Ruby script + .dae + Blender scene, plan and axo previews | **G2** approve layout or say what moves |
| 3 Render | Hero + supporting views, day/evening variants | **G3** pick the shots that go in the deck |
| 4 Presentation | Finished client deck + material/FF&E schedule | **G4** approve → export / send |

Read the stage reference before running each stage:
`references/01-moodboard.md`, `references/02-model.md`, `references/03-render.md`,
`references/04-presentation.md`. The single source of truth for geometry and
materials is `spec.json`, described in `references/spec-schema.md`.

## Project folder

Every project lives in `projects/<slug>/` at the repo root:

```
projects/<slug>/
  brief.md            # from templates/brief.md
  decisions.md        # from templates/decisions.md — append-only gate log
  state.json          # {"stage": "...", "gate_pending": "G1", "updated": "..."}
  01-moodboard/       # board-A.html, board-B.html, board-C.html, chosen.md
  02-model/           # spec.json, build.rb (SketchUp), model.dae, scene.py (Blender), previews/
  03-render/          # cameras.json, renders/*.png, selects.md
  04-presentation/    # deck (artifact link or .pptx/.pdf), schedule.xlsx
```

On "continue project X": read `state.json` and `decisions.md`, then resume at the
pending gate — never re-ask a decision already logged.

## How to run a gate

1. Finish *all* production for the stage first. A gate never shows half-work.
2. Show the options visually (publish an Artifact or send the files), then ask with
   **AskUserQuestion** — 2–4 options, recommended first, each with a one-line
   trade-off. The free-text "Other" covers nuanced answers.
3. Log the answer in `decisions.md` (date, gate, choice, the user's words).
4. Update `state.json`, commit, push, and start the next stage immediately — do not
   ask "shall I continue?".

## Autonomy rules

- **Default everything.** Missing dimension, budget, style, room count → choose a
  sensible value, write it in the brief under *Assumptions*, keep going. G0 is where
  the user corrects them.
- **Feedback is a delta, not a restart.** "Make the sofa smaller" edits `spec.json` and
  regenerates downstream outputs; earlier approved decisions stay.
- **Downstream regenerates automatically.** A change at stage N re-runs N+1…4 outputs
  that depend on it, without a new gate unless the change alters something the user
  already approved.
- **Be honest about tool limits.** If a step needs software only the user has (SketchUp
  desktop, Enscape, D5) give one copy-paste action, never a tutorial. If a render
  service key is missing, request it with the credential tool once, then fall back.
- **Commit at every gate** so the project survives the cloud session ending.

## Fast mode

If the user says "just do it" / "auto", pick the recommended option at every gate,
log it as `auto`, and present only the final deck plus a one-page summary of the
choices made so any one of them can be reversed.
