# Invert Camera

A tiny p5.js sketch that shows your webcam with inverted colors.

## What it does
- Opens the webcam with p5.js `createCapture(VIDEO)` at 320x240.
- Draws each frame on a 390x240 canvas and applies p5's `INVERT` filter to the whole canvas.

## Run it
Camera access needs either `localhost` or HTTPS. Two ways:
- Serve the folder locally (for example `python3 -m http.server`) and open `http://localhost:8000/invertCamera.html`, or
- Publish with GitHub Pages and open the HTTPS link.

Your browser will ask for permission to use the camera.

## Notes
- Loads p5.js and ml5.js from CDN (`@latest`). The code does not actually use ml5.
