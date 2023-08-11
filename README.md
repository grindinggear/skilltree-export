## Notice

This repository is for the Passive Skill Tree data. Please visit https://github.com/grindinggear/atlastree-export if you're looking for Atlas Tree data.

## Notable Changes

### 3.22.0
---
We aim to update this preview to include passive skill tree tattoo data on Wednesday 16th August (NSZT).

### 3.20.0
---
Group backgrounds are now defined in the group objects themselves using a new `background` property. If this property is missing then no background should be rendered.

| Key | Value Type | Extra Information |
| --- | --- | --- |
| background | ?object | |
| ↳ image | string | an image key for the `groupBackground` spritesheet |
| ↳ isHalfImage | ?boolean | always `true` if present |
| ↳ offsetX | ?int | offset from the group x in pixels |
| ↳ offsetY | ?int | offset from the group y in pixels |

| Background Keys | Extra Information |
| --- | --- |
| PSGroupBackground1 |
| PSGroupBackground2 |
| PSGroupBackground3 |
| PSGroupBackground1Alt | only on the Atlas tree |
| PSGroupBackground2Alt | only on the Atlas tree |
| PSGroupBackground3Alt |  only on the Atlas tree |
| GroupBackgroundCleansingFire | only on the Atlas tree |
| GroupBackgroundTangle | only on the Atlas tree |

The `backgroundOverride` property has been removed.

### 3.18.1
---
We have changed all image assets to now use spritesheets. These will be supplied with each data release from now on.

### 3.17.0
---
The amount of nodes per orbit has changed to give us more angles to work with.

| Orbit | Nodes (Old) | Nodes (New) |
| --- | --- | --- |
| 0 | 1 | 1 |
| 1 | 6 | 6 |
| 2 | 12 | **16** |
| 3 | 12 | **16** |
| 4 | 40 | 40 |
| 5 | 72 | 72 |
| 6 | 72 | 72 |

The angle for positions in these orbits (2 & 3) are now:

| Orbit Index | Angle |
| --- | --- |
| 0 | 0 |
| 1 | 30 |
| 2 | **45** |
| 3 | 60 |
| 4 | 90 |
| 5 | 120 |
| 6 | **135** |
| 7 | 150 |
| 8 | 180 |
| 9 | 210 |
| 10 | **225** |
| 11 | 240 |
| 12 | 270 |
| 13 | 300 |
| 14 | **315** |
| 15 | 330 |
