---
layout: default
title: "Knitting Counter Usage Guide"
---

## Overview

This is a memory-enabled counter specifically designed for knitting, consisting of two core components:  
1. **External Counter**: Primarily used for row counting with PDF or image-based patterns.  
2. **Internal Counter**: Tailored for patterns created with the App's built-in pattern editor, offering richer features such as simultaneous row and stitch counting.  

When used within a knitting project, the counter automatically calculates yarn consumption and cost once yarn details are entered.

### Document Explanation

This document follows the UI layout of the counter, explaining functions from top to bottom.

### Add (Create a New Tab)

Use this feature to add a customizable tab. A single knitting project can be divided into multiple tabs, each completely independent—sharing only the control buttons at the bottom of the page. All tab-specific data (row/stitch counts, logs, patterns, etc.) remains separate between tabs.

### Tab Area (Below Navigation Bar, Above Mode Switch)

#### Edit Button
- Located on the far right of the tab bar, used for renaming or deleting tabs.  
- **Deletion is irreversible**: All data associated with the tab will be permanently removed. Proceed with caution.

#### Pattern Display Area
Displays knitting patterns in two formats:
- **Internal Patterns**: Created using the App's built-in pattern editor.  
- **External Patterns**: Imported images or PDF files from the photo album or device storage.

##### External Pattern Area
> Access via: Function Bar → Select "External Pattern" button  

- **Crosshair Button (Top Right)**: Tap to display a centered crosshair guide for navigating complex patterns.  
- **Row Markers (Left Side)**: Simple row navigation for external patterns. Supports scrolling and tapping; the current row is indicated in red text at the bottom.

##### Internal Pattern Area
> Access via: Function Bar → Select "Internal Pattern" button  

Essentially a canvas from the internal editor (without editing controls). Unlike the virtual row markers for external patterns, row and stitch positioning here is precise and accurate.

### Counter Display Area

Shows row and stitch counts with the following features:
- Supports **Stable Mode** counting.  
- Supports **Variable Mode** counting (stitch count changes with rows).  
- Goal setting: The display flashes and vibrates slightly when the target row is reached, signaling the completion of a phase.  
- Customizable starting row: Defaults to row 0, but can be set to start at row 1 to accommodate different counting habits.

### Switch Tabs

As the name suggests, selecting a tab determines which count (row or stitch) will be modified. No further explanation is needed here.

### Log Area

Records logs of row/stitch count changes triggered by user operations:
- [S] = Stable Mode; [C] = Variable Mode.  
- **Note Button [M] (Right Side)**: Add notes to logs for error tracing.  
- Adjustable size: The log area is minimized by default but can be expanded when detailed review is needed.  
- Tap logged entries with notes to view the notes.  
- [+] operations are recorded in black; [-] operations in red.

### Knitting Mode Area

- **Stable Mode**: Consistent stitch count per row (knitting at a steady pace).  
- **Variable Mode**: Stitch count changes gradually per row (knitting with varying stitch frequencies).

#### Stable Mode
After selecting Stable Mode, tap [Settings] to open a configuration dialog requiring two parameters:
- **Max Stitches per Row**: Number of stitches needed per row.  
- **Total Rows to Knit**: Target number of rows.  

Once set, the counter display shows:
- Top of display: "Stitches per row: 10 | Target rows: 20"  
- Bottom of display: Current mode and unit of change for [+]/[-] taps.  
- Right side of display: Task progress (can exceed 100% if knitting beyond the target, e.g., 30 rows when the target is 20).  
- The display flashes and the device vibrates slightly when the target is reached.

#### Variable Mode
After selecting Variable Mode, tap [Settings] to open a dedicated configuration page (due to the increased number of parameters).  

**Mode Configurator**  
- Configuration parameters are detailed with in-app instructions at the bottom of the page; no repetition here.  

Once set, the counter display shows:
- Top of display: "Decrease 1 stitch every 3 rows | Repeat 4 times"  
- Bottom of display: Current mode, current repeat count, and unit of change.  
- Right side of display: Task progress (can exceed 100% if knitting beyond the target).  
- The display flashes and the device vibrates slightly when stitches need to change or the target is reached.

### Function Bar

For long-time users: Previously, control buttons were scattered across the page. As features expanded, centralizing and categorizing controls became a priority—resulting in the current function bar.

#### First Row Buttons

##### Chart Analysis
Generates visual graphs based on count logs. For users who enjoy data visualization, reviewing these charts can bring a sense of accomplishment by tracking the knitting process.  

When used within a project, Chart Analysis offers enhanced features:
- Links to the Yarn Record section: Select yarns used, track weight consumption, and automatically calculate costs based on stored prices.  
- Bidirectional data synchronization with the Yarn section.  
- Comprehensive project history tracking through linked data points.  
- Project回溯 (Retrospection) feature: View project details in tabular format.  

> The Project section is a labor of love from the developer. The counter is just one phase of project tracking—we recommend using the Project section for a more rewarding knitting experience.

##### Internal Pattern
Selecting this button switches the top pattern display area to an internal pattern, with controls including:
- **Import Project**: Choose a target pattern (e.g., fair isle design). If no project is imported initially, a quick import button is available in the pattern display area (select from the project list, sourced from the App's Tool section).  
- **Style Settings**: Access the pattern editor to customize display styles (see the editor's "Count Mode" explanation for details).  
- **Center Count**: Controls row positioning (enabled by default). When enabled, the current row stays centered in the pattern display area; when disabled, rows do not auto-center.  
- **Stitch +/-**: Manual stitch position adjustment (not yet linked to stitch count). Please provide feedback if you need this feature.

##### External Pattern
Selecting this button switches the top pattern display area to an external pattern, with controls including:
- **Import Pattern**: Supports imports from the photo album or iCloud Files. Note: PDF files typically offer better clarity than images, but the App uses vector rendering to enhance image quality.  
- **Link Settings**: Due to the variety of external pattern formats, the App does not automatically calculate virtual row heights. Users can customize linkage settings (enabled by default). Detailed usage rules are provided in the pop-up; no repetition here.

#### Control Area Buttons
- **Log Size**: Adjusts the log display size (minimized by default; expand for detailed review).  
- **Clear Logs**: Deletes all logs for the current tab (irreversible). Associated notes and chart data will also be reset.  
- **Reset Counts**: Quickly resets the selected count (row or stitch). To reset both, perform the action twice. All resets require secondary confirmation to protect user data.

### Bottom Control Buttons
- [-]: Decrease the selected count (row or stitch).  
- [+]: Increase the selected count (row or stitch).  
- **Unit Selector (Middle)**: Adjusts the increment/decrement unit. Note: If you scroll the unit selector quickly and tap [+]/[-] before the animation ends, the old unit will be used. Always refer to the unit displayed at the bottom of the counter—this is the unit used for calculations.

### Linked Sections

No section in the App operates independently; all are tightly integrated around knitting. The current counter is a sub-feature of knitting projects, designed to assist with counting during the knitting process.

> Some counter features are restricted to permanent or subscribed users. Maintaining a complex, regularly updated App requires ongoing time and effort from the developer.
