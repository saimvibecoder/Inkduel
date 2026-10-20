# Ink Duel

A hand-drawn fighting game: 20 original fighters, each with a unique special and finisher,
four CPU difficulties (Easy, Normal, Hard, Nightmare) and a practice mode.
It is an installable web app (PWA): it gets its own icon, opens full screen and plays offline after the first visit.

## Features
- 3D fighters (three.js, bundled so it works offline). Switch back to the 2D look in Settings > Fighters.
- Story mode: 6 acts, each with 3 bodyguards and a boss with its own trait (Iron Skin, Swift, Overcharge, Bloodthirst, Second Wind, Eclipse).
- Coins and a gear shop: gloves, armor, boots and charms that work with every fighter; better pieces unlock as you clear acts.
- Shadow Form: fill the meter, then hold Block and press Special for 6 seconds of extra damage, speed and toughness.
- Arcade mode: pick a fighter and a difficulty, then beat 8 fights in a row (7 fighters, then your own Shadow as the final boss). The difficulty stays the same for the whole run. Runs are saved, lose and you can continue. Clearing earns a bonus and a badge per difficulty.
- 20 painted fighters, each with its own special and finisher
- 4 stages with their own music and hazards: Moon Dojo (breakable walls), Neon Rooftop (lightning, shock railings), Robot Factory (hydraulic press, conveyor floor), Desert Sunset (sandstorm gusts, breakable ruins)
- Parry (tap Block just before a hit), throws (Forward + Punch up close), air combos (Uppercut, then Jump and attack), wall bounces and ring-outs
- XP and upgrades: earn XP in Versus, spend it on Attack, Defence, Speed and Energy for each fighter
- Robot announcer and synthesized music (toggle in Settings)
- Cheat code: open Settings and enter godmode for unlimited XP. Deactivate turns it off and resets all XP and upgrades.
- Progress is saved in the browser on each device.

## Files
- index.html: the whole game
- manifest.webmanifest: app name, icon and colours for installing
- sw.js: offline support
- *.png: app icons (keep them at the top level, next to index.html)
- _headers: Netlify settings so updates reach players

## Deploy on Netlify
Drag this whole folder onto your site's Deploys page. Keep every file at the top level.

## Install on a phone
- Android (Chrome): open the site, tap "Install app" on the menu screen, or Chrome's menu > Install app.
- iPhone (Safari): tap Share > Add to Home Screen.

## Updating later
After changing index.html, open sw.js and change `ink-duel-v1` to `ink-duel-v2` (and so on), then redeploy.
Installed copies pick up the new version the next time they're opened online.

## Controls
Controller (Xbox, PlayStation, Switch Pro or any standard gamepad, wired or Bluetooth): left stick or D-pad move, A/Cross jump, X/Square punch, Y/Triangle kick, B/Circle special, LB/RB/LT/RT block, Start pause. In menus the D-pad moves, A selects, B goes back. In practice, View/Select switches fighter and R3 sets up the finisher.

Keyboard:
- Move: A / D or arrow keys · Jump: W · Crouch: S
- Punch: J · Kick: K · Block: hold L · Special: I · Pause: Esc or P
- Phones and tablets get on-screen controls automatically. Landscape gives the biggest stage.

Combos: Punch x3 · Crouch + Punch = uppercut · Crouch + Kick = sweep · Kick in the air = flying kick.
