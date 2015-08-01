# Hidden Biomes

Enable a number of normally hidden biome types in the system editor biome drop-down.Created planets should be playable by anyone, although people without the mod will get file-not-found for the planet image in the lobby. No templates are provided, take any planet and edit it's biome type.

## Biomes

- 1v1 Test - no icon
- Asteroid - icon built-in, has issues
- CSG Debug - no icon
- Ice Boss - icon built-in
- Metal Boss - icon built-in
- Sandbox - icon provided by mod; will only be visible to people with the mod

### 1v1 Test

Desert biome with lots of tight passes.  Probably the prototype for designed planets, packaged as a biome rather than the new planetCSG attribute.  We don't know the planet parameters like radius, however.

### Asteroid

This biome type has several limitations.  It can't be previewed in the system editor, which precludes custom metal and CSG - you might be able to swing it by editing the planet as a sandbox and editing the file... but then this mod does you no good.  Having a planet with asteroid biome triggers the asteriod belt effect in-game.

### CSG Debug

Dev test for brushes; more of a curiosity than a practical planet type.

### Ice Boss

In Galactic War, the Foundation have a special biome type with with ice, volcanos, hot water, and maybe a metal crater. Curiously, the metal trenches are also used, but with BO_Add, and are not visible, except possibly for some odd strips cut through the snowy areas.

### Metal Boss

Normally this only appears in the GW Synchronous boss system. Has a metal crater, and does not function as a laser.

### Sandbox

The sandbox biome is used in the dev's internal test mode. It has a grid texture, supports water, and has no brushes or features, so it's a little kinder on load times and RAM.
