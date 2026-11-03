# THE CURSED — Halloween Escape

A mobile-friendly, first-person Halloween horror game built with Three.js.

## Play
The game is designed for a browser. Open it through GitHub Pages or a local web server; ES modules do not work reliably from `file://`. Three.js loads from jsDelivr, so an internet connection is required.

## GitHub Pages
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. Wait for the Pages deployment:
   https://cobra546.github.io/Haunted-Halloween/

## Controls
- **Desktop:** WASD move, mouse look, Shift sprint, F flashlight, E interact, I inventory, Esc pause.
- **Mobile:** left joystick to move, drag the right side to look, and use INTERACT / LIGHT / SPRINT / ITEMS / PAUSE.

## Current game features
- First-person mansion, forest and abandoned town environments.
- Ground floor, upstairs bedrooms, basement cellar and a hidden underground passage.
- Two main mansion escape choices: solve four difficult coded locks or find the pickaxe and break the side window.
- A hidden cellar route that requires finding the iron key upstairs and opening the concealed latch.
- Four flashlight cells with seven minutes of use per cell (28 minutes total); battery drains only while the light is on.
- Pocket inventory, clues, cursed forest computer and town gate objective.
- A distant apparition that watches from far away and causes temporary in-game control glitches. It does not attack or kill the player.
- Atmospheric lighting, flickering candles, fog, creaking-house effects, fear meter, jumpscares and nightmare sequences.

## Technical notes
This is an evolving browser-game prototype. The mansion architecture and puzzles are implemented in the single `index.html` file. The visuals use procedural Three.js geometry and lighting rather than downloaded texture packs. The game has been syntax-checked, but still needs hands-on browser playtesting on desktop and Android before calling it fully polished.
