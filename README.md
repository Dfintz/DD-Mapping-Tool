# Dune Awakening Deep Desert Mapping Tool

## Project Description

This project is a web-based interactive mapping tool designed for the game **Dune: Awakening**. It allows players to collaboratively map, annotate, and share information about the Deep Desert region, including resources, points of interest (POIs), and house locations. The tool is optimized for usability, accessibility, and performance, making it suitable for both individual and group use.

## Features

### Interactive 9x9 Grid Map
- Large, visually clear 9x9 grid representing the Deep Desert.
- Each cell can hold multiple icons representing resources, POIs, or house locations.
- Click or keyboard navigation to select, annotate, and explore cells.
- Multi-cell selection for batch operations.

### Icon Placement & Management
- Drag-and-drop or click-to-select icons from a categorized legend.
- Icons include resources (Spice, Titanium, Stravidium, etc.), POIs (Shipwrecks, Caves, Testing Stations), and all major Houses.
- Icons can be toggled on/off per cell.
- Visual feedback for icon placement and removal.

### Legend Panel
- Compact, categorized legend for quick icon access.
- Houses and resources/POIs are separated for clarity.

### Map Exploration & State
- Mark cells as explored/unexplored with a single click.
- Visual overlay for unexplored cells.
- "Explore All" button to mark the entire map as explored.

### Undo/Redo & Versioning
- Full undo/redo stack for all map actions.
- Save and load named map versions for easy progress tracking.
- Autosave and periodic memory cleanup for performance.

### Import/Export
- Export map data as JSON or a formatted PNG image (with legend and timestamp).
- Import map data from JSON files (with validation and error handling).
- Drag-and-drop or file input for importing JSON.

### Storm Timer
- Displays the next storm buildup and hit times for Europe (Monday 05:00 UTC and Wednesday 04:00 UTC).
- Real-time countdowns with phase highlighting (active, warning, critical).
- Toggle between UTC and local time display.
- Server location selector.

### Accessibility & Usability
- ARIA roles and labels for screen reader support.
- Tooltips and clear button labels for all controls.
- Responsive layout for various screen sizes.

### Additional Features
- Shareable map links.
- Notification system for user feedback.
- Data validation for safe imports and exports.
- Customizable icon set (SVG-based for clarity and scalability).

## Getting Started

1. Use the legend to drag or click icons onto the grid.
2. Use the control buttons to explore, undo/redo, save/load, or export your map.
3. Monitor storm phases with the built-in timer.

## File Structure
- `index.html` – Main application file (HTML, CSS, JavaScript).
- `Icons/` – Folder containing all SVG icons for resources, POIs, and houses.
- `background.jpg`, `arrakis.png`, `fwb.png` – Visual assets for the UI.
- `README.md` – Project documentation (this file).

## License
This project is provided for community use and is not affiliated with the official Dune: Awakening game or its developers.
