# CT-sim
A static HTML page rendering a CT scanner simulator with 3D visualization.

## Features
- **Interactive 3D Visualization**: Rotate and zoom the view using mouse controls
- **CT Scanner**: Ring structure with animated rotating components
- **Patient Bed**: End device parallel to the scanner
- **Self-contained**: No external dependencies required

## Usage
Simply open `index.html` in a web browser or serve it with any HTTP server:

```bash
python3 -m http.server 8080
```

Then navigate to `http://localhost:8080/index.html`

## Controls
- **Drag**: Click and drag to rotate the view
- **Scroll**: Use mouse wheel to zoom in/out

## Components
- **Scanner**: Blue ring structure representing the CT scanner gantry
- **End Device**: Gray patient bed/table running through the scanner
