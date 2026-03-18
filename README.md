# CS as fast as possible - Config Package
This .cfg-framework enables CS2 players to utilize advanced features and customization, which are all **legal to use on official Valve's matchmaking or Premier servers, as well as on FaceIt servers**.

Installation and usage is very easy and also shown here ↓↓

Video tutorial (version 1.0): https://youtu.be/G9hAaifu2H0<br />
Video tutorial (version 2.0): https://youtu.be/bqqCAiT1ip0

## Table of Contents
* [Features](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#features)
* [Screenshots](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#screenshots)
* [Installation](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#installation)
* [How to use the CSAFAP Config Package](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#how-to-use-the-csafap-config-package)
* [Customization](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#customization)
* [Pricing](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#pricing)
* [Known Issues](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#known-issues)
* **[FAQ (Frequently asked Questions)](https://github.com/FNScence/CSAFAP-config-package/blob/main/README.md#faq-frequently-asked-questions)**

  
- [Version History](https://github.com/FNScence/CSAFAP-config-package/blob/main/version_history.md)

## Features
- **Practice Mode** (in-game offline map guides featuring 1.000+ line-ups on all 9 competitive maps) 
- **Automatic line-ups** (instant smokes + wallbangs)
- **(W-)Jumpthrow binds** (just like in CSGO)
- **Snap-Tap** / Null-bind movement input
- **De-subtick binds** (WASD + jump)
- **Crouch-jump bind**
- **Pro-Crosshair and Viewmodel Options** (dynamically copy settings from the top20 teams)
- **Rapid-Fire mode for pistols**
- **Better Follow-Recoil mode**

All features are accessible via the in-game radio wheels, by using the four keybinds set in `csafap/main.cfg`, or by binding them directly in `csafap/main.cfg`.

## Screenshots
![guide](https://github.com/user-attachments/assets/8a3bee1b-2d5b-43a9-90a6-044e9bbe8fc3)
↑ Map Guides featured on ALL MAPS

![guide2](https://github.com/user-attachments/assets/76a7ecba-2f97-445e-a179-7eeaa18f7f81)
↑ Try 1.000+ line-ups and other tricks in-game

![practice](https://github.com/user-attachments/assets/008dbfb1-8247-470a-865b-1d1bd9a5236c)
↑ Quick access to practice commands (scroll mwheel for more options)

![autolineups](https://github.com/user-attachments/assets/d7240c14-75a1-47eb-991b-9effd9997612)
↑ Automatically line-up smokes on official servers...

![window_fast](https://github.com/user-attachments/assets/676fc7c2-e3d6-453c-be5a-04aa675e3d27)
↑ ... to land pixel-perfect smokes extra fast ...

![autoexec](https://github.com/user-attachments/assets/423c5446-4671-4f07-9564-a83b7e418ae4)
↑↓ ... or throw executes as if you were Valorant's Brimstone (not actual in-game footage)
![autoexec2](https://github.com/user-attachments/assets/613b7f8f-1864-489f-867c-28dbb700ef56)

![snaptap](https://github.com/user-attachments/assets/3c414e50-e07a-4af8-ae70-d5793f6a69a3)
↑ Snap-Tap (null binds) input option - does NOT trigger a kick

![crosshair](https://github.com/user-attachments/assets/3e235e49-2051-41b2-b978-5dde0213775a)
↑ Crosshair + Viewmodels from top20 teams

![follow-recoil](https://github.com/user-attachments/assets/1e25788b-5c92-4fdd-bab3-ed6af9edf78c)
↑ Better Follow-Recoil mode - shows spray-pattern indicated by a green dot when spraying
  
## Installation
- **Step 1:**
  Download and place the whole folder named `csafap` in the config folder of the CS2 installation, at this path:<br />
		`C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

- **Step 2:**
  Inside the `csafap`-directory, copy the `csgo`-folder and paste it at this path:<br />
		`C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\`

- **Step 3:**
  Open the main config of this package `csafap\main.cfg` with an editor of your choice (e.g. notepad++).<br />
  **ENTER YOUR SENSITIVITY AT THE TOP!** Change the keybinds to your preference.<br />
  If you want to use auto line-ups on faceit for example, you need to enable the faceit binds first, by removing the `// ` at the start of it's line.<br />
  If you don't want to use a feature, disable the keybind by adding `// ` at the start of it's line.
  

- **Step 4:**
  Run the main config in-game. Add exactly these launch options: <br />
  `+exec csafap/main -testscript "../../csgo/cfg/csafap/addons/.vtest"`

- **Done!**

## How to use the CSAFAP Config Package
- **How to use RADIO WHEELS:**<br />
Press one of the FOUR KEY BINDS to access a RADIO WHEEL.
Then, hover your mouse over the tile you want to use and PRESS AND RELEASE THE SAME KEY AS BEFORE again (clicking does nothing).

>  Default Keybinds:<br />
>  -  **H**: CT Line-ups (Smokes & Wallbangs)
>  -  **J**: T Line-ups (Smokes & Wallbangs)
>  -  **K**: Pro crosshairs, Rapid fire pistols, Better Follow-Recoil and Snap-Tap/Null binds
>  -  **M**: Map Selection + Practice Mode

  
- **How to use AUTO LINE-UPS:**<br />
Open the map wheel and select your current map.
Then, open the T-/CT-wheel and select the line-up you want (as described above) and throw your nade as usual. You can find 2 additional pages by scrolling your mouse-wheel while the radio-wheel is open.

- **How to use PRACTICE-MODE:**<br />
  Open the map wheel and select ENABLE PRAC-MODE, then choose the map you want. Use the bind you set for the auto line-up wheel (default: **J**) to access many practice mode options (incl. CT/T-side line-up switch).

- **How to use RAPID FIRE and FOLLOW-RECOIL mode:**<br />
  Rapid fire shoots pistols as fast as possible while holding mouse1. Follow recoil draws a second crosshair (green dot) to indicate the spray pattern.<br />
  Assign your personal keybinds in the required section at the bottom of `csafap/main.cfg`. By default, this mode is deactivated. Press the assigned keybind (default: right-alt) to toggle (you'll hear an activation/deactivation sound), or cycle the mode in the crosshair wheel (bottom left tile) between rapid fire, follow-recoil and both modes. Changing the mode will enable it as well.

## Customization
- **Change keybinds**

  > Open `csafap/main.cfg` with an editor of your choice and edit the desired keybinds.

- **Disable Features**

  > Open `csafap/main.cfg`, and put `// ` at the start of the line, where the unwanted feature is bound to a key.

- **Create your own Auto Line-up**

  > A detailed video explaination can be found at [THIS TIMESTAMP](https://youtu.be/G9hAaifu2H0?si=3U4mB8vV8oWa-x8g&t=669).
  >
  > - Step 1:
  Find the desired angle using `getpos` in-game.
  > - Step 2:
  Calculate desired values for the commands yaw and pitch (as described in FAQ Q9) and create an alias within `csafap/maps/<map_name>/<map_name>.cfg`.
  > - Step 3:
  Create a label within the language-file `platform_english.txt`.
  > - Step 4:
  Call this label on an empty radiotile within `csafap/maps/[mapname]_labels.cfg`.
  > - Step 5:
  Call the alias (which you created in step 2) within `csafap/maps/[mapname]_cmd.cfg` using the same radio tile as in the previous step.

## Pricing
I provide this config package and it's support absolutely for **free**! <br />
[Updates](https://github.com/FNScence/CSAFAP-config-package/blob/main/version_history.md) will follow as long as I have fun doing so. The continued development took 500+ hours and I've gotten 3 donations so far. If you are up for giving back, I'd be very thankful for it.

Donation Options:
-  [My CS2 Trade Link](https://steamcommunity.com/tradeoffer/new?partner=107947867&token=iBykTMd5)
-  [Youtube Membership](https://youtube.com/channel/UCdF_lTc-yX8BvVBo_oGYrHQ/join)<br />
-  [Youtube Super Thanks](https://www.youtube.com/@FNScence/videos) (on any of my videos)

**Thanks to supporters of this project** 🧡<br />
kek2181 <br />
luke <br />
irene762 <br />

## Known Issues
- **Fix: cfg rejected by game bug**  
  Launch your personal autoexec config using the launch option `+exec cfgname` and at the bottom of that config use `exec csafap/main`.
  Also don't exec the configs while already on a server. Run them from the main menu (or, as explained above, on game launch) instead.

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

- Q5: I get an error when trying to `exec csafap/main`...?
  > If the following error happens, you have saved the CSAFAP-config package at the wrong path.
  >
  > ```
  > exec csafap/main
  > [InputService] exec: couldn't exec '{*}cfg/csafap/main.cfg', unable to read file
  > ```
  >
  > Most likely you accidentally placed it in the directory for the old game CS:GO (instead of CS2), or you didn't take the csafap-folder out of the github repo folder.
  >
  > `..\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\csafap` ✅
  >
  > `..\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\csafap` ❌ 
  >
  > `..\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\csafap-config-package\csafap` ❌ 
  >
  > If you are on Liunx, make sure you wrote `exec csafap/main` correctly, as it is case sensitive.

- Q6: How to make the binds work on azerty (french) keyboard layout?
  > Make sure to use scancode binds instead of letters when adjusting the binds in `csafap/main.cfg`.
  > 
  > Here are [all qwerty keys and their respective scancodes](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_scancode.h#L218) and this is a [scancode bind converter](https://totalcsgo.com/binds/converter) which might be helpful.
  
- Q7: Why does my sensitivity change to 1.0 and doesn't switch back my playing sens?
  > Set your sensitivity at the top of `exec csafap/main`. Auto sensitivity detection got patched by Valve.

- Q8: What is Snap-Tap/Nulls? Should I use it? Will I get kicked for using it?
  > It's best to try them it yourself and see if you prefer it over default movement.
  >
  > **- nullWASD:** After holding down the initial strafe key, pressing the opposite strafe key will deactivate the initial one. For counter-strafing, this only corrects the human error of not letting go of the initial strafe key, but you still have to release the opposite one at the correct timing. It is good for extremely fast jiggles (holding down one strafe key and quickly tapping the opposite one), not too useful in CS though (maybe for pistol round AD spam).

  > **- desubtick:** Very similar to default movement, but the WASD movement inputs will wait for the next tick to register instead of being subticked and registered immediatelly. Some users report a more cs:go-like movement feel.

  > I showcased the key inputs for each of these at [this timestamp of the video](https://youtu.be/G9hAaifu2H0?si=ZAl2vxdoX8eZ_Ktn&t=63). Note that auto counter-strafe configs were patched and don't work anymore!
  
- Q9: How to calculate yaw/pitch values?
  > $$ X = \frac{a}{s \cdot m\\_yaw} $$

  > X ... desired yaw/pitch value
  > 
  > a ... angle you need to move [°]
  >
  > s ... sensitivity (we're using s = 1.0)
  >
  > m_yaw ... adjust your mouse sensitivity only on the X axis (we're using m_yaw = 0.022)
  >
  > **Note:** If you want to include custom line-ups, because we are now (since v.2.15) zeroing the vertical viewangle at -89° instead of at 0°, you need to add `+4045.45454545` to your calculated pitch value.

- Q10: The radio tiles are empty/blank. How to get the text working?
  > Make sure to follow step 2 of the installtion instruction, by copying the `csgo`-folder from the `csafap`-directory, to your game's installation path.
  > This places `../csafap/csgo/resource/platform_english.txt` in the correct folder. Edits to this file require a game-restart to take effect.
  > 
  > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource\platform_english.txt`
  >
  > You can always start debugging by checking the current binds by typing `cl_radialradio` into the console and see the autofill options.
  >
  > Note: Custom wheels do not work on workshop maps!

- Q11: It falsely selects the radio tile next to the one I am aiming at.
  > This is an issue with cursor displacement when playing on windowed or fullscreen-windowed while NOT on native resolution.
  > 
  > Solution option 1:
  > 
  > Change desktop resolution to in-game res before launching the game. This [CS2 launcher powershell script](https://old.reddit.com/r/GlobalOffensive/comments/1g56n34/cs2_launcher_script_update/) can do that automatically for you.
  >
  > Solution option 2:
  > 
  > Before selecting the radiowheel tile, make sure you move your mouse over the tile you want to choose after the text disappears.
  >
  > Solution option 3:
  > 
  > It seems like the cursor gets displaced to the right after pressing the keybind again. Make sure to place your mouse more to the left on the tile. Pulling outside of the circle helps, as the tiles are extended to the edge of the screen at that moment.

- Q12: Why can I only move my crosshair up/down and not side-to-side?
  > This might happen when zeroing gets interupted and not reset for whatever reason.<br />
  > Use this console command for instant fix: `m_yaw 0.022`

- Q13: Why can't I stop moving forward after W-Jumpthrow?
  > When using the W-JT bind, `-forward` has to be used delayed, otherwise the bind would be a simple jumpthrow without the 30 u/s forward velocity.
  > 
  > Switching to your knife by pressing `3` - or moving your crosshair - should reset this action. If not, you might have issued `+forward` multiple times without canceling it multiple times.
  >
  > **Short term fix:** Use this in console: `forward -999 0 0`
  > 
  > **Long term fix:** Make sure the same command is saved in `csafap/addons/-forward.cfg`, which should be called by an alias bound to the key `3`, as well as `mouse_x` and `mouse_y` after using the WJT bind.

- Q14: I can't jump!!1! How to reset jumping binds?
  > The recent [update of 28th of October 2024](https://steamcommunity.com/games/CSGO/announcements/detail/4522269457743085933) patched our multi-input methods, meaning only the first action of a bind will be issued and the rest ignored.
  > That means, using a pre-patch de-subtick jump bind now will use `+jump` but NOT issue `-jump`, resulting in you not being able to jump anymore afterwards. Typing `-jump` into the console will fix this issue, but you might need to use it multiple times, if you spammed the old-dated jumping bind multiple times: `jump -999 0 0`.

  > Now use working jump binds, by either resetting your binds to default (`bind mwheeldown +jump`) or by using the newest version of the CSAFAP config package.

- Q15: How to bind custom commands to the radiowheel (without using the config package)?
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

- Q16: How to practice instant spawns? Where can I find teleport commands to those spawns?
  > Option 1:
  > Launch the CSAFAP-practice-mode, and use the CT-wheel-bind (default: H) to teleport directly to the desired spawn. Use the mouse-scrollwheel to access more options while the radiowheel is open. Note that the numbering might differ from those of other practice services.
  > 
  > Option 2:
  > Offline with bots, set `mp_randomspawn 0` and `bind m "mp_restartgame 1"`. You can save a position by taking the first two values from `getpos` and the thrid from `getpos_exact`.
  > 
  > You can also find `setpos`-commands to every spawn in the description of videos, where I show instant smokes.
  > [Youtube playlists](https://www.youtube.com/@FNScence/playlists) sorted by maps.
  > Here are examples for Ancient [CT-side](https://youtu.be/fd6gRZDOCps?si=qLWsm4GrhhVyXXpC&t=7) and [T-side](https://youtu.be/klyGW-IUca4?si=dRQ8qaAShzDSY0GG&t=3), Dust2 [T-side](https://youtu.be/XGQDTpFwkKM?si=oTVD5aypaWxZqgrz&t=55), Nuke [CT-side](https://youtu.be/v204dZrtFbo?si=lLB9Z4ohute6-8rq&t=84) and [T-side](https://youtu.be/tImJDxKe70o?si=mAKxnBdTGIZ9TUrH&t=17), Anubis [CT-side](https://youtu.be/fullFlkzB0U?si=MYDkPpzPqFDqqEbj&t=55) and [T-side](https://youtu.be/wURJvMSSbF0?si=Bd7TZ9BmWbJOAVsD&t=164), Inferno [CT-side](https://youtu.be/5MzQnaHtjl4?si=dymht4z6wghpO1EE&t=8), Mirage [T-side](https://youtu.be/klBqOVbdckQ?si=GendkMN1315tFBTf&t=53), Train [T-side](https://youtu.be/r_NkXOjYiIM?si=7rZNnNfyRmbTTloF&t=8).

- Q17: On scoreboard, the right-click is not working.
  > If you are using JT, WJT, rapid fire or follow-recoil features, you also need to use `bind mouse2 +M2`. To make the scoreboard work with that, we use `cl_scoreboard_mouse_enable_binding +M2`.<br />
  > If you are not using those features and use the default `bind mouse2 +attack2`, you need to use `cl_scoreboard_mouse_enable_binding +attack2`. You need to run this command every time after the rest loads, so either put it at the end of `csafap/addons/loader.cfg` or prevent the crosshair modes from loading in the first place by disabling `exec csafap/crosshair/rapid_followrecoil` within `csafap/addons/loader.cfg` (by inserting `//` at the start of the line).

- Q18: Why is rapid fire and/or follow recoil mode not working?
  > Firstly, make sure you are setting all the requirements for it (using launch option `-testscript "../../csgo/cfg/CSAFAP/addons/.vtest"` and setting `ef_...` binds in `csafap/main.cfg`).<br />
  > Secondly, these features are framerate dependent. By default they work at >150 FPS. If you get less, you need to rename `csafap/crosshair/rapid_followrecoil_lessthan150FPS.cfg` to `csafap/crosshair/rapid_followrecoil.cfg`.
  >
  > Rapid fire is only enabled for pistols, so take out your pistol (by pressing the keybind you assigned ef_slot2 to) after activating the feature.

- Q19: Why is it that when I use crosshair and rapid fire, the grenades fire automatically as soon as I switch to them??
  > You need to use the `ef_...` binds towards the bottom of `csafap/main.cfg`, as they are a requirement for follow-recoil and rapid fire features.

- Q20: Why is my console getting spammed with `Unknown command: W!...`?
  > The launch option `-testscript "../../csgo/cfg/csafap/addons/.vtest"` spamms these alias every frame. If the alias are not assigned on game launch, this will happen and other binds using the ticker function (including movement and mouse binds) will not work.<br />
  > We initialize these alias on game launch by using the launch option `+exec csafap/main`, but if a command is too long (for example the `alias reset_crosshair "..."` at the bottom of `csafap/main.cfg`) the exec queue will exit causing this issue. To debug this, you can take out the vtest launch option and check console output directly after game launch or `exec csafap/main` to look for potential errors after loading the config initially.

- Q21: Why do movement keys and mouse buttons no longer work (and I cannot select team in offline mode) after installing? 
  > Same cause as in Q20 above.
  >
  > If you use `bind mouse1 +M1; bind mouse2 +M2` (from line 22 of `csafap/main.cfg`), you need to make sure you are also using this **exact** launch option `-testscript "../../csgo/cfg/CSAFAP/addons/.vtest"`.

- Q22: How to uninstall the config package?
  > Simply overwrite the keybinds used by this config package (`1, 2, 3, N, H, J, K, M, space, Q, W, A, S, D`) and don't use the launch options `+exec csafap/main -testscript "../../csgo/cfg/csafap/addons/.vtest"` anymore.
  >
  > To make right-click work on scoreboard again after using ticker features, you need to use this command once: `cl_scoreboard_mouse_enable_binding +attack2`

If any questions remain, join my discord and feel free to ask in the `#csafap-config`- or `#help`-channel:

> Join the **CS AFAP DISCORD SERVER** [HERE](https://discord.gg/cs-as-fast-as-possible-992407294866370681).


[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
