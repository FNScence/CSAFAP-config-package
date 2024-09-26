# CS as fast as possible - Config Package
This .cfg-framework enables CS2 players to utilize advanced features and customization, which are all **legal to use on official Valve's matchmaking or Premier servers, as well as on FaceIt servers**.

Installation and usage is very easy and also shown here ↓↓

Video tutorial: https://youtu.be/G9hAaifu2H0

## Features & Version History
- ***Base features (version 1.0):***
  - Automatic Smoke line-ups
  - Instant Flash line-ups
  - Movement Configs (auto counter-strafe and nulls)

- ***New with version 1.1:***
  - Automatic Map Detection (credit and thanks to "-Cap1taL-" - https://github.com/eLecCap1taL)

- ***New with version 1.2:*** (credit and thanks to "Leiti" - https://youtube.com/@xLeiti)
  - (W-) Jumpthrow-binds (desubticked; exactly like pre-patch 8/20/2024)
  - Desubticked movement binds (mwheel-jump for bhop, WASD, etc.)
  - Longjump Bind (aka Crouch-/Duck Jump)
  - Jump-bug Bind
  - Auto stop defuse when shooting

- ***New with version 1.3:***
  - Thera support (instant dropper, top mid and B main smokes for CT-side)
  - Overpass support (AWP wallbangs, mid runboost-incendiary)


## Installation
- **Step 1:**
  Download and place the whole folder named `CSAFAP` in the config folder of the CS2 installation, at this path:
  
		C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg

- **Step 2:**
  Place the modified language file `platform_english.txt` in the resource folder, at this path:

		C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource

- **Step 3:**
  Open the main config of this package `CSAFAP\MAIN.cfg` with an editor of your choise (e.g. notepad++).
  
  **IMPORTANT: EDIT LINE 6 TO ENTER YOUR PLAYING SENSITIVITY.** You can also change the keybinds in the following lines.
  If you don't want to use a feature, disable the keybind by adding `// ` at the start of it's line.

- **Step 4:**
  Run the main config in-game. Either type `exec CSAFAP/main` directly into the console, use the same line in a config you already use, or use launch option `+exec CSAFAP/MAIN`.

  **Done!**

## How to use the CSAFAP Config Package
- **Step 1:**
  Press one of the THREE KEY BINDS to access a RADIO WHEEL (default: H - instant flash, J - smokes, K - secondary smokes).
  
- **Step 2:**
  Hover your mouse over the tile you want to use and PRESS THE SAME KEY AS IN STEP 1 again.

- **Step 3:**
  Throw your line-up.

- **(Step 4):**
  When using INSTANT BUG FLASHES (default keybind: H), immediatelly after releasing MOUSE1, PRESS 1 (or 2) to switch to your gun.
  This will automatically turn away from the flash and pre-aim enemy positions.


## Customization
- Change keybinds
  Open CSAFAP/MAIN.cfg with an editor of your choice and edit the desired keybinds


## Frequently asked Questions

- Q1: Is this allowed on MM, PREMIER?
  > Yes! This config package works purely on in-game commands which work under SV cheats 0, and a modified language text-file.

- Q2: Is this allowed on Faceit?
  > Yes! It's allowed for your normal ranked PUGS. See respoonses from faceit support [HERE](https://imgur.com/a/NkOc7VZ)

- Q3: How to calculate yaw/pitch values?
  > $$ X = \frac{a}{s \cdot m\\_yaw} $$

  > X ... desired yaw/pitch value
  > 
  > a ... angle you need to move [°]
  >
  > s ... sensitivity (we're using s = 1.0)
  >
  > m_yaw ... adjust your mouse sensitivity only on the X axis (we're using m_yaw = 0.022)

- Q4: The radio tiles are empty. How to get the text working?
  > Make sure to place "platform_english.txt" in the correct folder and use the english language in-game. Edits to this file require a game-restart to take effect.
  > 
  > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource\platform_english.txt`

- Q5: Why do I stop running when using the jumpthrow binds?
  > Autostop configs interfer with (W-)JT binds. Make sure to use default movement (for JT), or movement configs with default W-bind (for W-JT).

- Q6: Why does my quickswitch (or whatever you bound Q to) not work anymore?
  > The instant window flash on Anubis overwrites the keybind of Q. If you don't want to use it, search for it in MAIN.cfg (CTRL+F) and change/delete it.

- Q7: How to uninstall the config package?
  > Simply overwrite the keybinds used by this config package (`1, 3, N, H, J, K, space, Q, W, A, S, D`) and don't execute `CSAFAP/MAIN` anymore.


If any questions remain, join my discord and feel free to ask in the `#auto-lineup-config`-channel:

> [JOIN THE CS AFAP DISCORD SERVER](https://discord.gg/cs-as-fast-as-possible-992407294866370681)
