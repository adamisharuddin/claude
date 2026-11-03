# Graph Report - claude  (2026-11-03)

## Corpus Check
- 133 files · ~284,029 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 11 file(s) not represented in the graph (top: .css 7, (none) 4)

## Summary
- 2734 nodes · 5514 edges · 140 communities (127 shown, 13 thin omitted)
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 123 edges (avg confidence: 0.85)
- Token cost: 298,657 input · 0 output

## Community Hubs (Navigation)
- Raptor Engine Build
- Arcade Cabinet Build
- Audit Core
- Ripple Tank Build
- Iso Kit TS Types
- Test Rig Geometry
- Turning Dial Build
- Iso Kit Primitives
- Lathe Profiles
- Arcade Cabinet Live
- Raptor Engine Live
- Spot Plate Art
- Ripple Tank Live
- Turn Kit Constants
- Print Pipeline
- Push Button Build
- Audit Fixture Tests
- Turn-Fixed Constants
- Test Rig React Art
- Turn Audit
- Audit Behaviour Tests
- Turning Dial Stress
- Turn Build
- Desk Computer Build
- Test Rig Model
- Spot Plate Drops
- Fingerprint & Publish
- Test Rig Live
- Audit Depth Checks
- 3D Turning Guide
- Turning Dial Live
- Dial Indicator Build
- Spot Plate Rig
- CI Workflow
- Raptor Part Placement
- Arcade Part Primitives
- Ripple Wave Model
- Turn-Fixed Emitters
- Anatomy Overview & Examples
- Kit Geometry Reference
- Spot Plate Live
- Spot Plate Fan
- Convex Path Utilities
- WebGL Layering Guide
- Session Tracking
- Turn Emitters
- Audit Module Reference
- React Readout Tests
- Bug Report Template
- Figure Request Template
- Turn Benchmark
- Test Rig Walkthrough
- Ripple Tank Parts
- React Solid Tests
- Kit Texture Reference
- Test Rig Rings & Ticks
- Turn Surface Sampling
- Turn-Fixed Clipping
- Browser Drive Tests
- Motion & Texture Rules
- Tube Module
- Spot Plate Figure
- Audit Shape Metrics
- Turn-Fixed Camera
- Turn Tubes & Clouds
- Anatomy Principles
- 3D Hinges & Contacts
- Craft Composition
- Test Rig Details
- Canvas Painter
- Parts Vocabulary Recipes
- Motion Choreography
- Shader Colour Ramps
- Capture & Drive Scripts
- Print Sheets
- Turn Emit Primitives
- Line-End Checks
- Contributing & PR Checks
- Line Audit Script
- Turning Dial Parts
- React Live Figure
- Turn Hull Clipping
- Line & Texture Craft
- Verify Workflow
- Changelog & Releases
- Code of Conduct
- GL Layer Module
- 3D Verification Checks
- 3D Part Constructors
- Graphify Setup
- Raptor Harness Routing
- Test Rig Poses
- GL Shared Module
- Turn-Fixed Tubes
- Turn-Fixed Emit Primitives
- Community Gallery Publishing
- Craft Anti-Patterns
- Harness Routing Guide
- React & Next.js Guide
- Turn-Fixed Pose Math
- Turn Pose Math
- Inline Kit Bundler
- Arcade Moving Parts
- 3D Materials
- WebGL Layer Reference
- Order Convergence Test
- Turn Fidelity Check
- Spot Plate Rulers
- Stress Workshop Helpers
- Issue Template Config
- Tube Reference
- Arcade Bezel Matrices
- Raptor Dome
- Capture Geometry Test
- Capture Selector Test
- OpenAI Agent Config
- Raptor Cone
- Test Rig Rods
- Turning Dial Poses
- Turning Dial Face
- 3D Performance Budget
- Explode States
- Line Arcs Test
- Lines Test
- Navigation Test
- Arcade Overlay Points
- Raptor Jackets
- Raptor Throat
- Ripple Knobs
- Session Start Hook
- Arcade Screen Points
- Arcade Coin Chute
- Arcade Flat Helpers
- Arcade Stack
- Arcade Screen
- Raptor Bell
- Raptor Puck
- Ripple Arm Ring
- Spot Plate Pair

## God Nodes (most connected - your core abstractions)
1. `3D Turning Groups Guide` - 41 edges
2. `dot3()` - 38 edges
3. `iso()` - 34 edges
4. `Anatomy skill` - 34 edges
5. `Kit API Reference` - 32 edges
6. `pathOf()` - 30 edges
7. `pathOf()` - 30 edges
8. `add3()` - 29 edges
9. `mul3()` - 29 edges
10. `sub3()` - 28 edges

