# Shallow Ground

This modlet greatly reduces the depth to `bedrock`, which encourages stable building (reducing possibility of base-drop) and discourages the hiding of underground buildings.

## Features

1. biome depths are all adjusted for a more shallow, trench-warfare experience
    - drastically reduces time necessary to set up a stable base (bedrock is just 2M down)
2. mineral veins are replaced with just boulders
    - to offset the reduction of resources, we've boosted boulder frequency
3. removed burried supply and treasure quests to avoid cutting any deeper into the ground

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
deco_iron_vein | oreIronBoulder
deco_coal_vein | oreCoalBoulder
deco_nitrate_vein | orePotassiumNitrateBoulder
deco_lead_vein | oreLeadBoulder
deco_shale_vein | oreShaleBoulder

## Quest Adjustments

Type | Removed
--- | :---:
Clear | unmodified
Fetch | unmodified
Clear & Fetch | unmodified
Burried Supplies | removed
Challenge | unmodified
Treasure | removed
