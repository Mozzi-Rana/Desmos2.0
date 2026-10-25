# GraphLab

Responsive static graphing calculator. Open `index.html` locally or deploy the folder to a static host.

## Deploy
- **Vercel:** import the repository, Framework Preset `Other`, leave Build Command empty, Output Directory `.`.
- **Netlify:** publish directory `.` with no build command.
- **GitHub Pages:** publish the repository root.

## Notes
GraphLab uses Math.js from cdnjs, so expression parsing requires an internet connection. Check graph types, sliders, touch gestures, and PNG export in target browsers before production use.
