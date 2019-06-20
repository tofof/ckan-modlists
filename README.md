# ckan-modlists
CKAN modlist files for Kerbal Space Program. Inspired by GiantWaffle's 2019 KSP playthrough and mod collection. Unfortunately, his CKAN file reflects several errors (requiring manual ScanSat install, using the abandoned fork of Engine Lighting, missing Trajectories fix, etc). In addition to correcting those errors, I partitioned the list to reflect the differing scopes of the included mods, and embellished with further visual/cosmetic, quality-of-life, and poweruser utilities, while preserving the stockalike disposition.

## Installation
1. Install and run CKAN
2. Refresh
3. CKAN Settings menu -> compatible ksp versions -> checkmark 1.7, 1.6, 1.5, 1.4, 1.3
4. File menu -> install from .ckan -> pick a file
5. Hit continue (do not use toggle checkbox to adjust anything)
6. Launch KSP from shortcut, from steam, or from CKAN once everything's installed.
7. (Optional) In Steam, lock KSP version to the most recent version Kopernicus supports.<sup>[[1]](#1-kopernicus)</sup>

## Suggested pack usage
Install 00 and 01 at a minimum.
Install 02 when you're ready to start building a permanent-ish space station.
Consider installing XX alongside 02 for useful station exterior signage, or whenever you want to add labels or hazard signs to your craft.
Install pieces from ZZ when you have progressed in skill to the point they might be helpful.

## The packs

| # | Name | Description |
|---|---------|-------------|
| 00 | Visual & QOL (essentially Stock++)  | Basic mods - only visual enhancement & essential quality of life|
| 01 | Community, Contracts, Tech Tree     | Community replacements/enhancements of stock mechanics<br>Nothing fundamentally altering balance, difficulty, or playstyle |
| 02 | Stations, Bases, Snacks             | New parts for station and base building, and a casual lifesupport system |
| XX | Decorative                          | Decals, animated screens, and fancy displays|
| ZZ | Utilities & Editors                 | Poweruser calculators, utilities, editors, etc|

## Details

### Pack 2, "Stations, Bases, Snacks" 
Other than the station and base parts, the major thing this pack adds is a life support system. It's completely configurable. By default, your veteran (orange-suit) Kerbals are immune to all negative effects. After 15 days without food or without power, your Kerbals will enter tourist-mode, making them unable to actually pilot the craft they're in or use any of their profession's abilities. *They will not die*, unless you change the configuration to use that option. Other alternatives include mutiny (destroy a part of the vessel, then become tourist), or to go M.I.A. (to respawn some period later).

### Pack ZZ, "Utilities & Editors" 
Useful once you're thinking *could x part of the game just let me have finer control* or perhaps *I just want to see the actual numerical value of y" or "how am I supposed to calculate z while I'm desigining my ship?*
* **Alternate Resource Panel** -- better than the stock resource display, can show countdown time to resource exhaustion
* **Kerbal Engineer Redux** --- displays extra part info on hover in the editor, calculates about a hojillion different properties of planets, ships, orbits, etc and can put any of them onscreen in flight, or into a little window for you.  If used, I suggest using the 'career' and 'part/engineer' requirements, which I think is the default - basically you dont get it in-flight without including the part or having an engineer abord
* **Real Chute** --- configure sizes of chutes on a per-craft per-part basis so you have just the right amount of parachute to slow your stage to whatever you want, and to control altitude parachutes open at and delay before they fully inflate, etc
* **Amp Year** --- calculate power usage in the editor, so you know how long you can operate in solar darkness, and even  shut down certain systems automatically when you get low on power
* **Editor Enhancements** --- gives fine grained control over part placement, makes rerooting parts easier, etc.
* **WASD Camera** --- lets you move the editor (VAB/SPH) camera freely, toggle between it and default cam
* **Too Many Orbits** --- lets you press a button (f8) to hide most of the orbits cluttering your map except for your active ship, so you can actually see what's going on
* **Quickstart** --- launch directly into your savegame
* **Quickgoto** --- go directly from scene to scene, instead of having to load the space center and then click into a building
* **Slingshotter** --- simulate where planets will be on a specific date, so you don't have to blindly fumble a maneuver around until it shows an encounter with a distant planet by chance
* **Trajectories** --- shows what your trajectory will do taking atmospheric drag into effect, highlights your landing spot clearly.  **MANUAL INSTALLATION STEP NEEDED** Browse to `kspinstallpath\GameData\Trajectories\Plugin\` and make a copy of `Trajectories16.bin` named `Trajectories17.bin` to get this mod working in version 1.7.x of KSP
* **Resonant Orbit Calculator** --- used to calculate how to place satellites into evenly-spaced locations along a single identical orbit
* **Portrait Stats** --- makes it easier to see what a kerbal's profession is while you're in flight.
* **TweakScale** --- lets you freely resize many parts. Their cost, mass, and capacity get scaled 'fairly' but many people still consider this mod a little cheaty.

## Suggested configuration
*If toolbar button spam is annoying, see the Janitor's Closet tip.*<sup>[[2]](#2-hiding-mod-buttons-with-janitors-closet)</sup>

#### Main menu - Settings (general tab)
* EVAs Auto-Rotate to Camera --- turn this off, instead toggle this behavior using the keybind set in Enhanced EVA Movement mod
* Extended Burn Time Indicator --- On --- Helpful information is helpful

#### Main menu - Settings (graphics tab)
* Terrain Scatters --- On --- adds physicsless trees and rocks, but costs fps
* Always show closest approach for target ---  makes it easier to actually rendezvous
* Orbit line fade strength --- 100% --- The difference is barely perceptible otherwise
* CommNet line brightness --- 50% --- Even this is probably too bright, unless you make a big deal of CommNet by radically altering the transmitter strengths in the game difficulty (as I have)
* Part Highlighter Brightness Factor --- 50% --- less detail-obliterating
* Part Highlighter in flight --- On --- helpful
* Pixel light count --- 16 or higher, particularly if you deliberately add surface lighting to your ships
* Ambient light boost --- 18%/10%/10% --- Otherwise you can't see your ships in the shadow of a planet at all, nor make out continents in the shadowed portion on the map
* Conic Patches -- relative mode works very well, since it switches how it draws depending which body you have as your current reference (doubleclick in the map on kerbin or the mun, for example, to change between the two). Turn patch limit up to 6 once you're trying to hit other planets.

#### Main menu - Settings (audio tab) 
* Master --- whatever you prefer, 50% etc
* Spacecraft --- 10% --- but turn this way up to 100% for your first several flights so you can appreciate the roar of a rocket taking off
* Ambience --- 5% --- there's a low bassy hum in the VAB that drives me crazy if it's any louder
* UI --- 100%
* Music --- 0% --- But leave this at like 20% until you've at least gotten to experience the transition to the orbital music a dozen times or so. Eventually, though, the VAB music will drive you insane.
* Voices --- 100% --- I don't think chatterer volume is controlled by this

#### Main Menu - Input
See also: https://github.com/TriggerAu/KSPKeyboardMap/blob/gh-pages/PNGs/KeyboardLayout-Flight_Hires.png
* Toggle navball --- Disable or use NumLock instead of Num. --- *You'll want to type decimals into the new maneuver window!*
* Camera mode/next --- Use Num/ and Num* instead of C and V --- Frees c key for use by Enhanced EVA mod.
* Camera 'view up' etc --- waste of arrowkeys. Use the mouse instead.
* Wheels steer/drive --- *Use arrowkeys, so you can use wheels (🠄🠆🠅🠇), gyros (WASD), & thrusters (HJKL) simultaneously.
* Translation --- I prefer the numpad, since I don't do HJKL directions.
* Translation key mode behavior --- *Keys shouldn't change behavior. Keep usage identical in all three modes.*

#### If you need to free up keys for use by more important things
* SAS hold (f) is almost worthless.
* Full throttle (z) --- *You will accidentally hit this instead of cutting throttle during a precision burn, ruining it. Unbind it.*
* Toggle mouselook is also useless in practice.

#### Difficulty (for a newcomer)
* Basic difficulty settings 
  * allow reverts 
  * allow quickloads
  * missing crews respawn but on like a 6hr (1 kerbal day) timer or longer
  * no auto-hire 
  * no indestructible facilities
  * no stock vessels
  * no comm network
  * decline penalty 0 *(contracts are wacky sometimes and you shouldn't take a hit to say no to something stupid or that you're tired of)*
  * heating/reward/penalty sliders all 100% otherwise
* Advanced difficulty settings - *Everything off, except...*
  * Kerbal G-force limits on *(short blackout from very rough parachutes is interesting and unlikely to make casualties)*
  * G-force Tolerance 1.0
  * Part Upgrades on
  * Building damage 0.05

#### Mod Settings inside Difficulty Menu
* **DMagic -> Portrait Stats** --- Always show (off), use icon (off), remaining settings (on) --- less ugly this way
* **Filter extensions** --- Hide unpurchased (off), Default to advanced (off), 
* **Hide Empty Tech Tree Nodes** --- Remove empty horizontal and vertical space both (on)
* **Janitor's Closet** --- everything (on) except debug mode, and definitely turn the slider up to like 1.5 seconds or more. The menu disappears too quickly otherwise
* **Stage Recovery** --- I would set the global modifier to 80% to make this a little less cheaty. Moving the cutoff velocities downward also increases the difficulty of getting a successful recovery of a part. Hide the space center button with the final option to (on).

#### In-Game Settings Menu
Upsize the ui and associated text without making icons annoyingly large:
* **UI Scale** --- 110%
* **Toolbar App Icon Scale** --- 93%

#### In-Game Mods Settings (clicking on the mod button in toolbar)
* **E.V.E.** --- Click the arrows over until you get to the City Lights Manager tab, then set `_CityOverlayDetailSca...` to `0.072` for better city lights at night.
* **Distant Object Enhancement** --- Enable flares and names, Max out the flare saturation (100%), brightness (150%), and size (100%), show debris flares (15% bright), render distant vessels at max slider distance, do not dim the skybox. Alternatively, edit the .cfg file in the `GameData` directory, and set the maximum sky brightness to 225% for a more vivid night sky on Kerbin (and much much more vivid in the map view).
* **Chatterer** --- Chatter frequency 90-180s, then in beeps tab SSTV frequency (no sstv),  sstv on science transmitted (on), sstv vol (6%) then in AAE tab bg1 (20%), bg2 (30%), only in IVA (on), breath volume (50%), airlock (100%), wind (10%), then in settings tab instachatter on singlequote, insta-sstv on semicolon.
* **ScanSat** --- turn Toolbar Menu (off) to get rid of the annoying popup behavior, and definitely have Show Ground Tracks (on), and consider setting its child setting Active Vessel Only (off). Note that you can disable all ScanSat scanning activity from all vessels with a single errant click on the Background Scanning tab, so be careful in that one.
* **Craft Manager** (VAB) --- kerbalx integration (no), replace load button (yes) --- far superior to the stock craft load dialog
* **Alternative Resource Display** (flight) --- show rate change values (on), show rates for parts (on), rate style **Up/Down+Text** is much nicer

## Notes

#### [[1]⤣](#installation) Kopernicus
Kopernicus is only used in these modlists to add rings to Jool. If you are near Jool, and want to see the rings, make sure Kopernicus isn't complaining at startup (it refuses to load at all on version mismatch). 

Otherwise, however, the warnings not to load your save can be safely ignored.

#### [[2]⤣](#suggested-configuration) Hiding mod buttons with Janitor's Closet
Alt-rightclick on most toolbar icons and choose 'hide everywhere'. Put items back into certain scenes (builder, map/trackingstation, in-flight) on an individual basis. Some may be unclickable, like KER. Unfortunately, sometimes it seems that janitor's closet dies until the game is restarted.

**Useful mods to leave showing in specific scenes:**
  * **VAB** --- Tags, Goto, KER, RCS Build Aid, Antenna Helper, WASD Camera, AmpYear, EditorExtensions, Stage Recovery
  * **Tracking Station** --- ScanSat, Goto, Waypoint Manager, KER, Alarm Clock, Antenna Helper, Slingshotter
  * **Flight** --- *Button visibility is shared between flight and flight's map view* --- Docking Alignment Indicator, AmpYear, Stage Recovery, Slingshotter, Alternate Resource Display, Alarm Clock, KER, Waypoint Manager, Goto, ScanSat, **ScienceAlert**, Antenna Helper
  * **Space Center Overview** --- Alarm Clock, Goto
