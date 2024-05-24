---
display_name: Insert Points
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

Inserts group of points into the Octree structure, multi-threaded.
If bRefreshPointsBounds is set to false, make sure you call RefreshBounds() manually or cloud centering may not work correctly.

Target is Lidar Point Cloud

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Points |  |
| enum | Duplicate Handling |  |
| boolean | Refresh Points Bounds |  |
| vector | Translation |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
