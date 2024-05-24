---
display_name: Get Base Material
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Walks up parent chain and finds the base Material that this is an instance of. Just calls the virtual GetMaterial()

Target is Material Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Walks up parent chain and finds the base Material that this is an instance of. Just calls the virtual GetMaterial() |
