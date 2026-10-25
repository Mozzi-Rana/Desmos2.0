# GraphLab — Graphing Calculator

A lightweight, client-side graphing calculator. No build step or server-side runtime is required.

## Features

- 2D functions, implicit equations, inequalities, points, polar and parametric curves
- Constants and animated sliders
- Basic expression calculator
- Interactive pan, zoom, touch pinch, and coordinate tracing
- Experimental 3D surface plotting
- PNG graph export, color controls, light/dark theme, and browser autosave
- Responsive layout for desktop and mobile

## Run locally

Open `index.html` in a modern browser. An internet connection is currently required to load Math.js from cdnjs.

## Deploy

### Vercel
1. Upload the contents of this folder to a Git repository.
2. Import the repository into Vercel.
3. Choose **Other** as the framework preset, leave the build command and output directory empty/default, and deploy.

### Netlify
1. Create a new site from the repository.
2. Set the publish directory to `.` and leave the build command empty.
3. Deploy.

### GitHub Pages
Push the contents to a repository, then enable Pages for the branch and root folder.

## Notes

- Graph expressions and preferences are stored in this browser's local storage; they are not uploaded to a server.
- Math.js is loaded from cdnjs, so expression parsing/calculation needs internet access. If the CDN is unavailable, the app's graphing features will not initialize.
- The 3D surface renderer is a lightweight visualizer, not a scientific 3D plotting engine.