## Surprising Connections (you probably didn't know these)
- `graphify skill` --conceptually_related_to--> `graphify rules`  [INFERRED]
  .claude/CLAUDE.md → CLAUDE.md
- `orientedBox()` --indirect_call--> `unit3()`  [INFERRED]
  .claude/skills/anatomy/kit/audit.mjs → .claude/skills/anatomy/kit/lathe.mjs
- `Gallery rejection rules` --semantically_similar_to--> `Security scope`  [INFERRED] [semantically similar]
  .claude/skills/anatomy/references/publish.md → .claude/skills/anatomy/SECURITY.md
- `Separating-Plane Painter's Order` --semantically_similar_to--> `Painter's Order`  [INFERRED] [semantically similar]
  .claude/skills/anatomy/references/3d.md → .claude/skills/anatomy/references/craft.md
- `The object is the explanation` --semantically_similar_to--> `The one idea that matters`  [INFERRED] [semantically similar]
  .claude/skills/anatomy/README.md → .claude/skills/anatomy/SKILL.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Anatomy figure verification pipeline** — claude_skills_anatomy_skill_verify_like_a_critic, claude_skills_anatomy_skill_geometry_audit, claude_skills_anatomy_skill_line_check, claude_skills_anatomy_contributing_read_every_png, claude_skills_anatomy__github_pull_request_template_pull_request_checks [INFERRED 0.85]
- **One true model drives readout, motion, caption and print** — claude_skills_anatomy_skill_truth_first, claude_skills_anatomy_references_walkthrough_rig_ts_pure_model, claude_skills_anatomy_references_print_sheet_mjs_spec, claude_skills_anatomy_references_motion_live_readout, claude_skills_anatomy_contributing_every_number_is_true [INFERRED 0.85]
- **Exploded view depth and collision correctness** — claude_skills_anatomy_references_motion_exploded_views, claude_skills_anatomy_references_motion_stagger_order, claude_skills_anatomy_references_motion_prefix_rule, claude_skills_anatomy_references_motion_depth_re_sorting_of_moving_parts, claude_skills_anatomy_skill_every_crossing_in_true_depth_order, claude_skills_anatomy_skill_no_pipe_or_cable_passes_through_anything [INFERRED 0.85]
- **Record, settle, audit flow** — claude_skills_anatomy_references_kit_recorder, claude_skills_anatomy_references_kit_settle, claude_skills_anatomy_references_kit_auditorexit, claude_skills_anatomy_references_verify_audit_report_lines [EXTRACTED 1.00]
- **Turning-group pair relations** — claude_skills_anatomy_references_3d_framed_plane, claude_skills_anatomy_references_3d_gjk_dynamic_plane, claude_skills_anatomy_references_3d_stable_kahn_sort, claude_skills_anatomy_references_3d_separating_plane_painter_s_order [EXTRACTED 1.00]
- **Light-theme ink rules** — claude_skills_anatomy_references_webgl_ink_on_paper, claude_skills_anatomy_references_webgl_ink_grows_with_light, claude_skills_anatomy_references_webgl_a_ground_for_the_light, claude_skills_anatomy_references_webgl_fallback_handover_crossfade, claude_skills_anatomy_references_webgl_ink_stops_at_stroke_inner_edge [EXTRACTED 1.00]

## Communities (140 total, 13 thin omitted)

### Community 0 - "Raptor Engine Build"
Cohesion: 0.01
Nodes (139): across, along, ARM, ARM_Y, back, backSvg, balance, beamBolts (+131 more)

### Community 1 - "Arcade Cabinet Build"
Cohesion: 0.02
Nodes (91): ANODE_F, anodeAt, anodeN, back, BAND, bd, BEZEL_B, BEZEL_OPEN (+83 more)

### Community 2 - "Audit Core"
Cohesion: 0.07
Nodes (72): audit(), auditOrExit(), baseSdf(), belongs(), body(), bodyDepth(), boundsOf(), box() (+64 more)

### Community 3 - "Ripple Tank Build"
Cohesion: 0.03
Nodes (70): ARM_LENGTH, ARM_N, ARM_U, at16, at28, back, backSvg, BAR (+62 more)

### Community 4 - "Iso Kit TS Types"
Cohesion: 0.05
Nodes (69): fit(), fit(), Camera, ExtrudeOptions, Faded, FadeLineStyle, FigureOptions, FitOptions (+61 more)

### Community 5 - "Test Rig Geometry"
Cohesion: 0.05
Nodes (69): ARM, BARS, BASE_SCREWS, BLOCK, BUSHES, DIAL_TICKS, FEET, FLOOR (+61 more)

### Community 6 - "Turning Dial Build"
Cohesion: 0.03
Nodes (61): argv, BACK, backSvg, BALL, BASE, BODY, BREAK_END, CONN (+53 more)

