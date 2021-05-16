# Shallow Ground

This modlet greatly reduces the depth to `bedrock`, which encourages stable building (reducing possibility of base-drop) and discourages the hiding of underground buildings.

## Features

1. biome depths are all adjusted for a more shallow, trench-warfare experience
    - drastically reduces time necessary to set up a stable base (bedrock is just 2M down)
2. mineral veins are also more shallow, but have a guaranteed solid block of minerals under them and an additional 2M spike directly below the boulder
    - this 2M spike can be used to place a chest and cover it back up
    - since this position is below all others, it offers some very basic defense against the x-ray camera exploit

## Biome Adjustments

Block | Before | After
--- | :---: | :---:
terrDesertGround | 4 | 1
terrSand | 4 | 1
terrDestroyedStone | 2 | 1
terrDirt | 3 | 0
terrStone | * | 1
terrSandStone | * | 1
terrBedrock | 3 | *

## Mineral Vein Adjustments

Original | Replacement
--- | ---
deco_iron_vein | deco_iron_vein_shallow
deco_coal_vein | deco_coal_vein_shallow
deco_nitrate_vein | deco_nitrate_vein_shallow
deco_lead_vein | deco_lead_vein_shallow
deco_shale_vein | deco_shale_vein_shallow
