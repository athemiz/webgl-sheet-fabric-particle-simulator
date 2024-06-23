# WebGL Particle Sheet Simulator

This project is a dynamic 2D particle sheet simulator using WebGL. It demonstrates cloth-like physics with interactive features such as dragging particles, cutting springs, and adjusting simulation parameters in real-time.

## Features

- WebGL-based rendering for efficient performance
- Interactive particle manipulation (dragging)
- Spring cutting mechanism
- Real-time adjustment of simulation parameters:
  - Gravity
  - Damping
  - Spring stiffness
  - Maximum spring tension before breaking
- Color-coded spring tension visualization

## Getting Started

### Prerequisites

- A modern web browser that supports WebGL (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Running the Simulation

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Interact with the simulation using your mouse:
   - Left-click and drag to move particles
   - Right-click and drag to cut springs
4. Use the sliders in the top-left corner to adjust simulation parameters.

## Development

If you want to modify the code and test it locally, it's recommended to use a local web server. You can use Python's built-in HTTP server or any other local server solution.

Using Python (Python 3):

```
python -m http.server
```

Then open your browser and navigate to `http://localhost:8000`.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- This project uses WebGL for rendering.
- Inspired by various cloth simulation techniques and interactive physics demonstrations.

