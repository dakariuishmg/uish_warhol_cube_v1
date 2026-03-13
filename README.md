# uish_warhol_cube_v1
Web Browser UI | Interactive 3D cube with six draggable HTML faces, featuring Warhol-inspired neon colors, orbital controls, zoom, and full-screen world viewing. | Web Browser Multi Desk | Web Browser Universe | Web Browser Multi-Tool 

V1 Version for as seen in my video contact me or get to develpoing.

# uish-warhol-cube

Interactive 3D cube with six draggable HTML faces, featuring Warhol-inspired neon colors, orbital controls, zoom, and full-screen world viewing.

## Description

A mesmerizing 3D cube experience that combines pop art aesthetics with modern web technologies. Each face of the cube can display different HTML content through drag-and-drop functionality. Features orbital camera controls, zoom capabilities, and a full-screen immersive viewing mode. The design pays homage to Andy Warhol's vibrant neon color palette.

## Features

- **Interactive 3D Cube**: Fully rotatable cube with smooth CSS3 3D transforms
- **Draggable HTML Faces**: Drag and drop HTML files or snippets onto any of the six cube faces
- **Warhol-Inspired Design**: Vibrant neon colors and pop art aesthetics
- **Orbital Controls**: Click and drag to rotate the cube in 3D space
- **Zoom Functionality**: Mouse wheel or pinch gestures to zoom in and out
- **Full-Screen Mode**: Immersive world viewing experience
- **iframe Sandboxing**: Safe rendering of user-provided HTML content
- **Touch Support**: Full touch event support for mobile and tablet devices
- **Responsive Design**: Adapts to different screen sizes and orientations
- **CSS Custom Properties**: Easy theme customization

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uish-warhol-cube.git
   ```

2. Navigate to the project directory:
   ```bash
   cd uish-warhol-cube
   ```

3. Open `index.html` in a modern web browser:
   ```bash
   open index.html
   # or
   python -m http.server 8000
   ```

## Usage

### Basic Controls

- **Rotate Cube**: Click and drag anywhere on the canvas
- **Zoom**: Use mouse wheel or pinch gesture (touch devices)
- **Full-Screen**: Click the full-screen button or press `F` key
- **Reset View**: Press `R` key to reset camera position

### Adding HTML Content

1. **Drag and Drop**: Drag an HTML file onto any cube face
2. **Paste HTML**: Click a face and paste HTML code directly
3. **Pre-loaded Examples**: Use the demo button to load sample content

### Customization

Edit CSS custom properties in `styles.css` to customize colors:

```css
:root {
  --neon-pink: #ff006e;
  --neon-blue: #0096ff;
  --neon-green: #00ff87;
  --neon-yellow: #ffea00;
  --neon-orange: #ff6b00;
  --neon-purple: #b100ff;
}
```

### Keyboard Shortcuts

- `F`: Toggle full-screen mode
- `R`: Reset camera to default position
- `Space`: Pause/resume auto-rotation
- `1-6`: Focus on specific cube face
- `ESC`: Exit full-screen mode

## Requirements

- Modern web browser with CSS3 3D transforms support:
  - Chrome 12+
  - Firefox 10+
  - Safari 4+
  - Edge 12+
  - Opera 15+
- JavaScript enabled
- No external dependencies or libraries required

## Browser Compatibility

| Feature | Chrome | Firefox | Safari | Edge | Opera |
|---------|--------|---------|--------|------|-------|
| 3D Transforms | ✓ | ✓ | ✓ | ✓ | ✓ |
| Drag & Drop API | ✓ | ✓ | ✓ | ✓ | ✓ |
| Touch Events | ✓ | ✓ | ✓ | ✓ | ✓ |
| Custom Properties | ✓ | ✓ | ✓ | ✓ | ✓ |
| Full-Screen API | ✓ | ✓ | ✓ | ✓ | ✓ |

## Project Structure

```
uish-warhol-cube/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and 3D transforms
├── script.js           # Core JavaScript functionality
├── README.md           # This file
├── LICENSE             # MIT License
└── examples/           # Example HTML files
    ├── example1.html
    ├── example2.html
    └── example3.html
```

## Technical Details

### Technologies Used

- **Vanilla JavaScript**: Pure JS with no frameworks or libraries
- **CSS3 3D Transforms**: Hardware-accelerated 3D rendering
- **HTML5 Drag & Drop API**: Native drag-and-drop functionality
- **CSS Custom Properties**: Dynamic theming system
- **iframe Sandboxing**: Secure HTML content rendering
- **Touch Events API**: Mobile and tablet support
- **Responsive Design**: Flexible layouts with media queries

### Security

- All user-provided HTML is rendered in sandboxed iframes
- Content Security Policy headers recommended for production
- No eval() or unsafe JavaScript execution
- XSS protection through iframe sandbox attributes

## Performance

- Hardware-accelerated CSS transforms for smooth 60fps animations
- Efficient event delegation for touch and mouse events
- RequestAnimationFrame for optimal rendering performance
- Lazy loading of iframe content

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by Andy Warhol's pop art and neon color aesthetics
- Built with modern web standards and best practices
- Thanks to the open-source community for inspiration

## Author

Your Name - [Your GitHub](https://github.com/yourusername)

## Topics

`3d-visualization` `interactive-cube` `html-viewer` `drag-drop` `orbital-controls` `neon-design` `web-art` `iframe-sandbox`

---

Made with ❤️ and neon colors
