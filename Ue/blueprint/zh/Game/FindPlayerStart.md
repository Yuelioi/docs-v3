---
display_name: FindPlayerStart
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Return the specific player start actor that should be used for the next spawn
This will either use a previously saved startactor, or calls ChoosePlayerStart

Target is Game Mode Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Player | The AController for whom we are choosing a Player Start |
| string | Incoming Name | Specifies the tag of a Player Start to use |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Actor chosen as player start (usually a PlayerStart) |
