REWIND Reference Effects Lab — PWA + Video

INSTALL:
1. Upload all files in this folder to the SAME directory on an HTTPS static host.
2. Open the deployed index.html URL in current Chrome on Android.
3. Use the in-app Install App button if it appears, or Chrome ⋮ > Install app / Add to Home screen.
4. Open the app once while online so the service worker can cache the app shell.

IMPORTANT:
- PWA install/service worker do not work from file:// or a local HTML file. HTTPS hosting is required (localhost is allowed for development).
- Keep index.html, manifest.json, sw.js and both PNG icons together in the same directory.
- Video effects preview while the video plays. Export records the processed canvas as WebM in real time.
- Audio is included only if the browser supports captureStream() for video elements; some mobile browsers may export without audio.
- Browser codec support varies. Current Chrome is recommended.
- Photo editing and PNG export remain available.
