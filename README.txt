MOTO RUSH X — PHASE 4
3D sport-bike model integration

FILES
- index.html: game
- Moto_Rush_X_Sport_Bike.glb: external 3D model loaded by GLTFLoader

HOW TO RUN
1. Keep index.html and Moto_Rush_X_Sport_Bike.glb in the same folder.
2. Host the folder on a static web host (for example Netlify) or run it through a local web server.
3. Open the page in a modern browser with internet access. Three.js and GLTFLoader are loaded from jsDelivr.
4. Tap START RIDE. Hold ACCEL; steer left/right; use BRAKE/TURBO. Camera button switches view.

NOTES
- The game is still a browser prototype, not an Android APK.
- The model loads asynchronously. If it fails to load, the original procedural bike/rider stays visible.
- On successful load, the supplied GLB replaces the procedural bike/rider. The model's orientation and scale may need fine tuning after visual testing.
- Traffic cars remain procedural in this phase; separate realistic car/rider assets can be integrated next.
- This package has not been tested on the user's device.
