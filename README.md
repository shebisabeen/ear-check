# 🎧 Ear Check

> Ear Check is a quick, no-install tool to test your earphones and headphones — play audio through left, right, or center channels to verify stereo separation and channel balance. Fully installable as a PWA, it works offline and runs entirely in your browser using the Web Audio API.

---

**Ear Check** is a lightweight browser-based tool for testing earphones and headphones. It lets you play audio through the left, right, or center channel independently — so you can instantly verify stereo separation, detect swapped channels, and check that both ears are working correctly. Choose from a variety of synthesized sounds (bell, bird chirp, water drop, wind chime, and more), adjust volume per channel, and watch a live waveform visualizer as audio plays. Built with the Web Audio API and fully installable as a **Progressive Web App (PWA)** — complete with a service worker and web manifest — so it works offline and can be added to your home screen on any device.

## Features

- 🔊 Test **left**, **right**, and **center** audio channels independently
- 🎵 6 synthesized sound types: Bell, Bird Chirp, Bottle Blow, Water Drop, Wind Chime, Pluck
- 🎚️ Per-channel volume control
- 📊 Live waveform visualizer for each channel
- 📴 Works **offline** — no internet required after first load
- 📲 **PWA** — installable on desktop and mobile (add to home screen)
- ⚡ Zero dependencies, runs entirely in the browser

## Usage

1. Put on your earphones or headphones.
2. Click **Left**, **Center**, or **Right** to test that channel.
3. You should hear sound only in the indicated ear (or both for Center).
4. If sound plays in the wrong ear, your left/right channels may be swapped.

## Tech

- Web Audio API (oscillators, stereo panner, analyser)
- Service Worker for offline support
- Web App Manifest for PWA installability

## License

See [LICENSE](LICENSE).
