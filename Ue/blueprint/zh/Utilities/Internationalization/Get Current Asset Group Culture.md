---
display_name: Get Current Asset Group Culture
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Get the given asset group category culture.
Note: Returns the current language if the group category doesn't have a culture override.

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| name | Asset Group | The asset group to get the culture for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The culture as an IETF language tag (eg, "zh-Hans-CN"). |
