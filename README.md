# My AI Studio — Starter v0.1

This is a beginner-friendly, responsive web prototype that can later be installed as a PWA.

## Included in this first version
- Responsive dashboard
- Local image upload preview
- Image-to-video prompt builder (prompt only; no rendering yet)
- Browser text-to-speech
- Music idea builder (brief only; no music rendering yet)
- Local demo chat
- Video script outline starter

## Run it
You can open `index.html` directly for a quick preview. For installable/PWA behavior, host it over HTTPS.

## Free publishing with GitHub Pages
1. Create/sign in to GitHub.
2. Create a public repository named `my-ai-studio`.
3. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
4. Open repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
6. Wait for the published URL shown in Pages. Open it on your phone and use the browser's Add to Home Screen option.

## Important
This is a front-end prototype. It does not yet connect to paid or free hosted AI inference APIs. Never put private API keys in browser JavaScript. The next development step is adding a secure backend and selecting available free-tier model providers.
