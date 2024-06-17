---
title: Get Current Culture
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Get the current culture as an IETF language tag:

- A two-letter ISO 639-1 language code (eg, "zh").
- An optional four-letter ISO 15924 script code (eg, "Hans").
- An optional two-letter ISO 3166-1 country code (eg, "CN").
  Note: This function exists for legacy API parity with SetCurrentCulture and is equivalent to GetCurrentLanguage.

Target is Kismet Internationalization Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The culture as an IETF language tag (eg, "zh-Hans-CN"). |
