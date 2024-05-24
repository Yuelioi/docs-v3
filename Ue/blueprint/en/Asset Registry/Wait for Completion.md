---
display_name: Wait for Completion
order: 54
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Wait for scan to be complete. If called during editor startup before OnPostEngineInit, and there are any assets that use classes in
not-yet-loaded plugin modules, WaitForCompletion will return silently with those assets still ungathered.

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
