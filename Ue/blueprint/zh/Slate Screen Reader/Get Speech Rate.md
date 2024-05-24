---
display_name: Get Speech Rate
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Returns the rate text to speech will be speaking at for a screen reader user. Value is between 0.0f and 1.0f.
If the provided user Id doesn't exist, 0.0f will be returned.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user to retrieve the text to speech rate for |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value |  |
