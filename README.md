# CS as fast as possible - Config Package
This .cfg-framework enables CS2 players to utilize advanced features and customization, which are all **legal to use on official Valve's matchmaking or Premier servers, as well as on FaceIt servers**.

Installation and usage is very easy and also shown here ↓↓

Video tutorial (version 1.0): https://youtu.be/G9hAaifu2H0

Video tutorial (version 2.0): https://youtu.be/bqqCAiT1ip0

## Features
- **Practice Mode** (in-game offline map guides featuring 1.000+ line-ups on all 9 competitive maps) 
- **Automatic line-ups** (instant smokes + wallbangs)
- **Snap-Tap** / Null-bind movement input
- **De-subticked Jump** (better bhopping)
- **(W-)Jumpthrow binds** (de-subticked, more consistent than manual throws)
- **Viewmodel Options** (lefthanded knife while everything else righthanded or vice versa)

All features are accessible via the in-game radio wheels, by using the four keybinds set in `CSAFAP/MAIN.cfg`.

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
↑ ... to land pixel-perfect smokes extra fast

![snaptap](https://github.com/user-attachments/assets/3c414e50-e07a-4af8-ae70-d5793f6a69a3)
↑ Snap-Tap (null binds) input option - does NOT trigger a kick

## Version History
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
  - <s>Auto sensitivity detection (you don't have to enter it anymore)</s> (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))
  - Option for a specific strafing config to launch with the game

- ***New with version 1.7:***
  - Removed instant flash feature ([patched on 2nd of October 2024](https://www.counter-strike.net/newsentry/4674264042200250912))
  - Split wheels into CT and T line-ups

- ***New with version 1.8:***
  - Reverted to manual map selection (default bind: M), since the command `dumpparticlelist` is now locked behind `sv_cheats`

- ***New with version 1.9:***
  - Removed multi-input binds ([patched on 28th of October 2024](https://steamcommunity.com/games/CSGO/announcements/detail/4522269457743085933))
    (de-subtick movement binds are still available)
  - Reverted back to JT and WJT binds using radialradio methods
  - Fixed 15 smoke line-ups, which were broken by the recent update to jumping

- ***New with version 2.0:***
  - Added new Practice Mode (accessible via map-wheel)
    - Includes in-game map guides for all 9 competitive maps (loaded dynamically, thanks to [Leiti](https://github.com/xLeiti/Annotations-Chunk-Loader-Cs2))
    - Map wheel becomes changelevel commands + disable practice mode button
    - CT wheel becomes spawn point teleports
    - T wheel becomes practice commands
  - Added Train support (T-side instant smokes)
  - Added Inferno instant FaZe smoke support
  - Added viewmodel options
  - General QoL improvements
  - Removed STYKO wallbang ([patched on 14th of November 2024](https://store.steampowered.com/news/app/730/view/4458095069430284352))
  - Removed autostop configs ([patched on 24th of November 2024](https://store.steampowered.com/news/app/730/view/6500469346429581891))

- ***New with version 2.1:***
	- Adjusted to new TRAIN map changes
		- updated instant smoke line-ups (practice mode & auto line-up)
		- updated spawn teleports (practice mode)
		- updated Ivy Solo Flash (they closed the cubby at back 6)
		- added wallbangs from white halls to ivy, gate and bombtrain

- ***New with version 2.2:***
	- Added a few T-side line-ups for Train (after the first pro matches on the map)

- ***New with version 2.3:***
	- Fixed a few T-side line-ups for Train (pop dog to gate, T-stairs to lower B)
 	- Exchanged radio tile position of Vertigo with Train
  	- Added Ancient Cave to B site solo god flash

- ***New with version 2.4:***
  	- Added Train Instant Sandwich Smokes to Instant-Lineups
  	- Added ~10 new line-ups to various maps in practice mode
  	- Default radio messages are now supported (`bind key +radialradio; bind key +radialradio2; bind key +radialradio3`)

- ***New with version 2.5:***
  	- Fixed Practice Mode (removed chunk_loader and automatic map detection, [broken by Valve on 27th of February 2025](https://store.steampowered.com/news/app/730/view/529839807839339585); split annotations into CT- and T-Side)
	- Fixed de-subtick binds (thanks to [Leiti](https://www.youtube.com/@xLeiti))
	- Re-added manual sensitivity entry within `CSAFAP/main.cfg`

 - ***New with version 2.6:***
  	- Added/changed practice mode line-ups for Train, Anubis, Inferno

 - ***New with version 2.7:***
  	- Changed auto-line-ups for Mirage Instant Window (spawns 2-5) to land faster (thanks to [-Cap1taL-](https://discord.com/channels/992407294866370681/1274522315853533338/1361582970393329834))

 - ***New with version 2.8:***
  	- Fixed a bug, where T-wheel would be stuck on Mirage line-ups (after selecting Mirage Instant Window smoke without resetting and selecting another map).
  
 - ***New with version 2.9:***
  	- Added auto line-ups suggested from [user feedback](https://discord.com/channels/992407294866370681/1277052590764326943/1370957519043956756).

- ***New with version 2.10:***
	- Shifted map selection one tile to realign with premier veto screen
   	- Added auto line-up for Overpass banana to B-stairs molotov
 
- ***New with version 2.11:***
   	- Added auto line-up for Overpass Instant Monster Smokes
 
- ***New with version 2.12:***
   	- Changed auto line-up Overpass Mid Runboost-Incendiary to regular Mid Incendiary

- ***New with version 2.13:***
   	- Added Mirage 5 Smoke A Exec to auto line-ups

## Installation
- **Step 1:**
  Download and place the whole folder named `CSAFAP` in the config folder of the CS2 installation, at this path:
  
		C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg

- **Step 2:**
  Inside the `CSAFAP`-directory, copy the `csgo`-folder and paste it at this path:

		C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\

- **Step 3:**
  Open the main config of this package `CSAFAP\MAIN.cfg` with an editor of your choice (e.g. notepad++).
  
  ENTER YOUR SENSITIVITY AT THE TOP! Change the keybinds to your preference.

  If you don't want to use a feature, disable the keybind by adding `// ` at the start of it's line.

- **Step 4:**
  Run the main config in-game. Either type `exec CSAFAP/main` directly into the console, use the same line in a config you already use, or use launch option `+exec CSAFAP/MAIN`.

- **Done!**

## How to use the CSAFAP Config Package
- **How to use RADIO WHEELS:**
Press one of the FOUR KEY BINDS to access a RADIO WHEEL.
Then, hover your mouse over the tile you want to use and PRESS AND RELEASE THE SAME KEY AS BEFORE again (clicking does nothing).

>  Default Keybinds:
>  -  **H**: CT Line-ups (Smokes & Wallbangs)
>  -  **J**: T Line-ups (Smokes & Wallbangs)
>  -  **K**: Snap-Tap and Viewmodel Settings
>  -  **M**: Map Selection + Practice Mode

  
- **How to use AUTO LINE-UPS:**
Open the map wheel and select your current map.
Then, select the line-up you want (as described above) and throw your nade as usual. You can find 2 additional pages by scrolling your mouse-wheel while the radio-wheel is open.

- **How to use PRACTICE-MODE:**
  Open the map wheel and select ENABLE PRAC-MODE, then choose the map and side you want. Use the bind you set for the T-wheel (default: **J**) to access many practice mode options (incl. CT/T-side line-up switch).

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
  >
  > If you are on Liunx, make sure you wrote `exec CSAFAP/MAIN` correctly, as it is case sensitive.

- Q6: How to make the binds work on azerty (french) keyboard layout?
  > Make sure to use scancode binds instead of letters when adjusting the binds in `CSAFAP/MAIN.cfg`.
  > 
  > Here are [all qwerty keys and their respective scancodes](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_scancode.h#L218) and this is a [scancode bind converter](https://totalcsgo.com/binds/converter) which might be helpful.
  
- Q7: Why does my sensitivity change to 1.0 and doesn't switch back my playing sens?
  > Set your sensitivity at the top of `exec CSAFAP/main`. Auto sensitivity detection got patched by Valve.

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

- Q10: The radio tiles are empty. How to get the text working?
  > Make sure to place "../csafap/csgo/resource/platform_english.txt" in the correct folder and use the english language in-game. Edits to this file require a game-restart to take effect.
  > 
  > `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource\platform_english.txt`

- Q11: Why do I stop running when using the jumpthrow binds?
  > This is caused by the W-bind of NullWASD. Make sure to use default movement (for JT), or change `csafap/movement/nullWASD.cfg` to use `bind W +forward` instead. I recommend using a Macro for Jumpthrow and the bind from this config for WJT. Here is how to set up a JT macro: https://youtu.be/yqtJZFQSF_U

- Q12: Why can't I stop moving forward after W-Jumpthrow?
  > The (W-)Jumpthrow binds (based on radiowheels) have anti-synergy with autostop configs, so don't use autostopWASD together with W-JT (autstopAD would be fine for example, since it doesn't mess with the W bind).
  > 
  > When using the W-JT bind from version 1.9, `-forward` has to be used delayed, otherwise the bind would be a simple jumpthrow without the 30 u/s forward velocity.
  > 
  > Switching to your knife by pressing `3` or moving your crosshair should reset this action. If not, you might have issued `+forward` multiple times without canceling it multiple times.
  >
  > **Short term fix:** Use this in console: `forward -999 0 0`
  > 
  > **Long term fix:** Make sure the same command is saved in `CSAFAP/addons/-forward.cfg`, which should be called by an alias bound to the key `3`, as well as `mouse_x` and `mouse_y` after using the WJT bind.

- Q13: I can't jump!!1! How to reset jumping binds?
  > The recent [update of 28th of October 2024](https://steamcommunity.com/games/CSGO/announcements/detail/4522269457743085933) patched our multi-input methods, meaning only the first action of a bind will be issued and the rest ignored.
  > That means, using a pre-patch de-subtick jump bind now will use `+jump` but NOT issue `-jump`, resulting in you not being able to jump anymore afterwards. Typing `-jump` into the console will fix this issue, but you might need to use it multiple times, if you spammed the old-dated jumping bind multiple times: `jump -999 0 0`.

  > Now use working jump binds, by either resetting your binds to default (`bind mwheeldown +jump`) or by using the newest version of the CSAFAP config package.

- Q14: Which ones are the better jumpthrow binds: Keyboard macros or the config version?
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

- Q17: How to fix the console getting spammed with this `Unknown command: Mouse_If_SetIMStopWS`?
  > This occures when you used autostopWASD before, but now didn't exec the config without resetting the keybinds changed by it. They will point to alias, which the game doesn't know anymore.
  > Set default movement again and you should be fine. These are the manual commands set by `movement_default.cfg`
  > ```
  > bind w +forward;
  > bind a +left;
  > bind s +back;
  > bind d +right;
  > bind mouse_x yaw;
  > bind mouse_y pitch;
  > rightleft 0 0 0;
  > forwardback 0 0 0;
  > ```

- Q18: How to uninstall the config package?
  > Simply overwrite the keybinds used by this config package (`1, 2, 3, N, H, J, K, space, Q, W, A, S, D`) and don't execute `CSAFAP/MAIN` anymore.

If any questions remain, join my discord and feel free to ask in the `#csafap-config`- or `#help`-channel:

> Join the **CS AFAP DISCORD SERVER** [HERE](https://discord.gg/cs-as-fast-as-possible-992407294866370681).


[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
