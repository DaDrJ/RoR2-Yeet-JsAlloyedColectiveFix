# Yeet

## Description

Clicking an item or equipment in your inventory will remove one stack of it and forcefully toss it in the direction you're aiming. Functions on both client and server by way of the `yeet [item name/index]` console command, which may also be used on its own.
###### note that with the Alloy Vultures DLC, temporary items will not be yeetable.

Holding the mouse button down for longer will throw the item farther.

Config options include (default values):

- Server:
	- Blacklist, prevent dropping:
		- Items and equipment by name token (none)
		- Items by tier (Lunar and all Void)
		- Tierless/hidden/non-removable items (all on)
		- Non-Lunar or Lunar equipment (both off)
		- All items (off)
		- All equipment (off).
	- Cooldown on dropping (10s) and on picking up items you just dropped (5s)
	- Prevent Recycler on dropped items (on)
	- Drop Command droplets if relevant artifact is active (off)
	- Limit maximum allowable items dropped per click if dropping multiple (1/off)
	- Entirely disable mod temporarily (on/not disabled)
	- Announce dropped items in chat (on)
	- Prevent dropping your last void item (on)
	- Minimum and maximum throw force (30, 150)
- Client:
	- Make left and/or right click drop multiple items (1/off, 1/off)
	- Click hold time required to reach maximum throw force (2 sec)


###### Please report any issues you may encounter on my [github page](https://github.com/DaDrJ/RoR2-Yeet-JsAlloyedColectiveFix) <br> I cant prommise any fixes since i suck at coding but i sure will try
