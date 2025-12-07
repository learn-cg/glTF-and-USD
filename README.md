# glTF-and-USD

A simple, interactive web-based viewer for glTF (GL Transmission Format) 3D models.

## Features

- 🎨 Interactive 3D model viewer
- 📁 Load your own .gltf or .glb files
- 🖱️ Intuitive controls (rotate, zoom, pan)
- 📱 Responsive design for desktop and mobile
- ⚡ Fast and lightweight using Three.js

## How to Use

1. Open `index.html` in a modern web browser
2. Click "Load Your glTF File" to select a .gltf or .glb file from your computer
3. Interact with the 3D model:
   - **Rotate**: Left-click and drag
   - **Zoom**: Scroll mouse wheel
   - **Pan**: Right-click and drag

## Running Locally

Simply open the `index.html` file in your web browser. No build process or server required!

Alternatively, you can serve it with a simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## About glTF

glTF (GL Transmission Format) is a royalty-free 3D file format designed for efficient transmission and loading of 3D models and scenes. It's often referred to as the "JPEG of 3D" for the web.

### Where to Find glTF Models

- [Khronos glTF Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models)
- [Sketchfab](https://sketchfab.com/features/gltf) - Download models in glTF format
- [Google Poly Archive](https://poly.pizza/)

## Technologies Used

- [Three.js](https://threejs.org/) - 3D graphics library
- HTML5, CSS3, JavaScript (ES6 modules)

## Browser Compatibility

Works in all modern browsers that support ES6 modules and WebGL:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

See LICENSE file for details.