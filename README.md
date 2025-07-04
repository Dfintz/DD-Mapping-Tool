# DD-Mapping-Tool

A comprehensive web-based mapping tool for Dune Awakening's Deep Desert region. Track resources, POIs, and house locations with an intuitive 9x9 grid interface.

## Features

### Interactive Map Grid
- **9x9 Grid System**: Each cell represents a map region (A1-I9)
- **Subcell Precision**: Each cell contains a 3x3 subcell grid for precise icon placement
- **Drag & Drop**: Easily place icons by dragging from the legend panels
- **Multi-Select**: Shift-click to select multiple cells at once
- **Explored/Unexplored States**: Track which areas you've visited

### Icon Management
- **Resource Icons**: Spice, Titanium/Stravidium Islands, Caves, Testing Stations, Shipwrecks, POIs
- **House Icons**: 25 unique house faction icons
- **Smart Scaling**: Icons automatically resize based on quantity (1-4+ icons per subcell)
- **House Restrictions**: Each house can only be placed once per map

### Controls & Navigation
- **Left-click** subcells to open the icon picker
- **Right-click** or **Double-click** cells to toggle explored status
- **Escape key** closes any open modal (icon picker or help)
- **Keyboard navigation** with arrow keys
- **Undo/Redo** functionality (up to 100 steps)

### Storm Timer
- Real-time countdown to next storm event
- Support for all server regions:
  - Europe: Monday 17:00 - Tuesday 05:00 UTC
  - North America: Tuesday 00:00 - 10:00 UTC
  - South America: Monday 22:00 - Tuesday 08:00 UTC
  - Asia: Monday 11:00 - 21:00 UTC
  - Oceania: Monday 09:00 - 19:00 UTC
- Toggle between UTC and local time display

### Export & Sharing
- **Export JSON**: Save your map data for backup
- **Import JSON**: Load previously saved maps
- **Export PNG**: Generate high-quality images with legends and timestamp
- **Share Link**: Create shortened URLs to share maps with others
- **Auto-save**: Maps automatically save to browser local storage

### Additional Features
- **Responsive Design**: Works on desktop and mobile devices
- **Help Modal**: Built-in guide accessible via the "?" button
- **Combine Maps**: Link to external tool for merging multiple maps
- **Visual Feedback**: Notifications for actions and confirmations

## Usage

1. **Open the tool** in any modern web browser
2. **Select icons** from the legend panels or use the icon picker
3. **Place icons** by clicking subcells or dragging onto the map
4. **Mark areas** as explored by right-clicking cells
5. **Export your map** as JSON or PNG when ready

## Technical Details

- Pure HTML/CSS/JavaScript (no build process required)
- Uses LZ-String for URL compression
- Canvas-based PNG export with high DPI support
- Local storage for persistence
- Responsive grid layout

## Browser Compatibility

- Chrome/Edge 88+
- Firefox 85+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Android)

## Installation

Simply download and open `index.html` in your web browser. All assets are included or loaded from CDN.

## Contributing

Feel free to submit issues and pull requests. The codebase is self-contained in `index.html` for easy modification.

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

Created for the Dune Awakening community to enhance Deep Desert exploration and coordination.
