# Time Video

A lightweight Progressive Web App (PWA) that renders a customizable digital clock onto an HTML5 Canvas and streams it to a video element for floating **Picture-in-Picture (PiP)** display on desktop and mobile.

## Features

- **Picture-in-Picture Clock**: Float a live clock widget anywhere on your screen, always on top of other apps.
- **PWA Support**: Installable on iOS, Android, macOS, and Windows.
- **100% Offline Ready**: Powered by Service Worker (`sw.js`) and Web App Manifest (`manifest.json`).
- **Customizable Display**:
  - 12-Hour / 24-Hour toggle
  - Date display toggle
  - Dark / Light canvas style for the PiP window
  - Persistent user preferences saved locally

## Running Locally

Open `index.html` in any modern web browser or serve it using any local HTTP server (required for Service Worker registration):

```bash
npx serve .
# or
python3 -m http.server
```