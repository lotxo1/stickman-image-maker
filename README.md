# Stickman Image Maker

[![Made with pollinations.ai](https://raw.githubusercontent.com/pollinations/pollinations/main/packages/ui/src/brand/badge-made-with.svg)](https://pollinations.ai/?ref=badge)

Describe a scene and get a 16:9 stickman cartoon image in a consistent style, ready for faceless YouTube videos.

**Live app:** https://lotxo1.github.io/stickman-image-maker/

## How it works

- Visitors sign in with their own Pollinations account ("Connect User Wallets" / Bring Your Own Pollen, OAuth with PKCE).
- Each image is paid with the visitor's own Pollen. The app only allows cheap image models:
  - FLUX.1 Schnell (0.002 Pollen)
  - Z-Image Turbo (0.004 Pollen)
  - FLUX.2 Klein (0.005 Pollen)
- One single `index.html` file, no server, no secret keys. Only the public App Key (`pk_`) is in the code.

## Features

- 3 styles: classic white background, colorful background, chalkboard
- Optional fixed seed for a more consistent look across images
- Download button and a gallery of the images made in the session
- Works on phones