### Community 7 - "Iso Kit Primitives"
Cohesion: 0.06
Nodes (66): attrs(), axesAt(), axisVector(), AZIMUTH, cameraOf(), circleRing(), coil(), convexHull() (+58 more)

### Community 8 - "Lathe Profiles"
Cohesion: 0.12
Nodes (54): wobble(), angleToward(), arcOf(), arcPoints(), bandOf(), bandOfProfile(), BANDS, bandsOf() (+46 more)

### Community 9 - "Arcade Cabinet Live"
Cohesion: 0.07
Nodes (50): at(), chuteZ(), CLIP_DOOR, CLIP_MECH, coinPose(), drawCoins(), drawPile(), drawPulses() (+42 more)

### Community 10 - "Raptor Engine Live"
Cohesion: 0.06
Nodes (43): announce(), burn, canvas, clamp(), describe(), engine, fireButton, fireLabel (+35 more)

### Community 11 - "Spot Plate Art"
Cohesion: 0.06
Nodes (44): BASE_ART, BASE_SCREWS, BOTTLE_ART, clean(), DECK_ART, DECK_SCREWS, FEET, knurl() (+36 more)

### Community 12 - "Ripple Tank Live"
Cohesion: 0.06
Nodes (45): aimOf(), angleOf(), announce(), bar, bytes, clampTo(), crestPath, drawFallback() (+37 more)

### Community 13 - "Turn Kit Constants"
Cohesion: 0.07
Nodes (43): T3_EB, T3_EYE, T3_LB, T3_MAT_KEYS, T3_MAT_TUBE, T3_MATERIALS, T3_ROOT, T3_SHINE (+35 more)

### Community 14 - "Print Pipeline"
Cohesion: 0.12
Nodes (42): capture(), captureScript(), chromePath(), DRIVE, drive(), HERE, main(), printPdf() (+34 more)

### Community 15 - "Push Button Build"
Cohesion: 0.09
Nodes (38): at(), BASE, body, BRIDGE, cap(), CELL, cell(), column() (+30 more)

### Community 16 - "Audit Fixture Tests"
Cohesion: 0.10
Nodes (23): fixtures, P, fixtures, P, fixtures, P, capture, execute (+15 more)

### Community 17 - "Turn-Fixed Constants"
Cohesion: 0.08
Nodes (35): T3_EB, T3_EYE, T3_LB, T3_MAT_KEYS, T3_MAT_TUBE, T3_MATERIALS, T3_ROOT, T3_SHINE (+27 more)

### Community 18 - "Test Rig React Art"
Cohesion: 0.08
Nodes (32): StretchArt(), TestRigFigure(), BASE_ART, CARRIAGE_ART, DIAL_ART, FINGER_ART, FRAME_ART, PLUNGER_ART (+24 more)

### Community 19 - "Turn Audit"
Cohesion: 0.12
Nodes (33): apply(), areaOfPath(), back(), clipArea(), continuity(), convexHull(), EYE, f2() (+25 more)

### Community 20 - "Audit Behaviour Tests"
Cohesion: 0.07
Nodes (9): F, profile, radius(), options, F, P, drive, execute (+1 more)

### Community 21 - "Turning Dial Stress"
Cohesion: 0.07
Nodes (30): argv, BACK, backSvg, BENCH, body, digit(), FINGER_Y, follow() (+22 more)

### Community 22 - "Turn Build"
Cohesion: 0.13
Nodes (32): attrs(), build(), out, closest(), dotsMarkup(), esc(), gjk(), groupData() (+24 more)

### Community 23 - "Desk Computer Build"
Cohesion: 0.12
Nodes (32): at(), BEZEL, byDepth(), cable(), CASE, COIL, computer(), CRT (+24 more)

### Community 24 - "Test Rig Model"
Cohesion: 0.06
Nodes (30): ACROSS, DIP_MOST, DRAG, FRAME, GIVE, GIVE_MOST, GIVEN, HOLD_SPRING (+22 more)

### Community 25 - "Spot Plate Drops"
Cohesion: 0.10
Nodes (29): atTop(), cache, concaveRuns(), ease(), Glint, glintsOf(), Grid, Hidden (+21 more)

### Community 26 - "Fingerprint & Publish"
Cohesion: 0.12
Nodes (25): fingerprintOf(), fingerprintOfSkill(), KIT_FILES(), sha256(), walk(), AGENTS, confirm(), detectKind() (+17 more)

### Community 27 - "Test Rig Live"
Cohesion: 0.11
Nodes (28): apply(), clamp(), ease(), Hand, Nodes, Props, RESTING_TEXT, restShown() (+20 more)

### Community 28 - "Audit Depth Checks"
Cohesion: 0.16
Nodes (24): cameraBasis(), centreline(), clearances(), crowding(), depthOrder(), entriesOf(), folds(), labelOf() (+16 more)

