---
title: Get Suitable Culture
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Given a list of available cultures, try and find the most suitable culture from the list based on culture prioritization.
eg) If your list was \[en, fr, de\] and the given culture was "en-US", this function would return "en".
eg) If your list was \[zh, ar, pl\] and the given culture was "en-US", this function would return the fallback culture.

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Available Cultures | List of available cultures to filter against (see GetLocalizedCultures). |
| string | Culture to Match | Culture to try and match (see GetCurrentLanguage). |
| string | Fallback Culture | The culture to return if there is no suitable match in the list (typically your native culture, see GetNativeCulture). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The culture as an IETF language tag (eg, "zh-Hans-CN"). |
