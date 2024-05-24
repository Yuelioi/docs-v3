---
display_name: Get Input Analog Key State
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Player)

Returns the analog value for the given key/button. If analog isn't supported, returns 1 for down and 0 for up.

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Key |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Returns the analog value for the given key/button. If analog isn't supported, returns 1 for down and 0 for up. |
