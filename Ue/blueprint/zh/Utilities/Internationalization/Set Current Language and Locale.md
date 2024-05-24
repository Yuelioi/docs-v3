---
display_name: Set Current Language and Locale
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Set the current language (for localization) and locale (for internationalization).

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Culture | The language and locale to set, as an IETF language tag (eg, "zh-Hans-CN"). |
| boolean | Save to Config | If true, save the new setting to the users' "GameUserSettings" config so that it persists after a reload. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the language and locale were set, false otherwise. |
