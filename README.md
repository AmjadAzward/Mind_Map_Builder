# Mind Map Builder


An advanced web-based concept map builder designed for creating, connecting, and customizing shapes with an intuitive drag-and-drop interface. Includes features like grouping, resizing, connectors, undo/redo, and saving/loading maps.

<img width="1919" height="861" alt="image" src="https://github.com/user-attachments/assets/41a75d41-6a73-49ba-b078-0d0030e9c4ff" />

---

## Features

- **Shape Palette**: Drag and drop shapes like Rectangle, Ellipse, Circle, Diamond, Triangle, and Note onto the canvas.
- **Inspector Panel**: Customize selected shape properties:
  - Label, Fill Color, Border Color
  - Font Size, Weight, Style, Family, and Color
  - Border Width, Opacity
- **Connectors**: Easily connect shapes with arrows using anchor points.
- **Grouping & Ungrouping**: Group multiple shapes together or separate them.
- **Undo/Redo**: Easily revert or redo actions.
- **Copy, Paste, Duplicate, Delete**: Efficiently manipulate selected shapes.
- **Zoom & Pan**: Zoom in/out and pan the canvas.
- **Save & Load**:
  - Save and load maps from local storage.
  - Import/export JSON files for sharing.
- **Export Options**: Export your concept map as SVG or PNG.
- **Context Menu**: Right-click options for quick actions on selected shapes.

---

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Use the **Shapes Palette** to add shapes to the canvas.
4. Select a shape to view and edit its properties in the **Inspector Panel**.
5. Connect shapes by clicking anchor points.
6. Save your work locally or export it as JSON, SVG, or PNG.

---

## Keyboard Shortcuts

| Action           | Shortcut                 |
|-----------------|--------------------------|
| Undo             | Ctrl + Z                 |
| Redo             | Ctrl + Y / Ctrl + Shift + Z |
| Delete Selected  | Delete                   |
| Copy             | Ctrl + C                 |
| Paste            | Ctrl + V                 |

---

## File Structure

- `index.html` — Main HTML file containing UI and script.
- Inline CSS — Styling for dark mode, panels, buttons, and canvas.
- Inline JS — Logic for shapes, connectors, grouping, undo/redo, inspector, export, and canvas interaction.

---

## Technologies

- HTML5, CSS3, JavaScript
- SVG for canvas rendering
- Local storage for saving maps
- Modern CSS for dark-themed UI

---

## Notes

- Canvas supports snapping to a 20px grid.
- Connectors dynamically attach to nearest anchor points.
- Inspector updates automatically when a single shape is selected.
- Undo/Redo functionality tracks shape, connector, and group changes.

---

## License

This project is open-source and free to use. You can modify it as needed for personal or educational projects.