### Community 29 - "3D Turning Guide"
Cohesion: 0.09
Nodes (20): 3D Turning Groups Guide, Browser Checks, Cover Masks, Cylinder Rule, Framed Plane, GJK Dynamic Plane, Known Limits, Live Layer (+12 more)

### Community 30 - "Turning Dial Live"
Cohesion: 0.12
Nodes (22): backLayer, controller, describe(), draw(), first, hold(), ignite(), paint() (+14 more)

### Community 31 - "Dial Indicator Build"
Cohesion: 0.14
Nodes (23): at(), BLOCKS, body, byDepth(), CARRIAGE, carriage(), D(), DIAL (+15 more)

### Community 32 - "Spot Plate Rig"
Cohesion: 0.10
Nodes (22): AZIMUTH, BORDER, BOTTLE_TOP, CAMERA, COLS, COS_A, fieldOf(), GLASS_TOP (+14 more)

### Community 33 - "CI Workflow"
Cohesion: 0.09
Nodes (22): concurrency, cancel-in-progress, group, name, runs-on, steps, timeout-minutes, jobs (+14 more)

### Community 34 - "Raptor Part Placement"
Cohesion: 0.24
Nodes (21): at(), ballAt(), boss(), boxAt(), cable(), clampAt(), Dots(), elbow() (+13 more)

### Community 35 - "Arcade Part Primitives"
Cohesion: 0.15
Nodes (21): at(), ball(), bead, board(), boltHeads, box(), cable(), chip() (+13 more)

### Community 36 - "Ripple Wave Model"
Cohesion: 0.15
Nodes (18): amplitudeOf(), BEAT, causticOf(), clippedRunsOf(), focusOf(), GLASS, magnificationOf(), nodalCount() (+10 more)

### Community 37 - "Turn-Fixed Emitters"
Cohesion: 0.24
Nodes (21): t3Arcs(), t3At(), t3BoxOf(), t3Broken(), t3EmitLathe(), t3EmitPrism(), t3EmitRibs(), t3EmitRound() (+13 more)

### Community 38 - "Anatomy Overview & Examples"
Cohesion: 0.13
Nodes (18): 3D figure kind (beta), Anatomy skill, Codex sandbox browser checks, example desk-computer, example dial-indicator, example raptor-engine, example ripple-tank, example spot-plate (+10 more)

### Community 39 - "Kit Geometry Reference"
Cohesion: 0.12
Nodes (20): coil, cylinder, depthOf, extrude, fitProjection, ISO_CSS, Kit API Reference, Kit Tools (+12 more)

### Community 40 - "Spot Plate Live"
Cohesion: 0.14
Nodes (18): GlassShape, keyOf(), RowShape, FanPose, apply(), BladeNodes, emptyBlade(), Glass() (+10 more)

### Community 41 - "Spot Plate Fan"
Cohesion: 0.14
Nodes (17): along(), BLADE, bladeAt(), BladePose, fanOf(), LEAD, place(), BLADE_LONG (+9 more)

### Community 42 - "Convex Path Utilities"
Cohesion: 0.16
Nodes (12): convexOrThrow(), fine(), finePath(), roundedPolygon(), signedArea(), turning(), TURN, prism() (+4 more)

### Community 43 - "WebGL Layering Guide"
Cohesion: 0.11
Nodes (15): Hot Plate Minimal Page, Layer Stack, Layering And Blending, Raptor Engine Shader Example, Ray-Marching In The Iso Camera, Reduced Motion, Registering Shader Content To SVG, Render Only While It Matters (+7 more)

### Community 44 - "Session Tracking"
Cohesion: 0.20
Nodes (17): parse(), usage(), entriesOf(), fromThisSession(), IDLE_CAP, measure(), parseMinutes(), parseTokens() (+9 more)

### Community 45 - "Turn Emitters"
Cohesion: 0.27
Nodes (18): t3Arcs(), t3At(), t3BoxOf(), t3Broken(), t3Dome(), t3EmitLathe(), t3EmitRibs(), t3EmitRound() (+10 more)

### Community 46 - "Audit Module Reference"
Cohesion: 0.14
Nodes (18): Audit Module, auditOrExit, clearances, crowding, depthOrder, folds, looseEnds, orderKeys (+10 more)

### Community 47 - "React Readout Tests"
Cohesion: 0.12
Nodes (13): alias, { build }, directory, nodePaths, require, alias, { build }, nodePaths (+5 more)

### Community 48 - "Bug Report Template"
Cohesion: 0.12
Nodes (16): description, label, options, placeholder, render, value, body, attributes (+8 more)

### Community 49 - "Figure Request Template"
Cohesion: 0.12
Nodes (16): description, label, options, placeholder, value, body, attributes, id (+8 more)

