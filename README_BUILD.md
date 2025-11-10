Learn Latvian — macOS Electron GitHub-ready repository

Contents:
- main.js, preload.js
- src/ (React app with voice features)
- public/index.html
- package.json (configured for electron-builder)
- build-icons/icon.icns (placeholder)
- .github/workflows/build-macos.yml (CI builder)

To build locally on macOS:
1. npm install
2. npm run build
3. npm run dist

To build on GitHub Actions:
1. Push the repository to GitHub (main branch)
2. The workflow will run and produce artifacts in `dist/` which will be uploaded to the Actions run as artifacts.

Note: Replace build-icons/icon.icns with a proper macOS icon if you want a custom app icon.
