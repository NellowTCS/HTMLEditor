# HTMLEditor  
<br>
<br>
<br>
<br>
<br>
<br>
HTMLEditor has a new home!
(Don't worry, it wasn't sold or anything)
https://github.com/HTMLToolkit/HTMLEditor
<br>
<br>
<br>
<br>
<br>
<br>

A web-based, drag-and-drop HTML editor for creating and prototyping web layouts with real-time preview, code editing, and dark mode support. Built with HTML, CSS, JavaScript, and powered by libraries like Interact.js and Highlight.js.

**[Live Demo on GitHub Pages](https://htmltoolkit.github.io/HTMLEditor/)**  
**[Download v1.0.0](https://github.com/NellowTCS/HTMLEditor/releases/download/v1.0.0/HTMLEditor-v1.0.0.html)**

## Features

- **Drag-and-Drop Interface**: Add and position elements like divs, text, images, buttons, forms, flexbox, grids, and cards.
- **Real-Time Preview**: See your changes instantly in an iframe preview.
- **Code Editors**: Edit HTML, CSS, and JavaScript with syntax highlighting (via Highlight.js).
- **Properties Panel**: Adjust element properties like position, size, colors, and content.
- **Snapping**: Align elements with snap guides for precise layouts.
- **Undo/Redo**: Revert or redo changes with history support (Ctrl+Z, Ctrl+Y).
- **Dark Mode**: Toggle between light and dark themes (Ctrl+D).
- **Project Management**: Save, load, and export projects as HTML, CSS, and JS files.
- **Keyboard Shortcuts**: Streamline workflow with shortcuts (e.g., Ctrl+S to save, ? for shortcuts panel).
- **Responsive Design**: Adapts to smaller screens for mobile use.
- **Auto-Save**: Automatically saves your project every 30 seconds.

## Screenshots

| Light Theme | Dark Theme |
|-------------|------------|
|<img width="1280" alt="Screenshot 2025-05-07 at 11 22 23 AM" src="https://github.com/user-attachments/assets/206b0c2e-705d-4ea1-89c0-02c6568a7744" /> |<img width="1280" alt="Screenshot 2025-05-07 at 11 22 34 AM" src="https://github.com/user-attachments/assets/bbf73206-83ca-45bd-b221-6b0f9ce20aa0" /> |
<img width="1280" alt="Screenshot 2025-05-07 at 11 19 57 AM" src="https://github.com/user-attachments/assets/09ba795b-fad9-4e20-a06a-89a8568eeb56" />


## Getting Started

### Option 1: Use Online (GitHub Pages)
1. Visit the **[Live Demo](https://nellowtcs.github.io/HTMLEditor/)**.
2. Start creating by dragging elements from the tools panel to the canvas.
3. Edit code in the HTML, CSS, or JavaScript tabs.
4. Save or export your project using the toolbar buttons.

### Option 2: Run Locally
1. Download the latest release:
   - **[HTMLEditor-v1.0.0.html](https://github.com/NellowTCS/HTMLEditor/releases/download/v1.0.0/HTMLEditor-v1.0.0.html)** from the [Releases page](https://github.com/NellowTCS/HTMLEditor/releases/tag/v1.0.0).
2. Open the `HTMLEditor-v1.0.0.html` file in a modern web browser (Chrome, Firefox, Edge, etc.).
3. Use the editor as described in the Usage section.

### Option 3: Clone and Customize
1. Clone the repository:
   ```bash
   git clone https://github.com/NellowTCS/HTMLEditor.git
   ```
2. Open `index.html` in a web browser or serve it using a local server (e.g., `npx serve`).
3. Modify the code to add features or customize the editor.

## Usage

1. **Add Elements**:
   - Use the Tools Panel to add elements (e.g., Div, Text, Button, Flexbox).
   - Click an element button to add it to the canvas at (50px, 50px).

2. **Position and Resize**:
   - Drag elements to reposition them (snapping enabled by default).
   - Use resize handles or the Properties Panel to adjust size.
   - Fine-tune position with Ctrl + Arrow Keys or resize with Shift + Arrow Keys.

3. **Edit Code**:
   - Switch between HTML, CSS, and JavaScript tabs to edit code.
   - Changes reflect instantly in the preview.

4. **Manage Projects**:
   - **Save**: Click "Save" or press Ctrl+S to store the project in localStorage.
   - **Load**: Click "Load" to restore a saved project.
   - **Export**: Click "Export" or press Ctrl+E to download `index.html`, `styles.css`, and `script.js`.
   - **Delete**: Select an element and click "Delete" or press Delete.

5. **Toggle Features**:
   - **Dark Mode**: Click the theme switch or press Ctrl+D.
   - **Properties Panel**: Click "Properties" or press Ctrl+P.
   - **Shortcuts**: Click "Shortcuts" or press ? to view the shortcuts panel.

6. **View Preview**:
   - The right pane shows a live preview of your project, updated in real-time.

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Delete` | Delete selected element |
| `Ctrl + S` | Save project |
| `Ctrl + E` | Export project |
| `Ctrl + D` | Toggle dark mode |
| `Ctrl + P` | Toggle properties panel |
| `Ctrl + Arrow Keys` | Fine-tune element position |
| `Shift + Arrow Keys` | Resize selected element |
| `?` | Show shortcuts panel |

## Dependencies

<a href="http://interactjs.io" style="display: block; text-align: left;"><img alt="interact.js" src="https://c4d6f7d727e094887e93-4ea74b676357550bd514a6a5b344c625.ssl.cf2.rackcdn.com/ijs-solid.svg" height="70px" width="100%"></a>
- [Interact.js](https://interactjs.io/) - Drag-and-drop and resizing functionality </br>

<a href="https://highlightjs.org" style="display: block; text-align: center;"><img alt="highlight.js" src="https://github.com/highlightjs/highlightjs.org/raw/d142d7eba85c3725548287bf5088d59cedf66bdb/public/icon.png" height="70px"></a>
 - [Highlight.js](https://highlightjs.org/) - Syntax highlighting for code editors


- No server-side dependencies; runs entirely in the browser

## Browser Support

- Chrome, Firefox, Edge, Safari (latest versions)
- Responsive design for mobile devices (some features may be limited)

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m "Add new feature"`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.

Please include a detailed description of your changes and ensure the code follows the existing style.

## Issues

Found a bug or have a feature request? Please open an [issue](https://github.com/NellowTCS/HTMLEditor/issues) with:
- A clear description of the problem or request
- Steps to reproduce (if applicable)
- Screenshots or error messages (if relevant)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Built by [NellowTCS](https://github.com/NellowTCS)
- Powered by Interact.js and Highlight.js
- Inspired by modern web design tools for websites.
