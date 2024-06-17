---
title: Get Culture Display Name
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Get the display name of the given culture.

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Culture | The culture to get the display name of, as an IETF language tag (eg, "zh-Hans-CN") |
| boolean | Localized | True to get the localized display name (the name of the culture in its own language), or False to get the display name in the current language. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The display name of the culture, or the given culture code on failure. |
