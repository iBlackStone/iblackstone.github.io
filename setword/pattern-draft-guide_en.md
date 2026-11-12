---
title: Smart Pattern Editor Guide
lang: en
hide_page_title: true
---

**Quick navigation**

- [Create](#create) · [Canvas](#canvas) · [Tools](#tools) · [Piece actions](#context) · [Counts](#counts) · [Settings](#settings) · [Membership](#membership) · [Evidence](#evidence)

<a id="create"></a>
## Create

Pattern Design includes New Pattern, files, records, templates, presets, gauges and people. Choose knitting or crochet, then Free Draw, Body Block, Strategy or Template. Free Draw opens an empty grid immediately; a person, strategy and gauge are optional. Every starting method leads to the same editable canvas. Files retain project and folder links. Touch and hold a library record to delete it with confirmation.

<a id="canvas"></a>
## Canvas

One finger or a pen uses the active tool; two fingers pan and pinch to zoom. Select an object before dragging. Hold overlapping objects to choose one, or use the object panel. Draw → Geometry offers saved construction points, two-tap or dragged straight lines, polylines, rectangles and center-to-edge circles. Keep paths open, continue them or explicitly close them. In Edit → Nodes, drag a selected segment’s midpoint to bend it with endpoints fixed; square handles refine curves. Brush and eraser handle sketches. Convert a single sketch through preview and confirmation into an independent piece, retaining the stroke. Connecting open paths creates a previewed continuous copy and retains originals and annotations. Continuous actions can be undone.

<a id="tools"></a>
## Tools

Draw → Snapping uses the visible centimeter grid, adapting its step with zoom. Targets include piece/image/sketch edges and centers, guides and visible body-block center, chest and waist lines. Locked targets remain usable; hidden targets are excluded. Orange points and dashed lines show a match; dragging away releases it. Text aligns by its center, Tips/callouts by position. Brush strokes, curve handles and dimension labels remain free. Person, comparison, paper and object-property menus anchor to the selected row.

The groups are Draw, Edit, Annotate, Knit, Person & References, Preview, and Objects & Display. Switching groups shows a short hint. Frequent tools stay visible; related actions expand as needed. Finish, Close, Keep Open and Cancel appear only during path drawing. Annotate contains Text, Tips, leaders and dimensions; Knit contains gauge, boundaries, knitting joins, chart placement and colorwork. Grid visibility, grid/endpoint snapping and direction constraints are independent.

The active drawing tool stays highlighted. The geometry entry names the current shape, such as “Geometry: Circle”, and its menu highlights that tool too. Opening or dismissing the menu keeps the tool unchanged. Hold a tool for a short explanation. The contour pen creates editable piece outlines that you can close or keep open; the brush stores sketches and handwriting, converted into an independent piece only after preview and confirmation. Symmetry has its own on/off highlight and applies to the contour pen and polylines.

Automatic actions appear after a complete rectangle, circle, ellipse or straight line, in a fixed tool area outside the canvas while keeping the drawing tool active. Contours and polylines show actions after explicit closure or completion as an open line. Actions stay hidden during point placement, dragging and unfinished paths. Starting the next drawing hides the old actions but retains the tool-area height to prevent canvas jumps. Brush strokes and erasing do not open menus automatically. Completed text, Tips, image and dimension additions also show their actions. Explicit object selection still uses a nearby floating menu; geometry, color and snapping options open from their controls.

Double-tap is an additional editing shortcut. With an idle drawing or selection tool, double-tap a piece for stretching, scaling and layout rotation, or a sketch/image for whole-object transforms. Text/Tips open content and style; dimensions open their editor. Body references only select that part and offer position unlocking, without stretching. The canvas names the edited object and offers Done Editing, which restores the previous menu and drawing tool; choosing another tool explicitly uses that choice. Unfinished contours, dimension placement, construction points and two-point lines retain their drawing behavior. Double-tap still closes an active polyline. In selection/node/transform modes, double-tap blank space to fit the view. Unlock objects before editing. Sketch transforms preserve strokes; conversion, erasing, hit testing and export use their paper positions after rotation. Charts keep their existing gauge mapping.

The selected-object menu shows frequent actions for its type, plus Objects & Layers and More. Pieces offer transform, nodes and duplicate; text/Tips offer content and style; sketches offer conversion preview; dimensions offer editing. The object panel locates and highlights the current object. Each row’s More menu offers its available editing, rename, duplicate, stacking and delete actions, always targeting that row. Unlock an object before editing or deleting it. A body block or body reference part can be copied as an independent piece; Hide Reference preserves its human-body source. Deleting a piece removes connections but keeps text, manual dimensions and chart records with invalid-link warnings. Independent charts and other projects remain. Duplicate, delete and stacking actions support Undo during the current edit; deletion requires confirmation.

The geometry menu includes Ellipse: drag between opposite corners of its bounding rectangle to set width and height. Select a piece, then choose Edit → Transform. Drag an edge to stretch horizontally or vertically, or a corner to scale proportionally; Lock aspect ratio also constrains edge handles. The top handle rotates only the paper layout. Precise dimensions accepts width/height in cm and a layout angle; resetting the angle keeps the center and real size. Resizing changes the actual outline and recalculates stitch/row estimates when gauge is available; manual plans are retained for review. Layout rotation preserves knitting direction and plans. Anchored text and dimensions follow and remain readable; charts rotate with the piece. Body-block comparison uses actual dimensions and the original knitting direction. Pinching only zooms the view; nodes and curves remain editable. Transforms support undo, and saving restores layout angle and aspect-lock state.

Body-block front, back and sleeve parts, and each body-dimension reference piece, have separate rows in Objects & Layers. Select, unlock, move, hide and reorder them individually. Tap a part’s outline, reference line or title, unlock it and drag within its frame. Its construction lines, points and notes move together; other parts stay in place. Existing projects inherit the former group’s position, visibility and lock state. Body-data updates preserve matching part identities and adjusted positions. References remain read-only at 1:1, without stretching or node editing. Copy as Piece copies the current part directly into an editable piece. Moves support Undo and saving; use the comparison page for precise checks.

<a id="context"></a>
## Piece actions

Choose top, bottom, left, right or straight dimensions, then tap successive nodes or bounds references. Measurements, estimated counts and your planned counts remain distinct. Labels avoid each other and can be dragged without changing pieces. Inspector boundaries can add path-length dimensions, which do not imply a stitch count. Annotate provides multiline Text, tap-to-open Tips, callouts and references. Text supports size/alignment. Attach an annotation to the nearest node of a chosen piece; it follows that node but remains draggable. A deleted anchor is marked invalid rather than rebound.

<a id="counts"></a>
## Dimensions and stitch plans

Estimates use current path bounds, perimeter, area and row coverage in four working directions. Recalculation never regenerates a strategy over your drawing. Without gauge, centimeters remain available. Geometric estimates are not approved knitting instructions; open or self-intersecting paths require correction. Plan edits cover cast-on, total rows, side shaping and applicable neck/center holds. Geometry, gauge or direction changes retain manual steps/counts and require another review.

<a id="settings"></a>
## Reusable data

Person & References selects measurements, reference images or independent copies of body-block pieces. Changing the person does not reshape drawn pieces. Objects & Display → Objects & Layers provides selection and location, visibility, locking, drag sorting and front/back ordering. Locked objects cannot be dragged normally but remain selectable in the panel for unlocking. Paper & Display sets dark, light or custom paper, centimeter minor/major grids, stitch grids and reference styles without recoloring content. More → New Defaults affects later documents; the current document can explicitly adopt common paper defaults.

<a id="membership"></a>
## Free version and membership

The free version can keep two pattern projects at a time. Deleting one frees a slot, while existing projects always remain openable, editable, savable, and deletable. Free Draw and essential drafting tools—including body reference, formal body block, ease, gauge, dimensions, curves, nodes, and stitch plans—remain available.

The Basic Drop-Shoulder Pullover is free. Other paid built-in strategies require active membership and a separate unlock purchase. Owned strategies remain usable in the current app data after membership expires. Local/imported strategies, My Templates and authoring tools require membership. Generation Prep is free; creating outputs checks membership. Strategy purchases are consumable and cannot be restored to a new device through the App Store. Multiple presets and strategy-package import/export also require membership.

<a id="evidence"></a>
## Evidence and future outputs

Generation & Links offers knitting, flat crochet, counter tasks and yarn estimates. Generation Prep lists requirements and links to gauge, plan or the original canvas; reopening from that canvas resumes preparation. Formal charts need an executable, confirmed plan. Free closed pieces can use flat crochet within the supported stitch/topology rules. Counter tasks retain their source. Yarn estimates use valid closed areas and a measured swatch; fix any invalid piece before estimating. Bounding rectangles are not substituted, and inventory is not deducted automatically.

<a id="workflow-save-export"></a>
## Preview, export and save

More → Export Design independently controls grids and expanded, numbered or hidden Tips. Saves retain open paths, annotations, stacking and paper. Each document restores its viewport, tool, selection and confirmed comparison without replaying commands or restoring Undo history. Pattern Records and Files share the latest successfully saved full-design preview, independent of the last zoomed or blank viewport. Readable older documents retain identity, geometry, notes and plans; unknown data is not overwritten with a blank project.

<a id="body-block-comparison"></a>
## Compare with a body block

Preview → Compare with Body Block starts from the current piece. Choose a front/back block and a full or half piece. Mark its centerline and corresponding chest/waist level, then align at a chosen level and lock the reference at 1:1. One finger moves only the unlocked reference; two fingers navigate. Mark same-side neck/shoulder, shoulder tip, neck center, underarm and hem as needed. Results use actual outlines for widths, planar side differences and shoulder/neck/vertical measurements. Missing marks or multiple intervals do not produce a single width. Tap a result to highlight it. Confirm to save evidence and placement, then edit the piece and resume comparison; Back cancels changes. Rule-derived blocks may include estimates. Differences are not whole-garment ease, body clearance, pressure or a fit verdict.

<a id="try-on-3d"></a>
## 3D samples and reference material simulation

In the release build, tapping the pattern editor’s 3D sample opens a maintenance notice. The 3D instructions below apply to Debug builds.

Open Preview → 3D Sample or the 3D workspace: Person, Assembly, Drape, Display, Camera and Adjust. Body blocks, 2D dimension comparisons and connection checks remain available. Bodies use saved measurement snapshots; choose neutral, female, male or child templates in person details. Templates estimate missing shape. Shoulder-point width is a positioning proxy; notes identify unfitted surface lengths. Changing people leaves panels unchanged.

A valid closed panel works without gauge, panel roles or seams. In Assembly → Panel Placement and Pinning, select a panel, place it in front of the chest, behind the back or over either shoulder, then drag with one finger; two fingers navigate. Pin two top-edge points, tap to add/remove pins, rotate 90°, or reset. For a basic vest, confirm four shoulder and side joins, leaving neckline, armholes and hem open.

Assembly → Reference Knit Material offers Soft Drape, Standard Knit and Stiffer. These are reference presets; gauge sets dimensions and motif scale, not elasticity. The main button starts, pauses or resumes gravity draping; restart from initial placement. Body and material estimates do not determine precise fit or pressure, and collisions may still show penetration.

When viewing, one finger rotates horizontally; two pan and pinch to zoom, and double-tap focuses. Display can hide the base. Saved try-on settings and camera return on reopening.

Update 3D after changing actual 2D paths. Compare results before and after changes from the same view under matching body, material, placement and pinning conditions. Save an effect image only from a current, valid completed result; running, paused or stale results are not current exports.

Front, back and sleeve panels copied from body blocks, including outlines that explicitly return to their start before closing, can enter 3D. If a panel outline or boundary is invalid, garment simulation stops while the current body remains visible. The message names the panel and reason; correct it and update 3D. This body preview cannot be exported as a valid garment result.

Valid 3D previews can be saved with a project and restored when the pattern, body and simulation conditions still match. Input changes require a new simulation; failed or unfinished results do not overwrite the last saved valid preview.

<a id="piece-colorwork"></a>
## Piece colorwork

Open Knit → Piece colorwork, or 3D → Display → Piece colorwork. Choose a piece and an existing knitting color chart. The motif repeats at stitch and row gauge from the bottom center. Switch to a single motif, enter whole-stitch/row offsets, set the background, or replace individual source colors. Dragging on the canvas also moves it by whole stitches and rows. Necklines, armholes and outer edges clip the pattern. Each source cell stays one stitch by one row; it is never stretched to fit. The selected background fills empty/transparent source cells and the area outside a single motif.

Save and delete support Undo; Cancel commits nothing. Sync after source or gauge changes. A change detected while saving first refreshes the preview for another review and save. 2D, assembly, 3D and eligible knitting output share the same sampling rule. Starting side changes numbering only; colorwork preserves active stitches and underlying symbols. This version accepts color cells or plain knit/purl only, excluding explicit no-stitch cells, multi-cell/structural stitches and translucent colors. Colorwork shows color appearance; yarn floats and the material behavior of the actual stitch structure are not yet simulated. Overall fabric drape uses an independent reference material rather than physical properties derived from the colorwork. Automatic seam matching, bands and saved colorways remain unavailable.

<!-- bernat-debug-2026-11-10 -->
Internal Debug sample: rebuild the app, then open Bernat M at the bottom of New Pattern → Knitting → Strategy Generation. This fixed-M four-panel reference supports editing, saving and reopening. The sample now uses a synthetic open-mesh body for experimental try-on. Automatic grading and neckband/rib details remain unfinished; final quality and result saving are under review.

When the Bernat M simulation finishes, tap **Fit review** and choose Chest, Neckline, Cuffs, or Hem. Dashed lines point to the body and solid lines point to the garment. Set a target range for chest ease, compare both cuffs, or compare the front and back hem. Template landmarks, unfinished neckband dimensions, and simulations that fail quality checks are identified in the panel.

In Hem, a short dashed line marks the body’s reference waistline. Tap **View body** to fade the garment, then **Restore garment** to return to the normal view. The guide lines realign after you finish moving the view.
<!-- /bernat-debug-2026-11-10 -->

<!-- bernat-debug-tryon-2026-11-10 -->
Open 3D to try the sample on a synthetic reference body. When simulation finishes, use Share to save an engineering preview image. Only results that pass quality checks can be saved and reopened as try-on results.
<!-- /bernat-debug-tryon-2026-11-10 -->
