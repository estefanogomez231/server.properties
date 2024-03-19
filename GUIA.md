Cambios para necesarios para optimizar tu server.properties

1: view-distance (Default: 10) (Optimized: 6 - 9)
- This is a big performance setting as it forcibly reduces the max render distance for players.

2: simulation-distance (Default: 10) (Optimized: 4 - 7)
- This is a big performance setting as it forcibly reduces the simulation distance for players, limiting how far away from any given player the game will update entities, blocks, and fluids.

3: network-compression-threshold (Default: 256) (Optimized: 512 // Bungeecord: -1)
- This option caps the size of a packet before the server attempts to compress it. Setting it higher can save some resources at the cost of bandwidth, setting it to -1 disables it.