### Community 50 - "Turn Benchmark"
Cohesion: 0.12
Nodes (15): angles, argv, cams, cpuFrames, frames, frameTimes, kinds, median() (+7 more)

### Community 51 - "Test Rig Walkthrough"
Cohesion: 0.15
Nodes (14): rig.ts pure model, Rubber band lean, Test rig camera and layout, Test rig painter's order, Test rig parts list (53 solids), Test rig walkthrough, Build geometry once, Frame it (+6 more)

### Community 52 - "Ripple Tank Parts"
Cohesion: 0.20
Nodes (16): at(), cornerPost(), dipper(), Dots(), glassLines(), Ln(), pillar(), postSeg() (+8 more)

### Community 53 - "React Solid Tests"
Cohesion: 0.14
Nodes (11): Solid(), directory, React, { renderToStaticMarkup }, require, ts, directory, React (+3 more)

### Community 54 - "Kit Texture Reference"
Cohesion: 0.14
Nodes (16): arcOf, bandsOf, dotsOf, fadedSvg, Frame {o,a,u,v}, holdStill, lathe, Lathe Module (+8 more)

### Community 55 - "Test Rig Rings & Ticks"
Cohesion: 0.18
Nodes (15): cyl(), ring(), barTicks(), cylinder(), dialTicks(), floorGrid(), join(), ring() (+7 more)

### Community 56 - "Turn Surface Sampling"
Cohesion: 0.22
Nodes (5): surfacePoints(), frameFrom(), hull2(), sampleShape(), T

### Community 57 - "Turn-Fixed Clipping"
Cohesion: 0.16
Nodes (15): t3ArcPoints(), t3ClipConvex(), t3Dome(), t3EmitBall(), t3Enclose(), t3Grown(), t3Hull(), t3HullOut() (+7 more)

### Community 58 - "Browser Drive Tests"
Cohesion: 0.16
Nodes (9): execute, drive, execute, run(), execute, run(), check(), execute (+1 more)

### Community 59 - "Motion & Texture Rules"
Cohesion: 0.14
Nodes (8): Depth re-sorting of moving parts, Prefix rule, ride (move with mount), Stagger order, Craft rules, Geometry audit, Tone hierarchy, Verify like a critic

### Community 60 - "Tube Module"
Cohesion: 0.23
Nodes (13): cable(), area(), capOf(), crossingsOf(), LIGHT, poly(), ringsOf(), ringsSvg() (+5 more)

### Community 61 - "Spot Plate Figure"
Cohesion: 0.25
Nodes (12): LiquidArt(), SpotPlateFigure(), bladesOutOf(), GAPS, joinedAt(), joinedListOf(), listOf(), MERGE (+4 more)

### Community 62 - "Audit Shape Metrics"
Cohesion: 0.23
Nodes (13): areaOf(), attributeOf(), boxOfPoints(), boxOfShape(), cornersOfBox(), coverage(), markupBox(), matrixOf() (+5 more)

### Community 63 - "Turn-Fixed Camera"
Cohesion: 0.16
Nodes (14): t3Anchor(), t3Apart(), t3Camera(), t3Cams(), t3Cover(), t3Disjoint(), t3Frame(), t3Gjk() (+6 more)

### Community 64 - "Turn Tubes & Clouds"
Cohesion: 0.20
Nodes (14): t3Basis(), t3Cloud(), t3Cut(), t3EmitTube(), t3PointAlong(), t3PrepareBall(), t3PrepareTube(), t3Pts() (+6 more)

### Community 65 - "Anatomy Principles"
Cohesion: 0.14
Nodes (9): Envelopes for one-shot events, Turning by hand, 3D figures that turn (beta), Anatomy SKILL.md, Materials remap the ramp, Order from separating planes, Three layers, WebGL inside the drawing (+1 more)

### Community 66 - "3D Hinges & Contacts"
Cohesion: 0.14
Nodes (11): Free Group, Free Groups Break-Off, Hinge Chains, Hinge Group, Knuckle Disc, Rigid Group, Slide Group, Turn Group (+3 more)

### Community 67 - "Craft Composition"
Cohesion: 0.14
Nodes (11): Camera And Composition, Cavity Token Set, Craft Guide, Exploded Views, Nested Theme Trap, Screens And Things On Faces, Shaders In The Drawing, Split Wrapping Parts (+3 more)

### Community 68 - "Test Rig Details"
Cohesion: 0.24
Nodes (13): barScrews(), faceRing(), knurl(), ruler(), segment(), sideArc(), coil(), frameOf() (+5 more)

### Community 69 - "Canvas Painter"
Cohesion: 0.31
Nodes (12): CANVAS2D, cpCompilePart(), cpCss(), cpGeometry(), cpMatrixOf(), cpMount(), cpMul(), cpRgba() (+4 more)

