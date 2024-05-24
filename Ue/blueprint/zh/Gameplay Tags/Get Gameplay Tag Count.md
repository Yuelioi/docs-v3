---
display_name: Get Gameplay Tag Count
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTags)

Returns the current count of the given gameplay tag.
This includes both loose tags, and tags granted by gameplay effects and abilities.
This function can be called on the client, but it may not display the most current count on the server.

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Gameplay Tag | The gameplay tag to query |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value |  |
