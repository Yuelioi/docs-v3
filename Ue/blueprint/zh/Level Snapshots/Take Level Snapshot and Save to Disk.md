---
display_name: Take Level Snapshot and Save to Disk
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Snapshots](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSnapshots)

@brief Creates a new Level Snapshot asset in the content browser and then captures the target world

Target is Level Snapshots Editor Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | World Context Object | Context object to determine which world to take the snapshot in |
| string | File Name | The desired asset file name |
| string | Folder Path | The desired asset location |
| string | Description |  |
| boolean | Should Create Unique File Name | If true, the asset name will have a number incrementally added to the file name if an asset with a similar name already exists. If false, the existing asset will be overwritten. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
