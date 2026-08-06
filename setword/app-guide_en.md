---
title: Knit & Crochet User Guide
---

Knit & Crochet helps you organize yarn, manage knitting projects, track progress, design knitting and crochet charts, and read PDF pattern notes. Each tool works independently and can also be attached to the same project.

## Quick navigation

- [Getting started](#getting-started)
- [Main navigation](#main-navigation)
- [Yarn library](#yarn-library)
- [Project workspace](#project-workspace)
- [Knitting counter](#counter)
- [Knitting charts](#knitting-chart)
- [Knitting chart area operations](#knitting-chart-area-operations)
- [Crochet charts](#crochet-chart)
- [Project Notes](#knitting-notes)
- [Other tools](#other-tools)
- [Import, export, and sync](#data-transfer)
- [Membership](#membership)
- [Settings and help](#settings-help)
- [FAQ](#faq)

<a id="getting-started"></a>
## Getting started

1. Open the built-in tutorial project on Home to see how projects, counters, charts, and notes work together.
2. Add yarn records with photos, specifications, stock, and price information.
3. Create a project and attach the yarn you plan to use.
4. Add counters and link knitting charts, crochet charts, or Project Notes.
5. Return to the current-project card on Home whenever you want to continue.

When the local project library is empty, Knit & Crochet installs one bundled tutorial project. This installation does not require membership and does not use the free personal-project allowance. If you delete it, Knit & Crochet will not recreate it repeatedly.

<a id="main-navigation"></a>
## Main navigation

### Home

Home is the project workspace. The header shows the current project and its next action. The project list can be filtered by states such as All, In Progress, Preparing, Completed, and Abandoned.

### Yarn

The Yarn tab stores your material library. Create and search records, browse groups, track stock, and review yarn activity in the calendar.

### Tools

Tools contains knitting charts, crochet charts, counters, Project Notes, color tools, symbol libraries, and calculators. Items created here can later be linked to a project.

### Settings

Settings contains appearance, language, membership, data sync, release notes, feedback, privacy information, and this help center.

<a id="yarn-library"></a>
## Yarn library

### Create and edit records

- Record name, brand, fiber, color, construction, ply, yarn count, weight, length, price, and stock.
- Attach multiple photos and keep purchasing or usage details.
- When enough specifications are available, Knit & Crochet can calculate values such as linear density, diameter, recommended needle size, and length.
- Link yarn to projects and record the amount used by each project.

### Find and organize yarn

- Filter the library with multiple search conditions.
- Browse groups based on name, fiber, color, form, and other stored fields.
- Use stock alerts to find yarn that is running low.
- Use the yarn calendar to review added and usage records.

### Swatch simulator

Open the swatch simulator from any yarn detail page. Enter stitches, rows, finished size, or gauge information to assist with gauge and target-size conversions.

<a id="project-workspace"></a>
## Project workspace

### Create a project

A project can store:

- Craft type, project type, status, and cover information.
- Linked yarn and usage amounts.
- One or more main counters.
- Project Notes, knitting charts, and crochet charts.
- Recommended techniques and symbols actually used by linked charts.

### Continue working

Home prioritizes recently updated projects. Open a project to continue its main counter or enter its materials, charts, notes, and techniques.

### Project status

Projects can be Preparing, In Progress, Completed, or Abandoned. Changing status organizes the list and does not delete project content.

### Complete project package

Members can export a project together with linked yarn, counters, charts, PDFs, images, and resource relationships as one `.lineopus` file. Import creates an independent copy and does not overwrite an existing project with the same name.

<a id="counter"></a>
## Knitting counter

The counter can be used as a standalone tool or as the main progress tracker inside a project.

### Counting

- Track rows/rounds and stitches, or use a single-value counter.
- Configure fixed stitch counts or increase/decrease rules.
- Choose automatic advance, confirmation, or manual completion when a row target is reached.
- Add multiple counter tabs, then rename, reorder, or remove them.
- Use action logs for project analysis.

### Knitting plan

Save the current counting rule as a plan task and add later sections. Applying the next section changes the rule without clearing the current values, logs, or linked chart.

### Chart modes

Each counter supports three display modes:

- **Knitting chart**: link an in-app grid chart and optionally follow the current row automatically.
- **Project Notes**: link a PDF or image note in read-only mode and remember the counter's current page.
- **Text instructions**: save written steps and adjust text size.

<a id="knitting-chart"></a>
## Knitting charts

The knitting chart editor stores colors and stitch symbols in grid cells. It is suitable for stitch charts, stranded colorwork, cross-stitch, and pixel art.

### Draw and edit

- Configure rows, columns, cell size, and reading direction.
- Choose stitches from the system or custom symbol library.
- Draw symbols, fill colors, erase, undo, and redo.
- Use area selection for copy, cut, paste, fill, replace, and repeated placement.
- Save reusable colors, templates, and custom symbols.

<a id="knitting-chart-area-operations"></a>
### Area operations

Tap **Area Operations** in the bottom toolbar, then drag the selection or its four edge handles to set the range. Copy, Cut, and Paste are useful when you want to reuse the same clipboard content. Commands under **More Operations**—transforms, mirror copy, 2D Tile, Alternating Mirror, Half-Drop Repeat, and Save as Pattern—use the current selection directly, so you do not need to copy first and your existing clipboard remains unchanged.

- **Transform**: flip horizontally or vertically, rotate 180°, or create a mirrored copy on either side. With **Mirror Stitch Symbols** enabled, directional decreases, increases, and cables are changed to their matching mirrored stitches. Neutral, custom, and unmapped stitches remain unchanged.
- **Repeat**: **2D Tile** repeats the selection to the right and down to the canvas edges. **Alternating Mirror** alternates the original and horizontally mirrored motifs across columns. **Half-Drop Repeat** shifts the 2nd, 4th, 6th, and later alternating motif columns down by half the selection height, so the selected height must be even.
- **Area editing**: **Blank Cell Stitches** affects only cells in the current selection that do not yet contain a stitch and preserves their backgrounds. With chart rules, flat knitting fills right-side rows with knit stitches and wrong-side rows with purl stitches; knitting in the round fills every row with knit stitches. You can instead choose one single-cell stitch and symbol color. Existing stitches, **No Stitch**, and cells occupied by multi-cell stitches are not replaced.
- **Patterns and other projects**: **Save as Pattern** stores the selection in My Patterns for reuse on another canvas. Cross-project copy uses a separate shared clipboard.
- **Edges and undo**: multi-cell stitches must be fully selected, and an incomplete stitch is not written when it cannot fit at a canvas edge. Each area command creates one undo step.

Examples:

1. Select a 4 × 4 motif and choose **2D Tile** to fill continuously from the selection’s top-left corner toward the canvas bottom-right.
2. Select a 6-row motif and choose **Half-Drop Repeat**. The 2nd, 4th, 6th, and later alternating columns are shifted down by 3 rows.
3. Select a motif with left- and right-leaning decreases or cables, enable **Mirror Stitch Symbols**, and choose **Alternating Mirror** to alternate both the motif geometry and stitch direction.
4. Select the part of a chart where blank squares represent base stitches, choose **Blank Cell Stitches**, review the rule and affected count, then fill everything in one undoable command.

### Create from an image

The image workspace has two separate paths:

- **Regular image**: for photos and illustrations. Crop, rotate, change aspect ratio and placement, then reduce the image to pixel colors.
- **Grid chart**: for pixel images or pattern images/PDFs that already contain cell lines. Calibrate the outer frame and horizontal/vertical spacing before aligning it to the editor grid. Then choose pixel drawing or symbol drawing.

Grid charts can adjust canvas cells, chart scale, and position. Preview before applying so existing canvas content is not replaced unexpectedly.

Color drawing offers **Natural**, **Simplified Blocks**, and **Monochrome** plans. A regular image can use quick preview or open **Confirm Drawing Plan** to edit settings and color groups; a grid pixel chart samples each calibrated cell before confirmation. You can recolor, locate, merge, split, or ignore groups. Symbol drawing shows grouped recognition results and lets you correct the stitch and cell background. Every path creates a preview first and changes the project only after **Apply to Canvas**.

### Counter mode and export

Link a chart to a project counter to display the current position on a larger canvas and follow rows. In the chart editor’s own counter mode, enable **Show Current Row Stitches** in common settings to display consecutive stitch runs in actual knitting order, including stitch color, cell background, and direction.

- Flat knitting reads odd rows from right to left and even rows from left to right. Knitting in the round reads every row from right to left. The project’s **Knitting Method** setting controls this behavior.
- Hiding row markers also hides the current-row strip. When column markers are enabled, the current column is the preferred position; otherwise the strip remembers its reading position.
- Adjacent cells merge only when stitch, symbol color, and background match. Ordinary blank cells break a run. **No Stitch** represents no worked stitch, so it is neither displayed nor counted and does not split matching stitches on its two sides.

Export options include images and editable project files; use project files for continued editing and images for sharing or printing.

### Saving

- Timed autosaves are disabled while you edit so saving cannot interrupt canvas interactions. Changes are saved when the app moves to the background, when you open Export, or when you tap Close; Close waits for the save to finish before returning. The top Save button remains available for an immediate manual save.

<a id="crochet-chart"></a>
## Crochet charts

The crochet editor uses a free canvas and is not restricted to the knitting grid.

- Create a canvas and configure its background and size.
- Use the multilingual system symbol library or maintain custom symbols.
- Move, rotate, scale, copy, delete, and reorder symbols.
- Select multiple symbols for grouping and whole-group transforms.
- Arrange repeated symbols along straight or curved paths and adjust direction, spacing, and start position.
- Use quick fill, default sizing, counters, and canvas guides.
- Save and export crochet charts.

### Editing tips

- Search the symbol library by name, abbreviation, or keyword. Recently selected symbols appear first under Used.
- Project settings control the line width and default size of newly added symbols. Turning-chain symbols 2–6 include a curvature handle for bending.
- Layer management shows regular group members recursively. Expand or collapse a group, locate elements, toggle visibility, or lock them.
- In multi-select mode, tap elements to add or remove them, or draw a new selection box to replace the current selection. Drag any selected element to move the selection together without creating a group, and tap empty canvas to exit multi-select.
- Smart Snapping is on by default. The center crosshair always follows the element while dragging; its center can snap to the visible canvas center, and its visual edges or center can align with other visible elements. A successful snap shows a highlighted guide and gives one light haptic response. Turn snapping off under Settings > Editing Aids while keeping the center crosshair.
- Timed autosaves are disabled while you edit so saving cannot interrupt canvas interactions. Changes are saved when the app moves to the background, when you open Export, or when you tap Close; Close waits for the save to finish before returning. The top Save button remains available for an immediate manual save.
- Export supports PNG/PDF, resolution, margins, and background options, plus optional title, notes, symbol legend, author, and copyright information.

Knitting and crochet editors use different data and coordinate models. Create and import files with the matching editor.

<a id="knitting-notes"></a>
## Project Notes

Project Notes imports PDF or image patterns and overlays editable page elements without rewriting the original PDF.

- Create notes from Camera, Photos, or Files.
- Zoom, change pages, use thumbnails, and add page tags.
- Add images, text, info markers, rulers, chart links, and grid-segmentation frames.
- Draw with pens, erase strokes, undo, redo, and manage elements.
- Use auxiliary counters inside a note.
- Link notes to a project or counter.

Project Notes has its own detailed guide. Select “Project Notes” in the help center.

<a id="other-tools"></a>
## Other tools

- **Color tools**: sample colors from images, create palettes, and save color records.
- **Symbol libraries**: browse and search knitting or crochet symbols and maintain personal symbols or notes.
- **Body measurements**: record measurements for garment projects and preview basic stitch/row conversions.
- **Calculators**: assist with gauge, length, weight, and size calculations.
- **Calendars and alerts**: review yarn/project records and configure stock-related reminders.

<a id="data-transfer"></a>
## Import, export, and sync

### iCloud data sync

Upload and download in Settings operates as a full-library backup. Current backup packages include the database and required PDF/image assets. Download replaces local data with the cloud backup; it is not a record-by-record merge. Check the device and backup time before restoring.

### File types

- `.lineopus`: one complete project and its linked resources.
- `.pxproj` or knitting-project formats: editable knitting charts.
- PDF/images: sources for Project Notes or sharing output.
- CSV: batch transfer for yarn records.

A complete project package is not a replacement for a full-library backup, and a full backup is not intended for sharing one project.

<a id="membership"></a>
## Membership

Basic browsing and access to existing content remain available where possible. Batch transfer, complete project packages, higher creation allowances, and some professional editing actions require membership. The message shown at the point of use is the current source of truth.

After changing devices or reinstalling the app, open the membership page in Settings and use Restore Purchases.

<a id="settings-help"></a>
## Settings and help

- **Appearance**: major editors support light and dark mode. Use the sun/moon button in the top-right of Settings for a quick toggle, or open Appearance to select a mode.
- **Language**: Simplified Chinese, English, Japanese, Korean, and French.
- **Release notes**: review important changes in published versions.
- **Feedback**: send a problem report, suggestion, and screenshots.
- **App Features Guide**: opens this page; Quick navigation jumps directly to a module.
- **Privacy Policy and Terms**: review privacy and service information.

<a id="faq"></a>
## FAQ

### Why did an import create a copy?

Complete project and chart packages import as copies by default to protect existing local work.

### Why is a PDF or image missing on another device?

Make sure you used a current backup package that includes assets and allowed upload/download to finish. Copying an older database file alone may omit PDF and image files.

### Why does the tutorial not return after I delete it?

The tutorial is installed only during the first empty-library check. Deleting it means it is no longer needed, so Knit & Crochet does not recreate it.

### Why does a button open the membership page?

The action is a member feature or its free allowance has been reached. Existing content normally remains viewable or editable as described by the on-screen message.

### How should I report a problem?

Open Settings → Feedback. Include the steps, expected result, actual result, and a screenshot for visual or layout issues.
