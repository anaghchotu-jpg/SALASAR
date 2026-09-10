# SALASAR — Final Netlify Build

## Features
- Rajasthan / Salasar Balaji inspired cinematic visual direction
- Generated temple hero artwork in `assets/salasar-hero.png`
- Mobile + desktop responsive design
- Playable quiz and pattern challenge
- VAJRA RUSH racing game with keyboard, pointer and mobile controls
- Solo progression with XP, lives, energy, streaks, levels and ranks
- Multiplayer room layer using WebRTC via PeerJS
- Create/join room codes and live race data sync
- Leaderboard UI
- Events, Vault and Profile
- Netlify Forms rating form
- Location section at the bottom with Salasar, Churu District, Rajasthan
- Links to Google Maps and Rajasthan Tourism

## Multiplayer
The demo uses PeerJS/WebRTC so two browsers can establish a peer-to-peer data connection after creating/joining a room. For production, replace the demo signaling/provider with a managed realtime backend and server-authoritative game state if you need competitive anti-cheat multiplayer.

## Rating email
The form is named `salasar-rating`. In Netlify, enable form notifications and route submissions to your private notification email.

## Deploy
Upload this folder to Netlify or connect it to a Git repository. The site is static and does not require a build command.
