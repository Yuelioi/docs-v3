---
display_name: Create Lidar Point Cloud From File
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

Returns new Point Cloud object imported using default settings.
If using Async, the process runs in the background without blocking the game thread.

Target is Lidar Point Cloud Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Filename |  |
| boolean | Use Async |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Success |  |
| exec | Failure |  |
| real | Progress |  |
| object | Point Cloud |  |