### Community 70 - "Parts Vocabulary Recipes"
Cohesion: 0.15
Nodes (13): Base Plate On Feet, Coil Spring Around A Rod, Dial Gauge, Drawer With Pull, Knurled Knob With Pointer, Parts Vocabulary Recipes, Perforations And Dot Grid, Post Collar Clamp And Thumb Screw (+5 more)

### Community 71 - "Motion Choreography"
Cohesion: 0.18
Nodes (13): Announcing phases, Arming, Critically damped settle, Exponential easing toward targets, Idle tour, Keyboard and accessibility, Motion and interaction guide, One loop per figure (+5 more)

### Community 72 - "Shader Colour Ramps"
Cohesion: 0.17
Nodes (10): Colour Along The Ramp, Ink Per Frame Hook, Light-Theme Shader Checks, Fallback Handover Crossfade, Ink On Paper, Ink Stops At Stroke Inner Edge, inkFor, Light Theme (+2 more)

### Community 73 - "Capture & Drive Scripts"
Cohesion: 0.31
Nodes (9): chromePath(), main(), parse(), problemWith(), usage(), chromePort(), chromePath(), main() (+1 more)

### Community 74 - "Print Sheets"
Cohesion: 0.17
Nodes (6): engine, Checking a printed sheet, Printable sheets guide, Sheet formats (poster, drawing, detailed), sheet.mjs spec, Printable sheets

### Community 75 - "Turn Emit Primitives"
Cohesion: 0.29
Nodes (12): t3Box(), t3Emit(), t3EmitDots(), t3EmitFixed(), t3EmitPlanes(), t3EmitPrism(), t3Fix(), t3Grow() (+4 more)

### Community 76 - "Line-End Checks"
Cohesion: 0.23
Nodes (9): LINE_ENDS, browser(), chromePath(), HELPERS, main(), PERF, POPS, usage() (+1 more)

### Community 77 - "Contributing & PR Checks"
Cohesion: 0.22
Nodes (8): Pull request checks, Pull request template, Building the examples, CI byte-identical rebuild, Contributing guide, House rules, Pull request process, The checks

### Community 78 - "Line Audit Script"
Cohesion: 0.18
Nodes (9): Line-end audit curve approximation fix, actions, argv, child, out, select, tolerance, wait (+1 more)

### Community 79 - "Turning Dial Parts"
Cohesion: 0.29
Nodes (11): at(), backPosts(), base(), byDepth(), cable(), D(), L(), midStatic() (+3 more)

### Community 80 - "React Live Figure"
Cohesion: 0.27
Nodes (9): IsoFigure(), asksForStillness(), follow(), Spring, Stage(), useEased(), useInView(), useLoop() (+1 more)

### Community 81 - "Turn Hull Clipping"
Cohesion: 0.20
Nodes (11): t3ArcPoints(), t3ClipConvex(), t3EmitBall(), t3Grown(), t3Hull(), t3HullOut(), t3LatheMid(), t3LatheOutline() (+3 more)

### Community 82 - "Line & Texture Craft"
Cohesion: 0.18
Nodes (8): Monotone Cubic Hermite (Fritsch-Carlson), Smooth Shading On Curved Surfaces, fadeLineSvg, lineSvg, Smooth Shading Option, solidSvg, Free End Marking, Line Ends Check

### Community 83 - "Verify Workflow"
Cohesion: 0.20
Nodes (11): Audit Report Lines, Capture Script, Close-Ups, Common Faults And Fixes, Detail Pass, Drive Actions, Drive Script, Review Checklist (+3 more)

### Community 84 - "Changelog & Releases"
Cohesion: 0.20
Nodes (9): Anatomy changelog, Keep a Changelog, Release 1.0.0, Release 1.1.0, Rename from isometric-objects to Anatomy, Semantic Versioning, Unreleased changes, example arcade-cabinet (+1 more)

### Community 85 - "Code of Conduct"
Cohesion: 0.20
Nodes (10): Contributor Covenant 2.1, Contributor Covenant Code of Conduct, Correction, Enforcement guidelines, Mozilla code of conduct enforcement ladder, Our Pledge, Our Standards, Permanent Ban (+2 more)

### Community 86 - "GL Layer Module"
Cohesion: 0.22
Nodes (6): burst(), glCamera(), GLSL_ISO, GLSL_TURN, smooth(), glLayer API

### Community 87 - "3D Verification Checks"
Cohesion: 0.20
Nodes (7): Halving Test, Orbit Audit, burst, Checklist For 3D Figures, Orbit Checks For 3D Figures, burst Envelope, Separate Hue Envelope

