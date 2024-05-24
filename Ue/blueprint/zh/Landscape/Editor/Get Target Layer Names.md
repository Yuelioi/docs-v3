---
display_name: Get Target Layer Names
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape) > [Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape/Editor)

Retrieves the names of valid paint layers on this landscape (editor-only : returns nothing at runtime)

Target is Landscape

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | In Include Visibility Layer | whether the visibility layer's name should be included in the list or not |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value | the list of paint layer names |
