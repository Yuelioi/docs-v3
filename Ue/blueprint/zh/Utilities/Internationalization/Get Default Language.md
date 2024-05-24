---
display_name: Get Default Language
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Get the default language (for localization) used by this platform
Note: This is typically the same as GetDefaultLocale unless the platform distinguishes between the two
Note: This should be returned in IETF language tag form:

- A two-letter ISO 639-1 language code (eg, "zh")
- An optional four-letter ISO 15924 script code (eg, "Hans")
- An optional two-letter ISO 3166-1 country code (eg, "CN")

Target is Kismet System Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The language as an IETF language tag (eg, "zh-Hans-CN") |
