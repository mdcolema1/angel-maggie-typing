# Angel & Maggie's Typing Adventure

Install Node.js 22. In this folder run `npm install` then `npm run dev`. Deploy by committing this folder to the `main` branch of a GitHub repository and enabling GitHub Pages > Source > GitHub Actions.

## What is included
- Separate Angel and Maggie profiles
- Approved chibi anime character art and Star General Store scene
- Transparent white-free individual product previews and illustrated shelves
- Keypress-triggered animated arm overlays for the typing companion
- Individual typing lessons, saved stars, store purchases and parent audits
- Original browser speech voice selection, preview, and optional webcam eye tracking

## Security and storage
Progress is local to each browser via localStorage. Parent password `Azara` is embedded in browser code, so it is a convenience control, not secure authentication. To sync devices or protect star edits, use real authentication and server-side authorization in a later release.

Webcam eye tracking requires HTTPS and an external WebGazer library, plus camera permission. Browsers may block autoplay voice until user interaction.

The original approved art is the visual reference. The interactive forearm movements are a lightweight 2D overlay, not a fully articulated rig. Purchased hairstyles and outfits are inventory/equip entries and are not yet redrawn as character-worn animation layers.
