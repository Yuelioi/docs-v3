---
display_name: Activate Modulation Generator (Deprecated - 5.4)
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

SOFT DEPRECATED: Use CreateModulationWatcher and store resulting watcher instead!
Manually activates a modulation generator. If called, deactivation will only occur
if generator is manually deactivated and not referenced or destroyed (i.e. will not deactivate
when all references become inactive).

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Generator |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
