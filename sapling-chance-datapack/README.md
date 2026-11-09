# Guaranteed Sapling Drops

This datapack targets Minecraft Java Edition 26.2. It replaces the vanilla leaf loot tables so every naturally harvested leaf block guarantees one matching sapling or mangrove propagule. The tables apply to leaves broken by players, leaves that decay, and leaves destroyed by explosions.

Leaf blocks drop only when the breaking tool is Shears or has Silk Touch. Leaves destroyed by decay or explosions do not drop as blocks.

## Install

Copy the `sapling-chance-datapack` folder into `<world>/datapacks/`, then run `/reload` or restart the world. Use `/datapack list` to confirm that it is enabled.

Supported trees are oak, spruce, birch, jungle, acacia, dark oak, mangrove, cherry, and pale oak. The datapack guarantees one matching sapling or propagule per eligible leaf block, subject to the explosion survival condition. It cannot inspect the complete tree shape.
