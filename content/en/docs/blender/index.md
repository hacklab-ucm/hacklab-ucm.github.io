---
title: "Blender"
date: 2023-12-01T10:07:14+02:00
draft: false
---

## Overview of UI - Working layouts
Default layout  
Sculpt layout  


## Basic viewport navigation

orbit -> CTRL + SHIFT + scroll  
pan ->  
pan -> middle mouse grab  
zoom -> scroll  

## Basic Object manipulation

| Command    | key | restrict to axis | numeric quantity |
| :-------:  | :-: |      :-----:     |    :------:      |
| Grab  ->   |  g  |      (xyz)       |     2.50         |
| Scale ->	 |  s  |      (xyz)       |     4            |
| Rotate ->  |  r  |      (xyz)       |     30º          |
| | | | |

Examples:  
`s z 0.1`  &nbsp;&nbsp; _Scale in the Z-axis by 0.1_  
`g x 3`  &nbsp;&nbsp; _Grab (move) along the X-axis by 2 units_  
`g xx`  &nbsp;&nbsp; _Move along the object's **local** X-axis, not the global axes._  
`r y 90`  &nbsp;&nbsp; _Rotate along the Y-axis by 90º_  
`s SHIFT+z`  &nbsp;&nbsp; _Scale on all axis **except** Z_  

Grab -> g	(xyz)
Scale -> s	(xyz)
Rotate -> r	(xyz)


## T Panel and N Panel
Tools panel, and numeric?

## F3 (Commands Panel)

## Edit Mode (Hard-surface modelling)
`TAB` to enter _Edit Mode_

## Object Origins
Orange dot.  
F3 for "Origin to 3D cursor", etc.

## Sculpt Mode (Organic modelling)
Dyntopo (for when we want to create new geometry, only in those areas which require more detail)

## Decimate Modifier
We can use the decimate modifier to make more lightweight geometry while maintaining the shape to a certain degree.

## Units
Blender units  
Metric, unit-scale multiplier  
Grid-overlay scale multiplier  

## Export (stl/obj)
### Scale

## Preferences:
More 'Undo' steps.  
Configure 'Autosave'.  

Reference & further info:  
https://www.blender.org/  
https://docs.blender.org/manual/en/latest/  

Blender Fundamentals:  
https://www.youtube.com/playlist?list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6  

Other resources:  
https://www.blendersecrets.org/book

More:  
https://www.kodeco.com/21459096-blender-tutorial-for-beginners-how-to-make-a-mushroom  	
https://en.wikibooks.org/wiki/Blender_3D:_Noob_to_Pro/Tutorial_Links_List  
https://www.creativebloq.com/advice/sculpt-in-blender  
https://www.b3d101.org/en/2.8/index.html  
