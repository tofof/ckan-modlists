# ckan-modlists
CKAN modlist files for Kerbal Space Program

## Installation
1. Install CKAN
2. settings -> compatible ksp versions -> checkmark 1.7, 1.6, 1.5, 1.4,
3. file -> install from .ckan -> pick a file
4. Hit continue (do not use toggle checkbox to adjust anything)

## Suggested configuration
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
Other than the station and base parts, the major thing this pack adds is a life support system. It's completely configurable. By default, your veteran (orange-suit) Kerbals are immune to all negative effects. After 14 (21? 28?) days without food or without power, your Kerbals will enter tourist-mode, making them unable to actually pilot the craft they're in or use any of their profession's abilities. *They will not die*, unless you change the configuration to use that option. Other alternatives include mutiny (destroy a part of the vessel, then become tourist), or to go M.I.A. (to respawn some period later).

### Pack ZZ, "Utilities & Editors" 
Useful once you're thinking *could x part of the game just let me have finer control* or perhaps *I just want to see the actual numerical value of y" or "how am I supposed to calculate z while I'm desigining my ship?*
* **Alternate Resource Panel** -- better than the stock resource display, can show countdown time to resource exhaustion
* **Kerbal Engineer Redux** --- displays extra part info on hover in the editor, calculates about a hojillion different properties of planets, ships, orbits, etc and can put any of them onscreen in flight, or into a little window for you.  If used, I suggest using the 'career' and 'part/engineer' requirements, which I think is the default - basically you dont get it in-flight without including the part or having an engineer abord
* **Real Chute** --- configure sizes of chutes on a per-craft per-part basis so you have just the right amount of parachute to slow your stage to whatever you want, and to control altitude parachutes open at and delay before they fully inflate, etc
* **Amp Year** --- calculate power usage in the editor, so you know how long you can operate in solar darkness, and even  shut down certain systems automatically when you get low on power
* **Editor Enhancements** --- gives fine grained control over part placement, makes rerooting parts easier, etc.
* **WASD Camera** --- lets you move the editor (VAB/SPH) camera freely, toggle between it and default cam
* **Too Many Orbits** --- lets you press a button (f8? f7? one of those) to hide most of the orbits cluttering your map except for your active ship, so you can actually see what's going on
* **Quickstart** --- launch directly into your savegame
* **Quickgoto** --- go directly from scene to scene, instead of having to load the space center and then click into a building
* **Slingshotter** --- simulate where planets will be on a specific date, so you don't have to blindly fumble a maneuver around until it shows an encounter with a distant planet by chance
* **Trajectories** --- shows what your trajectory will do taking atmospheric drag into effect, highlights your landing spot clearly.  **MANUAL INSTALLATION STEP NEEDED** Brose to `kspinstallpath\GameData\Trajectories\Plugin\` and make a copy of `Trajectories16.bin` named `Trajectories17.bin` to get this mod working in version 1.7.x of KSP
* **Resonant Orbit Calculator** --- used to calculate how to place satellites into evenly-spaced locations along a single identical orbit
* **Portrait Stats** --- makes it easier to see what a kerbal's profession is while you're in flight. **Suggestion** disable it from showing all the time, and disable the use of icons instead of text for the profession. Much less ugly that way.
* **TweakScale** --- lets you freely resize many parts. Their cost, mass, and capacity get scaled 'fairly' but many people still consider this mod a little cheaty.
