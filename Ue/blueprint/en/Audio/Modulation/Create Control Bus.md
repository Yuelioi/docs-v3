---
display_name: Create Control Bus
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Creates a modulation bus with the provided default value.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Name | Name of bus |
| object | Parameter | Default value for created bus |
| boolean | Activate | (DEPRECATED in 5.4: Use UAudioModulationDestination) Whether or not to activate bus on creation. If true, deactivation will only occur if returned bus is manually deactivated and not referenced or destroyed (i.e. will not deactivate when all references become inactive). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Bus | ControlBus created. This should be stored (eg. by a Blueprint as a variable) to prevent it from being garbage collected. |
