---
display_name: Update Graph Variable Overrides
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Experimental](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Experimental)

Updates the stored variable overrides to reflect the graph preset. Existing overrides will be updated to match
the graph variable name, value type, object type, and container type. Additionally, stale overrides that have no
corresponding graph variable will be removed, and overrides will be created for graph variables which do not have
existing overrides.

Target is Movie Job Variable Assignment Container

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
