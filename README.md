AR Scary House — Ready to Deploy
=================================

What's included:
- index.html : the webpage that embeds your Vectary project and includes ambient + jumpscare audio.
- Two audio files (ambient and scream) included in repo root.

How to use (GitHub Pages):
1. Create a new GitHub repository (public or private).
2. Upload all files from this package to the repository root: index.html, haunted-house-ambience-337104.mp3, 794212__aksiny_soundeditor__monster-scream-2.wav.
3. Commit and push.
4. In the repository Settings > Pages, choose the branch `main` (or `master`) and the root directory. Save.
5. GitHub Pages will publish at: https://<your-username>.github.io/<repo-name>/
6. Open that URL on your mobile phone (Safari on iPhone, Chrome on Android). Tap "Open AR" then press the AR icon inside the Vectary viewer to place the haunted house.

Notes & troubleshooting:
- The iframe uses the Vectary project link you provided. Make sure the Vectary project is published/shared publicly so the viewer loads.
- If the AR icon doesn't appear in the Vectary viewer: ensure the device/browser supports WebXR (Safari iOS for ARKit or Chrome on Android with ARCore support).
- If audio doesn't autoplay, use the "Open AR" button (first user gesture enables audio playback).
- To add more interactivity (tap inside the AR scene to open door) you'd need either:
  * Vectary scene to support postMessage listeners (advanced) OR
  * Host the model in echo3D and configure triggers there.
