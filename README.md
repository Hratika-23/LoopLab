# LoopLab

A colourful, funky storefront for **3D printed keychains**.

**Live site:** https://hratika-23.github.io/looplab/

## Features

- **Live printer animation:** a cute 3D printer prints a heart keychain layer by layer, pops it off the bed and starts again in a new colour.
- **3D product cards:** every keychain is a real 3D model you can drag to rotate.
- **Focus view:** tap a keychain to open it large with the background dimmed, then rotate and zoom it and pick a colourway.
- **Name-tag customiser:** choose a shape (tag, circle, heart, star, cloud, bone), base and text colours, a finish (matte, silk, glow) and up to 12 characters of text, with a live 3D preview.
- **Cart:** quantities, a free-shipping progress bar and a saved cart (demo checkout).
- **Responsive:** designed for phones and laptops.

## Tech

A single `index.html` file: HTML, CSS and JavaScript, with [three.js](https://threejs.org/) (r128) for the 3D models. Fonts: Anybody, Rethink Sans and Martian Mono from Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Note

This is a demo storefront. The keychain models are built in code for this site, and checkout is not connected to payments.
