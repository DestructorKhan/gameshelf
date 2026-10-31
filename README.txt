Game Shelf: deploy to GitHub Pages

1. Create a repo (for example "game-shelf") on GitHub.
2. Upload every file in this folder to the repo root: index.html, manifest.webmanifest, icon-192.png, icon-512.png, apple-touch-icon.png.
3. Repo Settings > Pages > Source: "Deploy from a branch", Branch: main, folder: / (root). Save.
4. After about a minute the app is at https://<your-username>.github.io/game-shelf/
5. On iPhone: open that link in Safari, tap Share > Add to Home Screen.
6. Move your games over: in the Claude version tap Export JSON, then on the new site tap Import JSON and choose the file.

Notes: your shelf is stored in that browser only (localStorage). Use Export JSON now and then as a backup.
