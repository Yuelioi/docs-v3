---
display_name: Get Default Locale
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Get the default locale (for internationalization) used by this platform
Note: This should be returned in IETF language tag form:

- A two-letter ISO 639-1 language code (eg, "zh")
- An optional four-letter ISO 15924 script code (eg, "Hans")
- An optional two-letter ISO 3166-1 country code (eg, "CN")

Target is Kismet System Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The locale as an IETF language tag (eg, "zh-Hans-CN") |
