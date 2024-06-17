---
title: Set Current Locale
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Set *only* the current locale (for internationalization).
Note: Unless you're doing something advanced, you likely want SetCurrentLanguageAndLocale or SetCurrentCulture instead.

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Culture | The locale to set, as an IETF language tag (eg, "zh-Hans-CN"). |
| boolean | Save to Config | If true, save the new setting to the users' "GameUserSettings" config so that it persists after a reload. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the locale was set, false otherwise. |
