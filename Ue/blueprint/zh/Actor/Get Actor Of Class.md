---
display_name: Get Actor Of Class
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Actor)

Find the first Actor in the world of the specified class.
This is a slow operation, use with caution e.g. do not use every frame.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Actor Class | Class of Actor to find. Must be specified or result will be empty. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Actor of the specified class. |
