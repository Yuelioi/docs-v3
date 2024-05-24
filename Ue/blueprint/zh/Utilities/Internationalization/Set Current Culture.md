---
display_name: Set Current Culture
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Set the current culture.
Note: This function is a sledgehammer, and will set both the language and locale, as well as clear out any asset group cultures that may be set.

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Culture | The culture to set, as an IETF language tag (eg, "zh-Hans-CN"). |
| boolean | Save to Config | If true, save the new setting to the users' "GameUserSettings" config so that it persists after a reload. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the culture was set, false otherwise. |
