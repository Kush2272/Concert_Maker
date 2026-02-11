Put your audio files in this folder and list them in `tracks.json`.
If you open `index.html` directly (without a local server), also update `tracks.js`.

How to use:
1. Copy songs into `music/` (example: `song1.mp3`).
2. Edit `music/tracks.json` and add each file name.
3. Edit `music/tracks.js` with the same songs (needed for `file://` mode).
4. In the app, click `Reload Songs`.
5. Pick a song from `Choose from /music`.

Notes:
- Supported formats depend on your browser (mp3/wav/ogg/m4a are common).
- Use file names only (for example: `track.mp3`), not absolute paths.
