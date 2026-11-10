# FishIO

> **Moved.** FishIO now ships inside [IO Hub](https://github.com/DrangedAddons/IOHub), which installs and updates it (WoW fishing bite trigger → *Install in WoW Forever*). Its source is [addons/FishIO](https://github.com/DrangedAddons/IOHub/tree/main/addons/FishIO) in that repo. This repository is archived.

A World of Warcraft addon for WoW Forever. While a fishing pole is in your main hand, it turns off the sounds that aren't part of fishing, so the bobber's splash stands out. Take the pole off and your sound settings go back to exactly how they were.

It's the companion to [IO Hub](https://github.com/DrangedAddons/IOHub)'s *WoW fishing bite* trigger, which listens to WoW's sound for the splash and can rumble your controller. It works on its own too: the splash is just easier to hear.

## Focus mode
With a fishing pole in your main hand:
- **Off:** music, ambience (wind, water, crowds), NPC dialog, emote sounds, pet sounds, and error voice lines ("Not yet!").
- **On, at full volume:** sound effects. That's combat, interaction, the cast and the splash.
- **Sound in the background** is turned on, so you still hear the splash while another window is in front.

Your own values are saved before anything changes and put back when the pole comes off, when you log out, or the next time you log in after a crash. If you change one of those settings yourself while fishing, FishIO leaves your choice alone.

## Using it
- `/fishio` shows whether it's on, whether a pole is in hand, and whether focus mode is running.
- `/fishio on` / `/fishio off` turns focus mode on or off (on by default).
- `/fishio quiet` / `/fishio loud` turns the chat line when focus starts or ends off or on.

Other addons with their own fishing sound options (EllesmereUI's *Fishing Sounds*, SKTools' *Mute* and *Louder Splash*) change the same settings. Use one of them or FishIO, not both.
