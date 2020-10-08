Isometric Tile map in [[Unity]]
- Grid - Serves as a template that holds all of Tile Map objects
- Tile Map - is where actual tiles get placed
- Tile Palette - holds all tiles I can place onto the Tile Map

I found out it's better to use multiple Tile Map objects with different rendering orders because it allows me to render things such as walls on top of floor tiles and does not force me to render them on a separate grid cell

You can set rendering of tiles to be in chunks or individual. Chunks save some time, because they are batch rendered. However for different tiles to sort properly you need to create a texture atlas for them so they can all be issued in one [[Draw Call]] ?. This will only work at runtime so for editing it's better to render each tile separately
#[[Unity]] #isometric 