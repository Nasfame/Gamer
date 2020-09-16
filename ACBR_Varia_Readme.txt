Prenotes:
- Scripts with a '*' in their descriptive enable depending on how you select your DRM (Uplay, Steam, etc)
- Best practise is to load the table AFTER your save game has fully loaded...
- You should only work with 'normal color' cheats (do not touch 'greyed' info)
- When returning to the main game menu, best is to disable any locked values
  (including God Mode, etc ~ since it will try to save data to "old" memory locations)
- FastTravel (and Cutscenes) will 'reset' data structure pointers. Whenever this happens,
  you must re-enable selected (sub)options again...
- All values (pointers) will be collected while "active"
  (iow not while in 'ESC' or 'TAB' mode; except for the Map Waypoint Marker)
- You can use [DXwnd] (v2.04.59) to work/play in Windowed Mode

* Player Status:
- Health: can be locked if needed
- Godmode: use [Ctrl+G] primarily during Teleporting...
- Invisible: you will become undetectable
  (when already in conflict, move out of sight...)
- Notoriety: once at 'full notoriety', this cheat will not "remove" the 'red' indicator...

* Inventory Supplies: edit accordingly, but keep most values - except Money - below {99}

* One Hit Kill: (not perfect, but working...)
* Table 1: Timer Freezers - make sure to select the proper DRM (you might try both of them...)
  (taken from another table ~ credits due)

* Teleport & Coordinates...:

> Teleport to map waypoint:
Prenote: 
When selecting any icon on the map, teleporting to that location should be fine. However, keep in mind that Player will drop from a great height (and therefore will/could die/desync). To avoid this altogether, simply enable 'God Mode' first...

0. Enable 'Map Waypoint' script first...
1. Open map and select an icon (such as chest, fragment, bottle, etc), or any location
2. Press [Shift+T] while still in the map view...!
3. Press [ESC] and Player should now teleport to that particular location

Notes:
a. If you wind up in some structure (like rocks, hills, trees, building, etc), simply teleport
to a different location. When you try/fail again, see pt b.
(this usually also means your 'Drop Height' is too low)
b. If you keep getting "stuck", zoom in completely and select a location in "close" proximity...
(and increment your drop height first)
c. You can not teleport from specific locations/positions
(such as from a boat, the water, a Viewpoint, a haystack, a tree branch, etc)

Important note:
This game engine seems to work with a 'water surface reference'. If you wind up in there,
it becomes (almost) impossible to teleport again! And since there is no 'FastTravel' feature,
you'll need to quit to main menu first...
=> Workaround:
- you can first try with Free Roam (but this does not seem to work here...)
- first wait till you see Ezio surfacing...
  (if you do not see him, teleport to a different location first)
- open the map [TAB]
- remove the map waypoint marker ! (using [Enter] a few times)
- click [Rome ~ 'Escape' water trapped...]
 (which will update coordinates to a river location near the left-top of the map)
- press [ESC] and wait till you see Ezio in the water... (you might need to move a bit)
- you can now swim/get out of the water.
=> If you are still stuck, teleport to another map location (some distance away from the river)
   and try above again ~ usually works after 2 attempts...

> Free Roam (also check out Help function)
> Cam Distance (FOV)


* Tools ~ Build Icon Lists:
The script will allow you to build/print 2 different lists: a) all Collectibles b) all Viewpoints
The script will allow you to build/print several different lists.
Tip: especially keep a copy of items (chests/feathers) that you've already collected !
     (so you can double-check/tick-off items already collected)
Options:
	01 = list Collectibles still to collect
	10 = list all Collectibles
	20 = show all Collectibles still to collect on the map
	30 = list all Map Icons (incl ViewPoints)
  Note1: you can not seem to save 'show on map' status permanently; so you'll need to run this when appropriate...
  Note2: experience was obtained during ACU/ACS research; tool is not really needed here...
         (since you can buy maps)
  Legend:
	Chest:		9	6  (or 0/0)
	Flag:		9	9
	Feather:	9	1
Action: in order to jump to a particular location, follow these steps:
        0. first make sure that a waypoint marker is currently "active"
           (so that you can fill in new values...)
	1. while ingame (!), manually copy/paste each coordinate to their respective 'Waypoint' X-, Y- (and Z-) axis
           (fill in Z-height value, if it is higher then '40' !)
	2. press [TAB] (go to map); and verify that the (new) waypoint marker is located within an accessible area...!
	3. press [Shift+T] (teleport...), then press [ESC]. You should now teleport to that location...
      Note: if you fill in coordinates directly into the player's coordinate fields, there is a good chance
            that you will crash after doing so a few times...



ps: you can change the hotkeys via CE's 'hotkey' feature
    ([Ctrl+G] = dis/enable God Mode)
