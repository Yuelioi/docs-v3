---
display_name: Create Asset (Message)
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/AssetTools)

Creates an asset with the specified name, path, and factory

Target is Asset Tools

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Asset Name | the name of the new asset |
| string | Package Path | the package that will contain the new asset |
| class | Asset Class | the class of the new asset |
| object | Factory | the factory that will build the new asset |
| name | Calling Context | optional name of the module or method calling CreateAsset() - this is passed to the factory |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | the new asset or NULL if it fails |
