---
display_name: Set Current Asset Group Culture
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Set the given asset group category culture from an IETF language tag (eg, "zh-Hans-CN").

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Asset Group | The asset group to set the culture for. |
| string | Culture | The culture to set, as an IETF language tag (eg, "zh-Hans-CN"). |
| boolean | Save to Config | If true, save the new setting to the users' "GameUserSettings" config so that it persists after a reload. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the culture was set, false otherwise. |
