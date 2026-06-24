# Knitting Notes Help

Knitting Notes lets you import and read PDF patterns, then add rulers, text, images, information pins, brush strokes, and counters. Adding page elements or drawing does not directly modify the original PDF.

## Create and Open a Project

1. Open Tools and select **Knitting Notes**.
2. Choose the PDF file you want to import.
3. The imported file appears in the Knitting Notes project list.
4. Tap the project to continue from your previous reading position and editing state.

Free users can create up to one Knitting Notes project. Deleting a project cannot be undone, so confirm that you no longer need it first.

## Editor Layout

### Top Toolbar

- **Close**: Return to the project list and save the current reading state.
- **Undo**: Undo the latest supported brush or component operation.
- **Redo**: Restore the operation that was just undone.
- **More**: Rename, save, or delete the current project.

### Show or Hide Toolbars

Tap an empty area of the PDF to hide the top and bottom toolbars and gain more reading space. Use the small buttons at the screen edges to show them again.

### Basic Reading Gestures

- Swipe with one finger to browse the PDF.
- Pinch with two fingers to zoom.
- Tap a page component to select it and show its floating controls.
- Scrolling or zooming the PDF clears the current component selection.

## Bottom Toolbar

| Tool | Purpose |
|---|---|
| Pages | Show page thumbnails and page labels for quick navigation |
| Components | Choose an image, information pin, chart link, text, or ruler |
| Move | Return to PDF reading, scrolling, and zooming |
| Brush | Select a brush and draw on the current PDF page |
| Eraser | Erase brush strokes |
| Counter | Show or hide project counters |
| More | Open Elements, Default Color, Brush Manager, and Ruler Manager |

## Pages and Labels

Tap **Pages** to open the thumbnail panel:

- Tap a thumbnail to jump to that page.
- Use the label list at the top to jump directly to labeled pages.
- A page label appears at the bottom of its thumbnail.
- Tap `...` on the selected thumbnail to add, edit, or delete a label.
- Each page can have one label.

Free users can create up to two page labels. Existing labels can still be edited or deleted.

## Add Page Components

1. Tap **Components**.
2. Choose a component.
3. The component button changes to show the selected item.
4. Tap the target position on the PDF. The component is placed with the touch point at its center.
5. The editor automatically returns to Move mode.

Adding new page components requires membership. Existing components remain available for viewing and editing.

### Available Components

#### Rulers

Use rulers to follow the current row or column. Horizontal, vertical, and 45-degree ruler presets are provided. Presets can be adjusted in Ruler Manager.

#### Text

Text components support multiple lines. Enlarging the text box reveals more content. Text settings include text color, font size, alignment, copy, and paste.

#### Images

Images can be selected from the camera, Files, or Photos. They are inserted using their original aspect ratio and support proportional scaling and rotation, but not independent edge stretching.

#### Information Pin

An information pin appears as a fixed-size `i` icon. Tap it to read the note. Double-tap the text area in the popup to edit the content.

#### Chart Link

A chart link connects the PDF to an existing knitting chart in the app. Once linked, it can show a thumbnail and open the related knitting chart directly.

## Edit Page Components

Tap a component to show its dashed selection frame, handles, and floating controls. Available actions depend on the component type:

- Drag inside the component to move it.
- Drag an edge handle to change width or height.
- Drag the upper-right handle to scale proportionally.
- Drag the top handle to rotate.
- Use Color to change the component color.
- Use Opacity to adjust background transparency.
- Use Transform for quick angles and scale settings.
- Use Delete to remove the component.

Not every component supports every action. For example, images cannot stretch individual edges, while information pins and chart links cannot rotate or scale.

### Lock and Unlock

- When locked, the floating toolbar collapses to a single **Unlock** button.
- A locked ruler can still be moved, but it cannot be resized, scaled, rotated, or restyled.
- Locked text, images, information pins, chart links, and other components cannot be moved or edited.
- Tap **Unlock** to restore the full controls and handles.

## Brushes and Eraser

Select a brush from **Brush** and draw on the current page.

- A brush preset contains its shape, size, color, and opacity.
- Brush Manager lets you add, edit, delete, and reorder presets.
- Presets near the top of the list are shown first in the editor.
- The eraser removes brush strokes only. It does not delete rulers, text, images, or other components.
- Delete components using their floating Delete button or Elements.

Adding new brush presets requires membership. Default and existing brushes remain usable.

## Counters

Every Knitting Notes project contains at least one counter.

- Tap the number to add 1.
- Tap `-` to subtract 1.
- Tap Reset to return the value to 0.
- Tap `...` or long-press a counter to open its menu.
- The menu supports editing, direct number input, color, rename, and delete.
- Rows defines the maximum value. After the maximum is exceeded, counting restarts from 0.
- The first counter in a project cannot be deleted.

Each horizontal counter page displays up to three counters. Swipe horizontally when there are more than three; a page indicator appears at the top. Use the upper-right button to switch between full and compact height.

Free users can use up to three counters.

## Elements

Open **More > Elements** to manage components and brush notes in one place.

- The preview on the left helps identify the element and its outline.
- Tap an element to locate it on its PDF page.
- Lock or unlock components.
- Delete elements that are no longer needed.
- Nearby brush strokes are grouped into a more recognizable note preview.

## Default Color, Brushes, and Ruler Presets

The bottom **More** menu contains shared settings:

- **Default Color** affects components added afterward.
- **Brush Manager** manages brush presets shared by all Knitting Notes projects.
- **Ruler Manager** manages ruler presets shared by all Knitting Notes projects.

Changing a shared preset does not automatically alter components or strokes that have already been added.

## Save, Undo, and Restore

- Reading position, page labels, counters, and most edits are stored with the project.
- To save immediately, use **Top More > Save**.
- Undo and Redo apply to supported component and brush operations in the current editing session.
- The undo history may not remain after leaving and reopening a project, but saved page content is restored.

## iCloud and Multiple Devices

Knitting Notes backups include the project database, PDF files, and PDF-related image assets. The complete project appears on another device only after the app's iCloud sync or restore has finished.

Please note:

- iCloud backup is not real-time collaboration.
- Large PDFs may take longer to upload and restore.
- Do not delete the project or PDF from the original device before restoration finishes.
- Older database-only backups may not contain the original PDF.

## Frequently Asked Questions

### Why can I not scroll the PDF after selecting a component?

Component gestures take priority within the component's hit area. Tap an empty area, switch to Move mode, or begin zooming the PDF to clear the selection.

### Why can the eraser not delete a ruler or text?

The eraser only handles brush strokes. Use the component's Delete button or Elements for other items.

### Why can a locked ruler still move?

Rulers need to be repositioned while following a pattern. Locking preserves their size, angle, and style, while other locked components remain completely fixed.

### Why do I tap the page after choosing a component?

The choose-then-place workflow adds the component exactly where it is needed and avoids moving it from the page center afterward.

### Why do some features show a membership prompt?

The free version supports basic import, reading, and limited usage. Advanced actions such as adding page components or creating more brush presets require membership.