### Community 88 - "3D Part Constructors"
Cohesion: 0.20
Nodes (10): Part Constructors, T.ball, T.billboard, T.fixed, T.lathe, T.plane, T.prism, T.round (+2 more)

### Community 89 - "Graphify Setup"
Cohesion: 0.28
Nodes (8): graphify skill, /graphify trigger, GRAPH_REPORT.md, graphify knowledge graph, graphify query, graphify rules, graphify update, graphify wiki index

### Community 90 - "Raptor Harness Routing"
Cohesion: 0.28
Nodes (9): CLAMPS, harnessRoute(), JACKET_BOSS, laneR(), laneS(), lugBall(), plug(), polar() (+1 more)

### Community 91 - "Test Rig Poses"
Cohesion: 0.36
Nodes (9): grownOf(), memberAt(), poseOf(), pressRun(), releaseRun(), rubberBand(), spring(), steady() (+1 more)

### Community 92 - "GL Shared Module"
Cohesion: 0.25
Nodes (4): burst(), GLSL_ISO, GLSL_TURN, smooth()

### Community 93 - "Turn-Fixed Tubes"
Cohesion: 0.31
Nodes (9): t3Basis(), t3Cloud(), t3EmitTube(), t3PrepareBall(), t3Pts(), t3Sides(), t3StripeEnd(), t3TubeCap() (+1 more)

### Community 94 - "Turn-Fixed Emit Primitives"
Cohesion: 0.36
Nodes (9): t3Emit(), t3EmitDots(), t3EmitFixed(), t3EmitPlanes(), t3Fix(), t3Grow(), t3Matrix(), t3Num() (+1 more)

### Community 95 - "Community Gallery Publishing"
Cohesion: 0.25
Nodes (9): Anatomy community gallery, Share a figure, anatomy-community repository, Gallery rejection rules, Publish steps, Publishing to the community gallery, Private vulnerability reporting, Security policy (+1 more)

### Community 97 - "Harness Routing Guide"
Cohesion: 0.22
Nodes (7): Choosing Waypoints, Clearance And Crossings, Harness Routing, Meridian Half-Section, Raptor Engine Example, Round Parts And Pipes, Saddle Pad

### Community 98 - "React & Next.js Guide"
Cohesion: 0.22
Nodes (9): Live readout, Hydration rest pose, Large-page key-warning trap, React and Next.js guide, Server/client split, useReadout, Kit setup, React or Next.js path (+1 more)

### Community 99 - "Turn-Fixed Pose Math"
Cohesion: 0.29
Nodes (8): t3Apply(), t3Compose(), t3FreeRot(), t3Mul(), t3Poses(), t3PosesMap(), t3Quat(), t3Rot()

### Community 100 - "Turn Pose Math"
Cohesion: 0.29
Nodes (8): t3Apply(), t3Compose(), t3FreeRot(), t3Mul(), t3Poses(), t3PosesMap(), t3Quat(), t3Rot()

### Community 101 - "Inline Kit Bundler"
Cohesion: 0.43
Nodes (7): fixedScript(), glScript(), glSharedScript(), KIT, kitScript(), strip(), turnScript()

### Community 102 - "Arcade Moving Parts"
Cohesion: 0.38
Nodes (5): makeParts(), stickLower(), stickUpper(), switchesClosed(), UP()

### Community 103 - "3D Materials"
Cohesion: 0.29
Nodes (7): Material brass/copper, Material chrome, Material gold, Material gunmetal, Material rubber, Material steel, Materials

### Community 104 - "WebGL Layer Reference"
Cohesion: 0.33
Nodes (7): glLayer, GLSL_ISO, GLSL_TURN, glslPose, settle Spring, WebGL Layer Module, Camera Contract

### Community 105 - "Order Convergence Test"
Cohesion: 0.33
Nodes (4): at(), cam, chain(), P

### Community 106 - "Turn Fidelity Check"
Cohesion: 0.57
Nodes (5): identity(), restValues(), rootOf(), rounds(), tubes()

### Community 107 - "Spot Plate Rulers"
Cohesion: 0.40
Nodes (6): countY(), rulerOf(), RULERS, rowX(), rowY(), WELLS

### Community 108 - "Stress Workshop Helpers"
Cohesion: 0.33
Nodes (6): L(), mat(), put(), S(), VERT(), workshop()

### Community 109 - "Issue Template Config"
Cohesion: 0.33
Nodes (5): blank_issues_enabled, contact_links, about, name, url

### Community 110 - "Tube Reference"
Cohesion: 0.40
Nodes (5): crossingsOf, Raptor pipe() Helper Pattern, Tube Module, Tube Rings Texture, tubePieces

### Community 111 - "Arcade Bezel Matrices"
Cohesion: 0.40
Nodes (5): bezelMatrix(), bezelPt(), faceClip, openClip, planeMatrix()

