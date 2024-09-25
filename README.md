Peated Ovens
=================

Overview
--------

A mod that adds peat, of various other mods, to be a source of fuel for the clay oven.

Things to note
--------

- This doesn't fix textures for the fuel; it all looks like firewood or broken textures in the oven.

- Fuel values are ignored by clay ovens; you're likely burning higher value stuff for the same poor fuel rates as wood.

- Total fuel items aren't adjusted; it's dictated by the oven model as a fix value.

See: [`game:systems/cooking/clayoven`](https://github.com/anegostudios/vssurvivalmod/blob/master/Systems/Cooking/Clayoven/BEClayOven.cs#L431)

Supported Mods
--------

- Vanilla Peat

- [Dried Peat](https://mods.vintagestory.at/show/mod/4149)


Future plans
--------

 - Add any missing peat types into the fold for all the super smokey bready goodness.

Notable mods that add similar features
--------

 - [Oven Fuel](https://mods.vintagestory.at/show/mod/5361)
	- Adds similar features to only `game:blocktypes/soil/peatbrick`

 - [Dana Tweaks](https://mods.vintagestory.at/danatweaks)
    - New home for what was `ovenfuel` and a bunch of other things