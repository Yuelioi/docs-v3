---
display_name: Get Attribute Value
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [DMX](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX) > [Fixture Patch](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX/FixturePatch)

Retrieves the value of an Attribute. Will fail and return 0 if the Attribute doesn't exist.

Target is DMX Fixture Patch

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Attribute | The Attribute to try to get the value from. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | Whether the Attribute was found in this Fixture Patch |
| integer | Return Value | The value of the Function mapped to the selected Attribute, if found. |
