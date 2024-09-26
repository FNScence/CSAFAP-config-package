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
  - Automatic Map Detection (credit and thanks to [-Cap1taL-](https://github.com/eLecCap1taL))

- ***New with version 1.2:*** (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))
  - (W-) Jumpthrow-binds (desubticked; exactly like pre-patch 8/20/2024)
  - Desubticked movement binds (mwheel-jump for bhop, WASD, etc.)
  - Longjump Bind (aka Crouch-/Duck Jump)
  - Jump-bug Bind
  - Auto stop defuse when shooting

- ***New with version 1.3:***
  - Thera support (instant dropper, top mid and B main smokes for CT-side)
  - Overpass support (AWP wallbangs, mid runboost-incendiary)

- ***New with version 1.4:***
  - Added additional AWP wallbangs for Mirage, Nuke and Overpass (thanks to [Kodalim](https://github.com/sneakybikimeh))
  - Added keybind for default movement
  - Improved user-friendly custimization options

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
- **Change keybinds**

  > Open CSAFAP/MAIN.cfg with an editor of your choice and edit the desired keybinds.

- **Disable Features**

  > Open CSAFAP/MAIN.cfg, and put `// ` at the start of the line, where the unwanted feature is bound to a key.

- **Find your own Line-up**

  > A detailed video explaination can be found at [THIS TIMESTAMP](https://youtu.be/G9hAaifu2H0?si=3U4mB8vV8oWa-x8g&t=669).
  >
  > - Step 1:
  Find the desired angle using `getpos` in-game.
  > - Step 2:
  Calculate desired values for the commands yaw and pitch and create an alias within `CSAFAP/logic.cfg`.
  > - Step 3:
  Create a label within the language-file `platform_english.txt`.
  > - Step 4:
  Call this label on an empty radiotile within `CSAFAP/maps/[mapname]_labels.cfg`.
  > - Step 5:
  Call the alias (which you created in step 2) within `CSAFAP/maps/[mapname]_cmd.cfg` using the same radio tile as in the previous step.

## FAQ (Frequently asked Questions):

- Q1: Is this allowed on MM, PREMIER?
  > Yes! This config package works purely on in-game commands which work under SV cheats 0, and a modified language text-file.

- Q2: Is this allowed on Faceit?
  > **Yes!** The CSAFAP config package **IS ALLOWED** for your normal ranked PUGS.
  >
  > See respoonses from faceit support about yaw/pitch commands and custom radiowheels [HERE](https://imgur.com/a/NkOc7VZ).
  >
  > See respoonses from faceit's Community Manager about [Null binds (aka snap-tap)](https://www.reddit.com/r/FACEITcom/comments/1ea2tgz/comment/leim41n/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button).
  >
  > See respoonses from faceit's Community Manager about Automatic counter-strafe configs, [Part 1](https://imgur.com/a/automatic-counter-strafe-config-allowed-on-faceit-yes-dcOlGBK) and [Part 2](https://www.reddit.com/r/FACEITcom/comments/1etp7di/comment/lifb8hf/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button).
  >
  > They are not allowed in higher leagues like ESEA, ESL, etc. as their rules are more strict and prohibit the use of the alias command in general. [Source](https://x.com/FACEIT_Darwin/status/1817926901689917525).

- Q3: How to install and run/execute a config in CS2?
  > - Step 1:
  Save the config at this path
  >
  > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
  > To create a new one, copy an existing .cfg file, rename it and edit its content.
  > - Step 2:
  > Execute it by either typing `exec filename` (when using a config named `filename.cfg`) into the in-game console, or by typing the same thing into an existing config that gets executed automatically.

- Q4: How to make an autoexec (automatically executing config at game start)?
  > In your steam library, right-click CS2 > properties > general > under launch options insert `+exec filename`.

- Q5: I get an error when trying to `exec CSAFAP/MAIN`...?
  > If the following error happens, you have saved the CSAFAP-config package at the wrong path.
  >
  > ```
  > exec CSAFAP/main
  > [InputService] exec: couldn't exec '{*}cfg/CSAFAP/main.cfg', unable to read file
  > ```
  >
  > Most likely you accidentally placed it in the directory for the old game CS:GO, instead of CS2. Here is how to differentiate them:
  >
  > `..\steamapps\common\Counter-Strike Global Offensive\csgo\cfg` ❌ 
  >
  > `..\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg` ✅

- Q6: Which movement (strafing) config should I use?
  > They all have their up- and downsides. It's best to try them out yourself and see which ones you prefer.
  >
  > Personally, I would recommend `autostop AD`, which is simple and effective. Even if you counter-strafe yourself, which you should, it will correct basically any mistakes.
  > If you're confident in your own counter-strafing, you can try `autostop WS nulls AD`, which will help when getting caught in diagonal movement and the nulls help a little extra.
  
- Q7: How to calculate yaw/pitch values?
  > $$ X = \frac{a}{s \cdot m\\_yaw} $$

  > X ... desired yaw/pitch value
  > 
  > a ... angle you need to move [°]
  >
  > s ... sensitivity (we're using s = 1.0)
  >
  > m_yaw ... adjust your mouse sensitivity only on the X axis (we're using m_yaw = 0.022)

- Q8: The radio tiles are empty. How to get the text working?
  > Make sure to place "platform_english.txt" in the correct folder and use the english language in-game. Edits to this file require a game-restart to take effect.
  > 
  > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource\platform_english.txt`

- Q9: Why do I stop running when using the jumpthrow binds?
  > Autostop configs interfer with (W-)JT binds. Make sure to use default movement (for JT), or movement configs with default W-bind (for W-JT).

- Q10: Why does my quickswitch (or whatever you bound Q to) not work anymore?
  > The instant window flash on Anubis overwrites the keybind of Q. If you don't want to use it, search for it in MAIN.cfg (CTRL+F) and change/delete it.

- Q11: How to bind custom commands to the radiowheel (without using the config package?
  > You can find the most basic set of configs to bind your own radio commands on my Discord in the ***pinned messages*** of the `#auto-lineup-config`-channel.
  > Join the **CS AFAP DISCORD SERVER** [HERE](https://discord.gg/cs-as-fast-as-possible-992407294866370681).
  > - Step 1:
  Within your own auto-exec, create a bind which opens the radio wheel, and switches between two phases (labels and commands):
  > ```
  > bind J +wheel_1					// Keybind to custom wheel_1
  >
  > alias +wheel_1 "exec CustomRadio/radio_labels"		// Call custom text			
  > alias -wheel_1 "+radialradio; bind J +wheel_2"		
  > alias +wheel_2 "exec CustomRadio/radio_cmd"		// Call custom commands
  > alias -wheel_2 "-radialradio; bind J +wheel_1"
  > ```
  > - Step 2:
  Create a label within the language-file `platform_english.txt`:
  >
  >    `"CFG_NOCLIP"          "NOCLIP \n without HUD \n  \n  \n  \n  \n "`
  > - Step 3:
  Call this label on an empty radiotile within a separate config, e.g.: `CustomRadio/radio_labels.cfg`:
  >
  >    `cl_radial_radio_tab_0_text_1 "#CFG_NOCLIP"`
  > - Step 4:
  Enter the desired commands within another separate config, e.g.: `CustomRadio/radio_cmd.cfg` using the same radio tile as in the previous step.
  >
  >    `cl_radial_radio_tab_0_text_1 cmd";noclip;toggle cl_drawhud 0 1;toggle r_drawviewmodel 0 1;`
  > 
  > This line has to end with `;` and cannot contain any `"` after `cmd";`. To use commands which need `"`, within your own autoexec create an alias:
  > 
  > `alias do_something "bind c "toggle sv_noclipspeed 50 800""`
  > 
  > ... and call that one instead (within `CustomRadio/radio_cmd.cfg`):
  > 
  > `cl_radial_radio_tab_0_text_1 cmd";do_something;`

- Q12: How to create custom binds bypassing `cl_allow_multi_input 0` (bypassing the patch of 8/20/2024) without using the package?
  >
  > Video explaination by [Leiti](https://www.youtube.com/@xLeiti) [HERE](https://www.youtube.com/watch?v=spEEtXVFwLM).
  > - Step 1:
  Create a separate config containing the commands you want to bind to the key, e.g.: `jumpthrow.cfg`:
  >
  > `+jump;-attack;-attack2;-jump`
  > - Step 2:
  Within your own autoexec, create an alias (calling the config from the previous step in a special way) and bind it to a key:
  >
  > ```
  > alias do_something "echo "jumpthrow" | exec;"
  > bind KEY do_something
  > ```

- Q13: Can my viewmodel influence the instant flash line-ups?
  > No, the only settings that can influence auto line-ups are `sensitivity` and `m_yaw`, which you should enter at the top of `CSAFAP/MAIN.cfg`.

- Q14: How to practice instant spawns? Where can I find teleport commands to those spawns?
  > The free way of doing it is going offline with bots, setting `mp_randomspawn 0` and `bind m "mp_restartgame 1"`. You can save a position by taking the first two values from `getpos` and the thrid from `getpos_exact`.
  > You can also find `setpos`-commands to every spawn in the description of videos, where I show instant smokes.
  > [Youtube playlists](https://www.youtube.com/@FNScence/playlists) sorted by maps.

- Q15: Which ones are the better jumpthrow binds: Keyboard macros or the config version?
  > The config version.
  >
  > They are desubticked and work just like pre-patch 8/20/2024. Until the `echo | exec`-method gets patched again, disable any macros you might have set up for jumpthrows within your keyboard software.

- Q16: How to uninstall the config package?
  > Simply overwrite the keybinds used by this config package (`1, 3, N, H, J, K, space, Q, W, A, S, D`) and don't execute `CSAFAP/MAIN` anymore.


If any questions remain, join my discord and feel free to ask in the `#auto-lineup-config`-channel:

> Join the **CS AFAP DISCORD SERVER** [HERE](https://discord.gg/cs-as-fast-as-possible-992407294866370681).
