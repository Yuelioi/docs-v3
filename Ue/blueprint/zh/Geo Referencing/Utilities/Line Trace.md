---
display_name: Line Trace
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geo Referencing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing/Utilities)

LineTrace at specific location/direction

Target is Geo Referencing Editor BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | World Location | Location of viewport origin (camera) in world space |
| vector | World Direction | Direction of viewport (camera) in world space |
| object | Actors to Ignore |  |
| boolean | Trace Complex | Whether we should trace against complex collision |
| boolean | Show Trace | Whether we should debug draw the trace |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | If the Level editor not are in focus it will return false, and same if nothing is hit. |
| struct | Hit Result | The trace hits result. |
