# CS as fast as possible - Config Package
This .cfg-framework enables CS2 players to utilize advanced features and customization, which are all **legal to use on official Valve's matchmaking or Premier servers, as well as on FaceIt servers**.

Installation and usage is very easy and also shown here ↓↓

Video tutorial: https://youtu.be/G9hAaifu2H0

## Features & Version History
- ***Base features (version 1.0):***
  - Automatic Smoke line-ups
  - <s>Instant Flash line-ups</s>
  - Movement Configs (auto counter-strafe and nulls)

- ***New with version 1.1:***
  - <s>Automatic Map Detection</s> (credit and thanks to [-Cap1taL-](https://github.com/eLecCap1taL))

- ***New with version 1.2:*** (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))
  - <s>(W-) Jumpthrow-binds (desubticked; exactly like pre-patch 8/20/2024)</s>
  - Desubticked movement binds (mwheel-jump for bhop, WASD, etc.)
  - <s>Longjump Bind (aka Crouch-/Duck Jump)</s>
  - <s>Jump-bug Bind</s>
  - <s>Auto stop defuse when shooting</s>

- ***New with version 1.3:***
  - Thera support (instant dropper, top mid and B main smokes for CT-side)
  - Overpass support (AWP wallbangs, mid runboost-incendiary)

- ***New with version 1.4:***
  - Additional AWP wallbangs for Mirage, Nuke and Overpass (thanks to [SneakyBikiMeh](https://github.com/sneakybikimeh))
  - Keybind for default movement
  - <s>Bind for R to release middle click nades while also reloading</s>
  - Improved user-friendly customization options

- ***New with version 1.5:***
  - Two additional wheels accessible via mouse wheel, when the smoke/flash wheel is already open
  - Ancient: CT instant smokes for mid and B doors from all 5 spawns (open smoke wheel, then scroll mouse wheel up/down)

- ***New with version 1.6:***
  - Auto sensitivity detection (you don't have to enter it anymore) (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))
  - Option for a specific strafing config to launch with the game

- ***New with version 1.7:***
  - Removed instant flash feature ([patched on 2nd of October](https://www.counter-strike.net/newsentry/4674264042200250912))
  - Split wheels into CT and T line-ups

- ***New with version 1.8:***
  - Reverted to manual map selection (default bind: M), since the command `dumpparticlelist` is now locked behind `sv_cheats`

- ***New with version 1.9:***
  - Removed multi-input binds ([patched on 28th of October](https://steamcommunity.com/games/CSGO/announcements/detail/4522269457743085933)]
    (de-subtick movement binds are still available)
  - Reverted back to JT and WJT binds using radialradio methods
  - Fixed 15 smoke line-ups, which were broken by the recent update to jumping

## Installation
- **Step 1:**
  Download and place the whole folder named `CSAFAP` in the config folder of the CS2 installation, at this path:
  
		C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg

- **Step 2:**
  Place the modified language file `platform_english.txt` in the resource folder, at this path:

		C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource

- **Step 3:**
  Open the main config of this package `CSAFAP\MAIN.cfg` with an editor of your choise (e.g. notepad++).
  
  Change the keybinds to your preference.

  If you don't want to use a feature, disable the keybind by adding `// ` at the start of it's line.

- **Step 4:**
  Run the main config in-game. Either type `exec CSAFAP/main` directly into the console, use the same line in a config you already use, or use launch option `+exec CSAFAP/MAIN`.

  **Done!**

## How to use the CSAFAP Config Package
- **Step 1:**
  Press one of the THREE KEY BINDS to access a RADIO WHEEL

  Default Keybinds:
  -  **H**: CT Line-ups (Smokes & Wallbangs)
  -  **J**: T Line-ups (Smokes & Wallbangs)
  -  **K**: Movement Configs
  
- **Step 2:**
  Hover your mouse over the tile you want to use and PRESS THE SAME KEY AS IN STEP 1 again.

- **Step 3:**
  Throw your line-up.


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
  > See responses from faceit support about yaw/pitch commands and custom radiowheels [HERE](https://imgur.com/a/NkOc7VZ).
  >
  > See responses from faceit's Community Manager about [Null binds (aka snap-tap)](https://www.reddit.com/r/FACEITcom/comments/1ea2tgz/comment/leim41n/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button).
  >
  > See responses from faceit's Community Manager about Automatic counter-strafe configs, [Part 1](https://imgur.com/a/automatic-counter-strafe-config-allowed-on-faceit-yes-dcOlGBK) and [Part 2](https://www.reddit.com/r/FACEITcom/comments/1etp7di/comment/lifb8hf/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button).
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

- Q6: Why does my sensitivity change to 1.0 and doesn't switch back my playing sens?
  > Make sure you're NOT using the command `host_writeconfig` within your autoexec.

- Q7: Which movement (strafing) config should I use?
  > They all have their up- and downsides. It's best to try them out yourself and see which ones you prefer, but here is a detailed list of what they do:
  >
  > **- autostopAD:** Counter-strafes automatically when letting go of initial strafe key and also stopps fast when overlapping both strafe keys. **I consider this the best option**, because it corrects any imperfect counter-strafes from you and works the same if you still counter-strafe manually (which you should do).
 
  > **- nullAD:** After holding down the initial strafe key, pressing the opposite strafe key will deactivate the initial one. For counter-strafing, this only corrects the human error of not letting go of the initial strafe key, but you still have to release the opposite one at the correct timing. It is good for extremely fast jiggles (holding down one strafe key and quickly tapping the opposite one), not too useful in CS though (maybe for pistol round AD spam).

  > **- autonullAD:** Combines the previous two, so it will auto counter-strafe when releasing the initial strafe key, but it will work the same as nulls/snap-tap when pressing both at the same time.

  > **- autostopWS_nullAD:** This version auto counter-strafes your forward/backward movement, so it will help immensely if you get caught in +W or diagonal movement, while the nulls help with AD counter-strafing. This might be the best version if you're very confident in your own AD counter-strafing (and like the null functionality).

  > **- autostopWASD:** Counter-strafes automatically in 8 directions. On some occasions (pressing W+A, then releasing A and only running forward without moving the mouse in between before also letting go of W) will result in a faulty sidestep. Because of this reason, **I don't recommend using this version**.

  > **- desubtick:** Very similar to default movement, but the WASD movement inputs will wait for the next tick to register instead of being subticked and registered immediatelly. Some users report a more cs:go-like movement feel.

  > I showcased the key inputs for each of these at [this timestamp of the video](https://youtu.be/G9hAaifu2H0?si=ZAl2vxdoX8eZ_Ktn&t=63).
  
- Q8: How to calculate yaw/pitch values?
  > $$ X = \frac{a}{s \cdot m\\_yaw} $$

  > X ... desired yaw/pitch value
  > 
  > a ... angle you need to move [°]
  >
  > s ... sensitivity (we're using s = 1.0)
  >
  > m_yaw ... adjust your mouse sensitivity only on the X axis (we're using m_yaw = 0.022)

- Q9: The radio tiles are empty. How to get the text working?
  > Make sure to place "platform_english.txt" in the correct folder and use the english language in-game. Edits to this file require a game-restart to take effect.
  > 
  > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource\platform_english.txt`

- Q10: Why do I stop running when using the jumpthrow binds?
  > Autostop configs interfer with (W-)JT binds. Make sure to use default movement (for JT), or movement configs with default W-bind (for W-JT).

- Q11: How to bind custom commands to the radiowheel (without using the config package?
  > You can find the most basic set of configs to bind your own radio commands on my Discord in the ***pinned messages*** of the `#auto-lineup-config`-channel.
  > Join the **CS AFAP DISCORD SERVER** [HERE](https://discord.gg/cs-as-fast-as-possible-992407294866370681).
  > - Step 1:
  Within your own auto-exec, create a bind which opens the radio wheel, and switches between two phases (labels and commands):
  > ```
  > bind J +wheel_1						// Keybind to custom wheel_1
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

- Q12: How to practice instant spawns? Where can I find teleport commands to those spawns?
  > The free way of doing it is going offline with bots, setting `mp_randomspawn 0` and `bind m "mp_restartgame 1"`. You can save a position by taking the first two values from `getpos` and the thrid from `getpos_exact`.
  > You can also find `setpos`-commands to every spawn in the description of videos, where I show instant smokes.
  > [Youtube playlists](https://www.youtube.com/@FNScence/playlists) sorted by maps.
  > Here are examples for Ancient [CT-side](https://youtu.be/fd6gRZDOCps?si=qLWsm4GrhhVyXXpC&t=7) and [T-side](https://youtu.be/klyGW-IUca4?si=dRQ8qaAShzDSY0GG&t=3), Dust2 [T-side](https://youtu.be/XGQDTpFwkKM?si=oTVD5aypaWxZqgrz&t=55), Nuke [CT-side](https://youtu.be/v204dZrtFbo?si=lLB9Z4ohute6-8rq&t=84) and [T-side](https://youtu.be/tImJDxKe70o?si=mAKxnBdTGIZ9TUrH&t=17), Anubis [CT-side](https://youtu.be/fullFlkzB0U?si=MYDkPpzPqFDqqEbj&t=55) and [T-side](https://youtu.be/wURJvMSSbF0?si=Bd7TZ9BmWbJOAVsD&t=164), Inferno [CT-side](https://youtu.be/5MzQnaHtjl4?si=dymht4z6wghpO1EE&t=8), Mirage [T-side](https://youtu.be/klBqOVbdckQ?si=GendkMN1315tFBTf&t=53).

- Q13: Which ones are the better jumpthrow binds: Keyboard macros or the config version?
  > The ones from the config are desubticked, but only trigger on button release. The macro version is instant, but not pixelperfect, as they are not de-subticked (inconsistent).
  >
  > For normal Jumpthrows, a combination would be the best option. Use macros like shown in [THIS VIDEO](https://youtu.be/yqtJZFQSF_U) using desubticked actions from the config package, like so:
  ```
	alias +jump_ "echo "CSAFAP/addons/+jump" | exec;"
	alias -jump_ "echo "CSAFAP/addons/-jump" | exec;"

	bind "space" +jump_
	bind "f8" "echo "CSAFAP/addons/-attack" | exec;"
	bind "f9" "echo "CSAFAP/addons/-attack2" | exec;"
  ```
  >
  > For W-Jumpthrows, use the radialradio version (which is implemented in the CSAFAP config package; default bind `N`), as mixing de-subticked `+forward` binds with macros will result in a different forward speed everytime.

- Q14: How to uninstall the config package?
  > Simply overwrite the keybinds used by this config package (`1, 2, 3, N, H, J, K, space, Q, W, A, S, D`) and don't execute `CSAFAP/MAIN` anymore.


If any questions remain, join my discord and feel free to ask in the `#auto-lineup-config`-channel:

> Join the **CS AFAP DISCORD SERVER** [HERE](https://discord.gg/cs-as-fast-as-possible-992407294866370681).
