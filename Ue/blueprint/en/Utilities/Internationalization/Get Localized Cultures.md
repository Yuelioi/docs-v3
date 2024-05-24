---
display_name: Get Localized Cultures
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Internationalization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Internationalization)

Get the list of cultures that have localization data available for them.

Target is Kismet Internationalization Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Include Game | Check for localized game resources. |
| boolean | Include Engine | Check for localized engine resources. |
| boolean | Include Editor | Check for localized editor resources. |
| boolean | Include Additional | Check for localized additional (eg, plugin) resources. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The list of cultures as IETF language tags (eg, "zh-Hans-CN"). |
