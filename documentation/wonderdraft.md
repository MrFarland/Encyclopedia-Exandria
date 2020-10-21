---
name: Documentation
slug: documentation
order: 0
---
# Documentation
Atlas Exandria is an ambitious project that aims to create a comprehensive, canon-consistent set of maps for the world of Exandria. Maintaining accuracy and consistency requires a great deal of effort and this document was created to help me achieve these goals while simultaneously helping others recreate the look & feel of these maps and even create their own companion maps. 

## Wonderdraft
The maps in this atlas were created using the application, [Wonderdraft](https://wonderdraft.net). The maps in this atlas were created with Wonderdraft version **1.1.3**.

An advanced cartography application, Wonderdraft provides the cartographer with a range of settings and style choices. The following are the settings used to create the look and feel of these maps.

### General Settings
|||
|:---|:---|
| **Textures**            | Worn / Worn   |
| **Coastal FX Distance** | ~ 33%  |
| **Landmass Outline**    | ~ 75%  |
| **Vignette**            | ~ 50%  |
| **Coastline**           | Irregular |
| **Coastline Color**     | r(48) g(67) b(1) a (122)  |
| **Landmass Color**      | r(67) g(42) b(10) a (255) |
| **Freshwater Color**    | r(41) g(91) b(51) a (140) |
| **Freshwater Outline**  | r(45) g(30) b(0) a (255)  |
| **Path Color**          | r(132) g(117) b(110) a (180) |
| **Symbol Color 1**      | r(37) g(20) b(12) a (255) |
| **Symbol Color 2**      | r(37) g(35) b(30) a (150) |
| **Symbol Color 3**      | r(76) g(71) b(63) a (255) |
{.gray}

### Color Palette
The color palette used in my maps is from the Avoro 4 theme for Wonderdraft. I have not made any modifications to colors, but only used a small subset of them for the map.

When painting, use the grunge like brush and lower the opacity, but keep the brush large. Multiple passes blend areas better than high opacity or a small brush.

### Labels

I am not documenting all of the label styles including colors and styles because there are simply too many. I'm only including the base styles used on the world map as a way to quickly replicate the overall feel. 

| Preset             |  TS | TC        | OS | OC        |
|:-------------------|:---:|:---------:|:--:|:---------:|
| Continent          | 128 | #9c000000 |  - | -         |
| Desert             |  24 | #7d000000 |  3 | #7dab9262 |
| Forest (Broadleaf) |  24 | #c8000000 |  3 | #c8ccbe99 |
| Forest (Dark/Dead) |  24 | #c8000000 |  3 | #c85f5543 |
| Forest (Evergreen) |  24 | #c8000000 |  3 | #c8505633 |
| Island             |  18 | #9c000000 |  - | -         |
| Island Chain       |  36 | #9c000000 |  - | -         |
| Mountain           |  16 | #c8000000 |  2 | #c8918775 |
| Mountain (Snow)    |  16 | #c8000000 |  2 | #c8e2e1e1 |
| Mountains          |  24 | #c8000000 |  3 | #c8918775 |
| Mountains (Snow)   |  24 | #c8000000 |  3 | #c8e2e1e1 |
| Plain              |  18 | #c84c4a21 |  3 | #c8989367 |
| Plain (Snow)       |  18 | #c8000000 |  3 | #c8e0dad6 |
| Point of Interest  |  12 | #000000   |  - | -         |
| Roads              |  10 | #000000   |  - | -         |
| Settlement (Cap)   |  18 | #c8ffffff |  1 | #c8000000 |
| Settlement (City)  |  16 | #c8ffffff |  1 | #c8000000 |
| Settlement (Town)  |  14 | #c8ffffff |  1 | #c8000000 |
| Settlement (Vill)  |  12 | #c8ffffff |  1 | #c8000000 |
| Swamp              |  16 | #c8483010 |  3 | #c87a6e46 |
| Water (Lake)       |  12 | #32ffffff |  - | -         |
| Water (Feature)    |  24 | #32ffffff |  - | -         |
| Water (Ocean)      | 128 | #32ffffff |  - | -         |
| Water (River)      |  12 | #96ffffff |  - | -         |
{.gray}

#### Font
All labels use the **IM Fell English Italic** font.

#### Font Size
Smaller font sizes are used for some labels where the full size version would not fit. Forests, mountains, swamps, etc. Might have a smaller label then is listed if the feature is too small. I will decrease the font by two until I find a size that fits. 

The smallest font size is 10. It is small, but readable on the full-size image at 100% zoom.

#### Curvature
Curvature is an artistic choice and varies from one label to the next.

### Paths
The following settings were used for all paths.
- Color: #b483756e
- Width: 2
- Type: 1
{.square}

In addition to drawing roads using the above settings, all roads are traced with the dirt color to help blend them into the countryside. It also helps to convey "wear" from travelers.

(print-page)


### Scale 
The scale of the maps in this atlas are based on the official map of Tal'Dorei from the 1.1 release of the Tal'Dorei Campaign Setting Guide. The continent of Tal'Dorei in the Atlas is a 1:1 representation of that map and all other continents and regions are positioned and scaled to that reference map.

All of the maps use a faint hex grid to provide DMs with a means of quickly and accurately measuring the distance between two points. The size and scale of those hexes vary based on map type.

- **F2F**: The distance across the hexagon from one face to the opposite face.
- **V2V**: The distance across the hexagon, diagonally from one vertex to vertex.
- **V2C**: The distance from a vertex to the center of the hexagon. Also the length of a single face.
{.square}

*^All^ ^numbers^ ^are^ ^in^ ^miles^ ^or^ ^square^ ^miles^*

#### Dimensions of a Hex
The following actual numbers are included for completeness. I strongly recommend using the recommended distances to speed up estimating distances and make it easier to remember.

#### Actual
| Map Type  | F2F | V2V   | V2C  | Area     |
|:----------|:---:|:-----:|:----:|:--------:|
| World     | 120 | 138.6 | 69.3 | 12,471.0 |
| Continent |  60 |  69.3 | 34.6 |  3,118.0 |
| Region    |  30 |  34.6 | 17.3 |    779.4 |
{.gray}

#### Recommended
| Map Type  | F2F | V2V   | V2C  | Area     |
|:----------|:---:|:-----:|:----:|:--------:|
| World     | 120 | 140   | 70   | 12,471.0 |
| Continent |  60 |  70   | 35   |  3,118.0 |
| Region    |  30 |  35   | 17.5 |    779.4 |
{.gray}


### Title Blocks

#### World
- Exandria = 192 - #282828
- Text = 24 - #000000
- Sovereign = 48
- Council = 36 
- Box = 919191
- Red = #732828

#### Continents
- Name = 96
- Box

## Detail Maps
The following table lists all of the maps in the atlas, the working size of the map used in Wonderdraft and both the digital and physical dimensions of the exported image. In all cases, the base **points per inch (PPI)** of each map is **300**. 

### Continent Maps


### Regional Maps

#### Tal'Dorei
| Name                |Zoom|   X  |   Y  |   W  |   H  | Resolution   |
|:--------------------|:--:|:----:|:----:|:----:|:----:|:------------:|
| Alabaster Sierras   | 4x | 2757 |  810 |  600 |  450 |  2400 x 1800 |
| Bladeshimmer Shore  | 4x | 1750 | 1250 |  600 |  675 |  2400 x 2700 |
| Cliffkeep Mountains | 4x | 1900 |  550 | 1050 |  750 |  4200 x 3000 |
| Dividing Plains     | 4x | 2350 | 1150 |  600 |  450 |  2400 x 1800 |
| Lucidian Coast      | 4x | 2850 | 1200 |  450 |  600 |  1800 x 2400 |
| Rifenmist Peninsula | 4x | 2000 | 1900 | 1050 |  675 |  4200 x 2700 |
| Stormcrest Mountains| 4x | 2500 | 1600 |  450 |  375 |  1800 x 1500 |
| Verdant Expanse     | 4x | 2050 | 1600 |  600 |  450 |  2400 x 1800 |
{.gray}

#### Wildemount
| Name                   |Zoom|   X  |   Y  |   W  |   H  | Resolution   |
|:-----------------------|:--:|:----:|:----:|:----:|:----:|:------------:|
| Blightshore            | 4x | 4950 |  750 |  450 |  900 | 1800 x 3600 |
| Eiselcross             | 4x | 3675 |   40 |  750 |  450 | 3000 x 1800 |
| Greying Wildlands      | 4x | 4300 |  280 |  750 |  600 | 3000 x 2400 |
| Marrow Valley          | 4x | 3950 |  900 |  750 |  675 | 3000 x 2700 |
| Menagerie Coast        | 4x | 3200 |  850 | 1200 | 1200 | 4800 x 4800 |
| Xhorhas                | 4x | 4500 |  860 |  600 | 1050 | 2400 x 4200 |
| Zemni Fields           | 4x | 3900 |  600 |  600 |  525 | 2400 x 2100 |
{.gray}

#### World Map
| Name                   | Wonderdraft | Digital      | Physical  |
|:-----------------------|:-----------:|:------------:|:---------:|
| **Exandria**           | 5400 x 3600 | 10800 x 7200 | 36" x 24" |
{.gray}

#### Issylra
| Name                   | Wonderdraft | Digital      |
|:-----------------------|:-----------:|:------------:|
| Issylra                | 3600 x 4800 |  7200 x 9600 |
{.gray}

#### Marquet
| Name                   | Wonderdraft | Digital      |
|:-----------------------|:-----------:|:------------:|
| Marquet                | 3600 x 2850 |  7200 x 5700 |
{.gray}

#### Shattered Teeth
| Name                   | Wonderdraft | Digital      |
|:-----------------------|:-----------:|:------------:|
| Shattered Teeth        | 4200 x 2700 |  8400 x 5400 |
{.gray}

(print-page)










