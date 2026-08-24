# AudioLink — WebRTC audio-only

Static GitHub Pages-ready WebRTC audio streamer.

## Features
- WebRTC audio only
- `echoCancellation`
- `noiseSuppression` / voice-isolation style filtering
- `autoGainControl`
- Auto-bass enhancement
- Compressor for more consistent voice level
- Generated receiver URL uses `?room=...`
- Receiver view contains only an `<audio>` element; no video/UI

## Deploy
Upload `index.html` to GitHub Pages and open it over HTTPS.

## Important
The current version uses PeerJS Cloud for signaling. The media itself is WebRTC peer-to-peer when possible.

Browsers may require a user gesture before audio can autoplay on a receiver device. If that happens, tap the page once.
