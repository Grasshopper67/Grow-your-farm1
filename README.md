# Grow Your Farm 3D

A playable 3D browser farming game made with Three.js. It can be hosted for free with GitHub Pages.

## Play locally
Open `index.html` using a modern browser with an internet connection. The game loads Three.js from jsDelivr.

## Publish on GitHub Pages
1. Upload `index.html` and `README.md` to the root of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then click **Save**.
5. Wait for GitHub Pages to publish the site. The Pages screen will show your game URL.

## Controls
- Left-click an empty soil bed to plant the selected seed.
- Left-click a ripe crop to harvest it.
- Drag to rotate the camera.
- Scroll to zoom.
- Right-click and drag to pan.
- Select or buy seeds in the left-side panel.

## Features
- 3D garden scene with camera orbit and zoom
- Five crop types with different prices, growth times, and harvest values
- Real-time crop growth
- Seed shop, coins, harvest count, and farm expansion
- Automatic browser save using localStorage

Note: This is a browser game, not a downloadable Windows executable. Three.js is loaded from a CDN, so an internet connection is required.
