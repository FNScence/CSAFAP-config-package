==================== HOW TO INSTALL === CSAFAP CONFIG PACKAGE (version 1.3) ==========
			written by ".FNScence" (youtube.com/c/CSasfastaspossibleFNScence)
			FULL TUTORIAL: https://youtu.be/G9hAaifu2H0

STEP 1: Place the whole folder named "CSAFAP" in the config folder of the CS2 installation:
		"C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg"
		
STEP 2: Place the modified language file "platform_english.txt" in the resource folder at the following path:
		"C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource"

STEP 3: Open the main config of this package "CSAFAP\MAIN.cfg" with an editor of your choise (e.g. notepad++).
		IMPORTANT: EDIT LINE 6 TO ENTER YOUR PLAYING SENSITIVITY. You can also change the 3 (+2) keybinds in the following lines.

STEP 4: Run the main config in-game. Either type "exec CSAFAP/main" directly into the console, ...
		... use the same line in a config you already use, or use launch option "+exec CSAFAP/MAIN".
		You can also set-up an alias for quick execution by adding the following line in your own config.
		Simply typing this newly defined alias into the console will run the config.
		alias "afap" "exec CSAFAP/MAIN"

		Done!

============================ FEATURES (and version history) ============================	
  - Base features (version 1.0)
	x)	AUTOMATIC SMOKE LINE-UPS
	x)	INSTANT FLASH LINE-UPS
	x)	MOVEMENT CONFIGS (auto counter-strafe and nulls)
	
  - New with version 1.1: (credit and thanks to "-Cap1taL-" - https://github.com/eLecCap1taL)
	x)	AUTOMATIC MAP DETECTION
	
  - New with version 1.2: (credit and thanks to "Leiti" - https://youtube.com/@xLeiti)
	x)	(W-)JUMPTHROW BINDS (desubticked; exactly like pre-patch 8/20)
	x)	DESUBTICKED MOVEMENT BINDS (mwheel-jump for bhop, WASD, etc.)
	x)	CROUCH-JUMP BIND (aka Longjump-bind)
	x)	JUMP-BUG BIND
	x)	AUTO STOP DEFUSE WHEN SHOOTING
	
  - New with version 1.3:
	x)	THERA support (instant dropper, top mid and B main smokes for CT-side)
	x)	OVERPASS support (AWP wallbangs, mid runboost-incendiary)

======================= HOW TO USE === AUTO-LINE-UP and MOVEMENT CONFIG PACKAGE ===========
STEP 1: Press one of the THREE KEY BINDS to access a RADIO WHEEL (default: H - instant flash, J - smokes, K - secondary smokes)

STEP 2: Hover your mouse over the tile you want to use and PRESS THE SAME KEY AS IN STEP 1 again.

STEP 3: Throw your line-up.

(STEP 4): When using INSTANT BUG FLASHES (default keybind: H), immediatelly after releasing MOUSE1, PRESS 1 (or 2) to switch to your gun.
		This will automatically turn away from the flash and pre-aim enemy positions.
		
============================ FAQ ============================	
Q1: Is this allowed on MM, PREMIER?
	> Yes! This config package works purely on in-game commands and which work under SV cheats 0, and a modified language text-file.

Q2: Is this allowed on Faceit?
	> Yes! It's allowed for your normal ranked PUGS.
	> https://imgur.com/a/NkOc7VZ

Q3: How to calculate yaw/pitch values?
	> [X = a / (s * 0.022)];[ a...angle you need to move (in °); s...sensitivity, X...desired yaw/pitch value]

Q4: The radio tiles are empty. How to get the text working?
	> Make sure to place "platform_english.txt" in the correct folder and use the english language in-game.
	
Q5: Why do I stop running when using the jumpthrow binds?
	> Autostop configs interfer with (W-)JT binds. Make sure to use default movement (for JT),
	> or movement configs with default W-bind (for W-JT).

Q6: Why does my quickswitch (or whatever you bound Q to) not work anymore?
	> The instant window flash on Anubis overwrites the keybind of Q.
	> If you don't want to use it, search for it in MAIN.cfg (CTRL+F) and change/delete it.
	
Q7: How to uninstall the config package?
	> Simply overwrite the keybinds used by this config package (1, 3, N, H, J, K, space, Q, W, A, S, D)
	> and don't execute CSAFAP/MAIN anymore.

> If any questions remain, join my discord and feel free to ask in the #auto-smoke-channel:
	> https://discord.gg/7GatkNvUyh
