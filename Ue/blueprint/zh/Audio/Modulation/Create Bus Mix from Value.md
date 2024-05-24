---
display_name: Create Bus Mix from Value
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Create a mix with stages created for each provided bus that are initialized to the supplied value and timing parameters.
\*

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Name |  |
| object | Buses | Buses to assign stages within new mix to * |
| real | Value | Initial value for all stages created within the new mix. * |
| real | Attack Time | Fade time to user when mix activates. * |
| real | Release Time | Fade time to user when mix deactivates. |
| boolean | Activate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Mix |  |