### Community 112 - "Raptor Dome"
Cohesion: 0.50
Nodes (5): DOME_BOSS, domeAt(), onBody(), radiusOn(), slopeOn()

### Community 113 - "Capture Geometry Test"
Cohesion: 0.60
Nodes (3): capture(), execute, pngOf()

### Community 114 - "Capture Selector Test"
Cohesion: 0.60
Nodes (3): capture(), driveTarget(), execute

### Community 115 - "OpenAI Agent Config"
Cohesion: 0.50
Nodes (3): interface, display_name, short_description

### Community 116 - "Raptor Cone"
Cohesion: 0.50
Nodes (4): cone(), CONE, coneShare(), coneSlope()

### Community 117 - "Test Rig Rods"
Cohesion: 0.50
Nodes (4): RODS, solid(), haloOf(), slabOf()

### Community 118 - "Turning Dial Poses"
Cohesion: 0.50
Nodes (4): breakAt(), follow(), poses(), tapAt()

### Community 119 - "Turning Dial Face"
Cohesion: 0.67
Nodes (4): faceMarkup(), ringPath(), tick(), wheelFace()

### Community 120 - "3D Performance Budget"
Cohesion: 0.50
Nodes (4): Adaptive Half Rate, Detail By Speed, Part Cost In Prism Units, Performance Budget

### Community 121 - "Explode States"
Cohesion: 0.50
Nodes (4): Explode States, prefixStates, reversalsOf, springStates

### Community 122 - "Line Arcs Test"
Cohesion: 0.67
Nodes (3): check(), execute, lines

### Community 123 - "Lines Test"
Cohesion: 0.67
Nodes (3): check(), execute, lines

### Community 125 - "Arcade Overlay Points"
Cohesion: 0.67
Nodes (3): cpPoint(), cpTop(), overlay

### Community 126 - "Raptor Jackets"
Cohesion: 0.67
Nodes (3): band(), JACKETS, RINGS

### Community 127 - "Raptor Throat"
Cohesion: 0.67
Nodes (3): throat(), THROAT, throatSlope()

### Community 128 - "Ripple Knobs"
Cohesion: 0.67
Nodes (3): FA(), knobAt(), needleAt()

## Knowledge Gaps
- **150 isolated node(s):** `[RA, RB]`, `GRAPH_REPORT.md`, `graphify wiki index`, `/graphify trigger`, `skills CLI install` (+145 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1122 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **13 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Kit API Reference` connect `Kit Geometry Reference` to `Raptor Engine Build`, `Audit Core`, `Lathe Profiles`, `Turn Kit Constants`, `Test Rig React Art`, `Turn Audit`, `Turn Build`, `3D Turning Guide`, `Audit Module Reference`, `Turn Benchmark`, `Kit Texture Reference`, `Tube Module`, `Craft Composition`, `Capture & Drive Scripts`, `Line-End Checks`, `Line Audit Script`, `React Live Figure`, `Line & Texture Craft`, `GL Layer Module`, `Inline Kit Bundler`, `WebGL Layer Reference`, `Tube Reference`?**
  _High betweenness centrality (0.200) - this node is a cross-community bridge._
- **What connects `[RA, RB]`, `GRAPH_REPORT.md`, `graphify wiki index` to the rest of the system?**
  _150 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Raptor Engine Build` be split into smaller, more focused modules?**
  _Cohesion score 0.012987012987012988 - nodes in this community are weakly interconnected._
- **Why does `Kit setup` connect `React & Next.js Guide` to `Anatomy Principles`, `Audit Core`, `Inline Kit Bundler`, `Lathe Profiles`, `Capture & Drive Scripts`, `Line-End Checks`, `Turn Kit Constants`, `Line Audit Script`, `Push Button Build`, `React Live Figure`, `Print Pipeline`, `Test Rig React Art`, `Turn Audit`, `Turn Benchmark`, `GL Layer Module`, `Turn Build`, `Tube Module`?**
  _High betweenness centrality (0.130) - this node is a cross-community bridge._
- **Should `Arcade Cabinet Build` be split into smaller, more focused modules?**
  _Cohesion score 0.019417475728155338 - nodes in this community are weakly interconnected._
- **Why does `WebGL Inside The Drawing Guide` connect `WebGL Layering Guide` to `Craft Composition`, `Inline Kit Bundler`, `WebGL Layer Reference`, `Shader Colour Ramps`, `Capture & Drive Scripts`, `Verify Workflow`, `GL Layer Module`, `3D Verification Checks`, `3D Turning Guide`?**
  _High betweenness centrality (0.053) - this node is a cross-community bridge._
- **Should `Audit Core` be split into smaller, more focused modules?**
  _Cohesion score 0.06736842105263158 - nodes in this community are weakly interconnected._