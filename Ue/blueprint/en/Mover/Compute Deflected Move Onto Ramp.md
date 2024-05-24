---
display_name: Compute Deflected Move Onto Ramp
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Used to change a movement to be along a ramp's surface, typically to prevent slow movement when running up/down a ramp

Target is Ground Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Orig Move Delta |  |
| struct | Ramp Hit Result |  |
| real | Max Walk Slope Cosine |  |
| boolean | Hit from Line Trace |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Return Value | Used to change a movement to be along a ramp's surface, typically to prevent slow movement when running up/down a ramp |
