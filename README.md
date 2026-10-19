# Ink Duel

A stickman fighting game: 20 original fighters, each with a unique special and finisher,
four CPU difficulties (Easy, Normal, Hard, Nightmare) and a practice mode.
It is an installable web app (PWA): it gets its own icon, opens full screen and plays offline after the first visit.

## Files
- index.html: the whole game
- manifest.webmanifest: app name, icon and colours for installing
- sw.js: offline support
- icons/: app icons
- _headers: Netlify settings so updates reach players

## Deploy on Netlify
Drag this whole folder onto your site's Deploys page. Keep every file and the icons folder.

## Install on a phone
- Android (Chrome): open the site, tap "Install app" on the menu screen, or Chrome's menu > Install app.
- iPhone (Safari): tap Share > Add to Home Screen.

## Updating later
After changing index.html, open sw.js and change `ink-duel-v1` to `ink-duel-v2` (and so on), then redeploy.
Installed copies pick up the new version the next time they're opened online.

## Controls
- Move: A / D or arrow keys · Jump: W · Crouch: S
- Punch: J · Kick: K · Block: hold L · Special: I · Pause: Esc or P
- Phones and tablets get on-screen controls automatically. Landscape gives the biggest stage.

Combos: Punch x3 · Crouch + Punch = uppercut · Crouch + Kick = sweep · Kick in the air = flying kick.
