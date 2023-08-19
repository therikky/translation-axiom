# Очиститель

**Очиститель** — это набор предопределенных инструментов рисования, которые обычно имеют сложный набор предопределенных правил размещения, не подпадающих под другие категории. Из-за этого они часто используют продвинутые алгоритмы для создания интересных шаблонов, но более конкретно указывают, в каких случаях их можно использовать.

Очиститель позволяет настроить кисть для определения пути штриха, как и другие инструменты. Помимо этого, у него есть две другие опции, которые можно переключать и настраивать. **Ландшафт** и **Украшения**. Их можно смешивать и сочетать, чтобы обеспечить широкий спектр настроек.

## Terrain

These clentaminator presets affect solid blocks in your brush stroke

### Stone
    
The Stone Terrain preset is a very simple terrain tool, just setting the base to only stone.
    
### Grass
    
The Grass Terrain preset naturalizes the terrain by making the top layer grass blocks followed by 3-4 layers of dirt and any terrain below that being set to stone.
    
### Sand
    
The Sand Terrain preset makes a desert terrain by making the top 4-5 layers sand and blocks below that being set to sandstone.
    
### Dirt Ground
    
The Dirt Ground Terrain preset uses a wave function collapse algorithm to make a pattern of dirt with mixed in blotches of dry mud and coarse dirt to make a quick and easy floor for things such as forest floors, paths, etc.
    
### Gravel Ground
    
The Gravel Ground terrain preset uses a wave function collapse algorithm to make a pattern of stone mixed in with blotches of gravel and cobblestone to make a quick and easy rough rocky pattern, useful for mountain gravel slides, paths, etc.
    
### Fertile Ocean Floor
    
The Fertile Ocean Floor terrain preset uses a mix of layered voronoi as well as cellular noise patterns in order to create a varied look of an ocean, swamp or riverbed floor in ‘fertile’ water areas such as mangroves near oceans, swamps, river deltas/mouths, etc.
    
## Decorations

These clentaminator presets affect non-solid blocks, often intended to be placed on top of existing terrain to help enhance the aesthetics.

### Clear
    
The Clear decoration preset isn’t a ‘nothing’ brush, instead it can be used to clear other decorations found in the natural generation or placed by other clentaminator presets. Useful to create something like a clearing in a forest for example.
    
### Grass
    
The Grass decoration preset uses a perlin noise to randomly disperse dense plots of grass in a pleasing pattern in order to quickly decorate a plains biome, edges next to paths, etc. When selecting the grass decoration preset two new sub-settings appear:
    
- A grassiness slider ranging from 0-1 (uncapped but going above 1 has no effect) to denote how ‘grassy’ an area should be. The closer to 1 the more grass there is.
- An ‘Allow Tall Grass’ toggle which lets the perlin noise’s most dense areas use tall grass. This creates the appearance that grass gets more dense the further in you go which can be useful for more wild areas.
