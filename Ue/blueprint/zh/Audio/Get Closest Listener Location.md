---
display_name: Get Closest Listener Location
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Finds and returns the position of the closest listener to the specified location

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Location | The location from which we'd like to find the closest listener, in world space. |
| real | Maximum Range | The maximum distance away from Location that a listener can be. |
| boolean | Allow Attenuation Override | True for the adjusted listener position (if attenuation override is set), false for the raw listener position (for panning) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Listener Position | \[Out\] The position of the closest listener in world space, if found. |
| boolean | Return Value | true if we've successfully found a listener within MaximumRange of Location, otherwise false. |
