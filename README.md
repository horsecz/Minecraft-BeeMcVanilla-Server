# Minecraft Server: BeeVanilla

Vanilla server with Multiverse plugin, enabling possibility to play more gamemodes & maps at one place - server. The idea was to have one save (therefore Minecraft server) for playing multiple worlds, modes and difficulties on singleplayer, also with preserving the worlds somewhere on cloud - so once I return to playing Minecraft, I can continue where I've left or go far away and start over.


## Core information

- Version:		`1.20.1`
- Server:		`PaperMC`
- Client:		`Required same Minecraft version as server`
- Plugins:		`Dynmap, Chunky, Multiverse, VoidGen, WorldEdit, WorldGuard, ViveCraft`


## Vanilla with plugins?

Vanilla but I see some plugins there, so why is the server called "Vanilla" exactly?

Plugins are there for ensure multiple world/mode selection, optimized performance and more. 
Everything is made for most clean Vanilla experience with just extra possibility of multiple modes and worlds on one server.

### Used plugins

- `Dynmap`
	- dynamic map of all worlds, ehnances experience
- `Chunky`		
	- pre-loadaing chunks of world(s) to prevent server lag
- `Multiverse`		
	- multiworld possibility with portals and nether/end dimensions
	- this includes plugins: `Multiverse-Core`, `Multiverse-Inventories`, `Multiverse-NetherPortals`, `Multiverse-Portals`, `Multiverse-SignPortals`
- `VoidGen`
	- world generator used for SkyBlock world (only)
- `WorldEdit`
	- building Lobby and base structures, allows easy WorldGuard usage
- `WorldGuard`
	- spawn protection on world(s), used on:
		- Lobby, for obvious purposes
		- Limited world, to limit world boundaries and prevent player from leaving it
		- All spawn areas in every world, to prevent destroying portals (Lobby and bed portal)
- `ViveCraft`	
	- enables VR support on server-side


## Playable worlds

### Lobby

The default area all players will spawn, when they join the server first time. Relatively small sphere with multiple portals in it. These portals teleport player to different worlds.

### Survival

Survival world with normal difficulty.

### Creative

Classic world with creative mode.

### Flat

Flat world with creative mode.

*Nether and The End portals do not work in this world.*

### Large Biomes

Survival world with Large Biomes and hard difficulty.

### Limited

Survival world with normal difficulty, which attempts to simulate old Minecraft worlds from previous (old) versions, when the entire world was limited in size and was not generated infinitely.

World boundaries are visible on the water level (bedrock blocks) and player cannot pass them. The world "size" is 256x256x256 blocks.

*Nether and The End portals do not work in this world.*

### Ocean

Survival world with hard difficulty and only one biome: Ocean.

### Skyblock

Classic Skyblock survival world (normal difficulty).

*Nether and The End portals do not work in this world.*


## Other

### Dynmap

Dynamic map of all worlds - dynmap plugin. The map is present at `localhost:8123` in web browser.

Even though dynamic map is not available in Vanilla Minecraft, this plugin does not affect gameplay in any way (if the player won't open the map in his browser).

### VR support

Thanks to ViveCraft plugin, this server supports playing in VR. However this plugin only enables the possibility to play in VR on server-side. It does not affect gameplay in any way if you're not using VR.

Players with VR can play with players with classic set (usually keyboard and mouse) simultaneously.

Note: If you wanna play in VR, you also need VR support on your client, meaning:
- Installed SteamVR (or any other application that enables VR support in Minecraft)
- Enabled or installed ViveCraft (client-side) mod 