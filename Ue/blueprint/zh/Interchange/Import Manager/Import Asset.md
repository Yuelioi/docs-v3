---
display_name: Import Asset
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Import Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/ImportManager)

Call this to start an asset import process. The caller must specify the source data.
This process can import many different assets into the game content.

Target is Interchange Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Content Path | The path where the imported assets will be created. |
| object | Source Data | The source data input to translate. |
| struct | Import Asset Parameters | All parameters that need to be passed to the import asset function. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the import succeeds, or false otherwise. |
