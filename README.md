# Mini AR Studio — Interactive WebAR Showcase

Mini AR Studio is a browser-based augmented reality prototype. It uses a phone or computer camera to recognize the **Hiro fiducial marker** and anchor a small animated 3D scene to that marker.

When the marker is visible, the experience displays one of three selectable 3D objects:

- **Orbit Cube** — a rotating indigo cube with a gold cone accent and a cyan ground ring.
- **Mini Planet** — a blue planet with a pink orbit ring and an animated moon.
- **Crystal** — a rotating purple octahedron on a small pedestal.

The three buttons in the on-screen object selector switch between the models without reloading the camera experience.

## Live demo

After enabling GitHub Pages, the project is available at:

`https://<your-github-username>.github.io/<your-repository-name>/`

## How to use

1. Open the live HTTPS URL on a modern mobile browser.
2. Allow camera access when prompted.
3. Display or print a **Hiro marker** (the marker preset used by AR.js).
4. Point the camera at the marker and keep it flat, visible, and well lit.
5. Use the three buttons at the bottom of the screen to switch between the 3D objects.

For best results, show the marker on another screen or print it at a reasonable size. Avoid glare, low light, and extreme camera angles.

## Built with

- **A-Frame 1.5.0** — declarative 3D scene creation and rendering.
- **AR.js 3.4.5** — browser-based marker tracking and camera-based AR.
- **HTML, CSS, and JavaScript** — responsive overlay interface and object selection.
- **GitHub Pages** — static HTTPS hosting.

## Run locally

Camera access is generally restricted to secure contexts. Use the deployed HTTPS GitHub Pages URL, or run the project through a local development server such as VS Code Live Server (`http://localhost` is treated as a secure context by modern browsers).

## Project scope and limitations

This is a **marker-based WebAR demo**, not a native Snap Spectacles, Snap OS, or Lens Studio application. It demonstrates a basic AR workflow: camera access, marker detection, anchoring 3D content, simple animation, and user-driven model selection.

The experience depends on browser camera permissions, device/browser compatibility, and the external A-Frame and AR.js CDN scripts. An internet connection is required to load those libraries. Performance and camera behavior may vary by device.

## Repository contents

- `index.html` — complete WebAR experience, styling, 3D models, and interaction logic.
- `README.md` — project overview, setup instructions, technology stack, and limitations.
