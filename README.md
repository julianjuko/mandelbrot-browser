# Mandelbrot Set Explorer

This is a web-based explorer for the Mandelbrot set, utilizing WebGL for high-performance rendering.

## How to use

1. Open the HTML file in a web browser that supports WebGL 2.
2. Click and drag to pan around the Mandelbrot set.
3. Use the scroll wheel to zoom in and out.

## Features

- High-precision Mandelbrot set rendering.
- Colored using an escape time algorithm with a randomized starting hue.
- Panning and zooming functionality.
- Responsive design - the explorer fills the entire browser window and adjusts to window resizing.

## Implementation Details

This application is implemented using WebGL for graphics rendering. It uses a fragment shader to calculate the Mandelbrot set, with a resolution equal to the pixel resolution of the canvas.

The color of each point in the set is determined by the number of iterations it takes for that point to escape the Mandelbrot set, as determined by the escape time algorithm. The starting hue of the coloring is randomized on each page load or window resize, providing a varied visual experience each time the explorer is used.
