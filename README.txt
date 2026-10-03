GN Math Silksong web game files
Source: https://gn-math.dev/?id=771

Includes the Unity WebGL build, all 100 game-asset ZIP parts,
JSZip, loading-screen files, and a local index.html launcher.
The launcher uses local assets; site advertising/tracking scripts
were omitted. This is the browser build, not a native Mac/Windows game.

To run:
1. Extract the entire folder.
2. Open Terminal in the extracted folder.
3. Run: python3 -m http.server 8000 --bind 127.0.0.1
4. Open http://localhost:8000 in your browser.

Python 3 must be installed. Keep the server running while playing.
Do not open index.html directly: browser caching requires a supported origin.
First launch extracts and caches about 2 GB of assets and needs additional memory
and disk space. Saves from GN Math will not automatically appear on localhost.

Asset integrity was checked; gameplay has not been tested locally.
