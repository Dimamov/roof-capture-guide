# Roof Capture Guide

A mobile-first guided photo workflow for roof estimate capture. Each required photo and framing check must be completed before the next step unlocks. The app records a measured reference and at least one ground dimension, then lets the user save each photo and a JSON measurement summary.

## Run

Open `dist/index.html` in a browser, or serve `dist/` with a static web server. Camera capture works best over HTTPS on an iPhone. No backend is required; photos remain in the current browser session until saved.

## Current limitations

The framing checks are user confirmations. The app rejects images below 1000 × 700 pixels but cannot verify roof visibility, perspective, blur, or measurement accuracy automatically. It does not calculate roof area.

## Install on iPhone

Open the [live app](https://roof-capture-guide.coral-ball-5810.chatgpt.site) in Safari. Tap Share, then **Add to Home Screen**. Open the new icon to run it like an app. Photos are held only during the current session, so save them before leaving the capture.
