---
display_name: Log Performance Snapshot
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Performance](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Performance) > [Health Snapshot](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Performance/HealthSnapshot)

Writes a snapshot to the log. Captures memory stats by default. Also captures performance stats if called after StartHealthSnapshotChart and before SopHealthSnapshotChart.

Target is Health Snapshot Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Snapshot Title | The name to be given to the new HealthSnapshot. |
| boolean | Reset Stats |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
