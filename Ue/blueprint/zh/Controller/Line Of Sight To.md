---
title: Line Of Sight To
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Controller)

Checks line to center and top of other actor

Target is Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Other | is the actor whose visibility is being checked. |
| vector | View Point | is eye position visibility is being checked from. If vect(0,0,0) passed in, uses current viewtarget's eye position. |
| boolean | Alternate Checks | used only in AIController implementation |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | true if controller's pawn can see Other actor. |
