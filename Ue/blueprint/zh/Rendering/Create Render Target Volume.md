---
display_name: Create Render Target Volume
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Creates a new volume render target and initializes it to the specified dimensions

Target is Kismet Rendering Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Width |  |
| integer | Height |  |
| integer | Depth |  |
| enum | Format |  |
| linearcolor | Clear Color |  |
| boolean | Auto Generate Mip Maps |  |
| boolean | Support UAVs |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Creates a new volume render target and initializes it to the specified dimensions |
