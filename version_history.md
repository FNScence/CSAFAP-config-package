# CS as fast as possible - Config Package
## Version History
- ***Base features (version 1.0):***
  - Automatic Smoke line-ups
  - <s>Instant Flash line-ups</s>
  - Movement Configs (<s>auto counter-strafe and</s> nulls)

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
	- Re-added manual sensitivity entry within `csafap/main.cfg`

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

- ***New with version 2.14:***
   	- Interim fix for 5-A-smokes auto line-ups

- ***New with version 2.15:***
   	- Fixed all auto line-ups (after valve broke angle zeroing with their animgraph2 update on [28th July 2025](https://steamcommunity.com/games/CSGO/announcements/detail/529853121068793940)).

- ***New with version 2.16:***
   	- Adjusted practice-mode Train CT-side Ivy pop flashes
	- Added auto line-up for Dust2 CT-side upper tunnels

- ***New with version 2.17:***
   	- <s>Added FPS-lock binds (hold and toggle options) for 100% perf bhops when used together with the already featured desubticked jump bind</s>

- ***New with version 2.18:***
	- Added custom sensitivity_y_scale support when using auto-lineups
	- Adjusted some practice mode line-ups on Overpass

- ***New with version 2.19:***
	- Reduced the amount of alias being loaded at any given time to a minimum, in a temporary attempt at fixing stability issues (caused by valve's first animgraph2 update)

- ***New with version 2.20:***
	- <s>Added auto bunny hop bind (hold)</s> (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))
    - Fixed a few practice mode line-ups (Ancient, Mirage, Train)

- ***New with version 2.21:***
	- Auto line-up setup no longer requires you to aim below head height (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))
    - Fixed compatibility between auto line-ups and auto bhops (credit and thanks to [Leiti](https://www.youtube.com/@xLeiti))

- ***New with version 2.22:***
	- Fixed an issue with auto line-up logic

- ***New with version 2.23:***
	- Fixed auto line-ups breaking after first line-up

- ***New with version 2.24:***
	- Added teleport to auto line-ups (to practice on servers with sv_cheats 1)
 	- Added auto line-ups for Mirage instant top con and bottom con smokes without having to throw window first (scroll mwheel while the radiowheel is open)
  	- Added 5 additional instant smokes to auto line-ups (Train: 2x A Main, 2x A bombtrain, 1x gate)
  	- Fixed an issue with auto line-ups turning the wrong way
  	- Fixed horizontal sensitivity breaking when exiting auto line-up wheel with map- or movement-wheel
 	- Fixed a practice mode line-up on Ancient
    - Fixed map wheel not resetting correctly if aborting on practice mode map selection
    - Removed Inferno instant deep mid smoke (patched)

- ***New with version 2.25:***
	- Fixed game crashes on disconnect or changelevel.  
      (Make sure not to exec csafap/main after the initial exec on game launch) Thanks to [girlglock](https://github.com/girlglock)

- ***New with version 2.26:***
	- Added alternative auto line-up binds, which work for faceit (and all other servers)
	- Another attempt at fixing auto line-ups being 180° wrong for the x-axis

- ***New with version 2.27:***
	- Fixed practice mode line-up on Ancient
 	- Fixed practice mode chat logic

- ***New with version 2.28:***
	- Fixed a bug, where auto line-up vertical zeroing would only move 90° up before opening the radiowheel

- ***New with version 2.29:***
	- Fixed remaining issues with auto line-ups

- ***New with version 2.30:***
	- Fixed wrong spawns for CT auto line-ups on Inferno and Overpass

- ***New with version 2.31:***
	- Switched Overpass spawn 4 and 5 teleports on practice mode

- ***New with version 2.32:***
	- Fixed an issue that caused Mirage auto line-ups to be 180° wrong horizontally when first selecting a different map
	- Changed Overpass mid incendiary auto line-up
	- Fixed practice line-ups for Train and Ancient
	- Removed option for desubtick binds (patched)

 - ***New with version 2.33:***
	- Switched Train and Anubis in radiowheel
 	- Added/improved Anubis practice mode line-ups
  	- Fixed some broken auto line-ups when using faceit binds

 - ***New with version 3.0:***
	- Added ticker mechanic allowing auto bhop bind and cs:go-like (W-)jumpthrow binds (credit and thanks to [AveYo](https://github.com/AveYo/Gaming/tree/main/CS2))
	- Fixed wrong practice mode spawn teleports on Anubis

- ***New with version 3.1:***
	- Added new pro crosshair section on movement wheel (default K)
	- Changed viewmodel options to adapt pro viewmodels
	- Fixed a bug that woud kick you from official games when attempting to use practice mode spawn-teleport tiles

- ***New with version 3.2:***
	- Added new rapid fire × follow recoil toggle bind
	- Removed bhop bind (patched)

- ***New with version 3.3:***
	- Fixed practice mode annotations not loading after season 4 update
	- Fixed some practice mode line-ups on Anubis
	- Fixed some issues about follow-recoil configs
	- Added left/righthanded knife options for rapidfire-followrecoil configs

- ***New with version 3.4:***
 	- Renamed movement wheel to crosshair wheel
 	- Added option for better follow-recoil binds on only primaries  (without rapid fire)
 	- Pro crosshairs are now compatible with the better follow-recoil bind

- ***New with version 3.5:***
 	- Added automatic side detection (CT/T) (thanks to [Leiti](https://github.com/xLeiti/))
    - Added/fixed a couple practice mode line-ups on Anubis
    - Various fixes and QoL improvements

- ***New with version 3.6:***
 	- Reverted to manual  side selection (2 keybinds) for auto line-ups

- ***New with version 3.7:***
 	- Realigned map wheel with premier veto screen
	- Fixed mouse2 not working for non-ticker users
	- Fixed/added a few Overpass practice mode line-ups

- ***New with version 3.8:***
 	- Re-added standalone desubtick binds for WASD and jumping
    - Fixed Linux loading issues (changed paths to all lower case)

- ***New with version 3.9:***
 	- Added Ancient Instant Anti-Elbow-Smoke Molotov (T spawn 5) to practice mode
  - 
- ***New with version 3.10:***
 	- Removed separate faceit binds for auto line-ups (server type is now detected automatically and binds set accordingly)
