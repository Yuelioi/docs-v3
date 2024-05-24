---
display_name: Set SmartObject Enabled (default reason Gameplay)
order: 48
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Enables or disables the smart object using the default reason (i.e. Gameplay).

Target is Smart Object Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Enable |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Status Changed | false if it was not possible to change the enabled state (ie. if it's not registered or there is no smart object subsystem). |
