---
display_name: Set Data Layer Is Loaded in Editor
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataLayers)

Changes the DataLayer's IsLoadedInEditor flag to the provided state

Target is Data Layer Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Data Layer | The DataLayer to affect. |
| boolean | Is Loaded in Editor | The new value of the flag IsLoadedInEditor. If True, the Editor loading will consider this DataLayer to load or not an Actor part of this DataLayer. An Actor will not be loaded in the Editor if all its DataLayers are not LoadedInEditor. |
| boolean | Is from User Change | If this change originates from a user change or not. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
