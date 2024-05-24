---
display_name: Line Trace Single
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

Performs a raycast test against the point cloud. Returns the pointer if hit or nullptr otherwise.

Target is Lidar Point Cloud

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | Origin |  |
| vector | Direction |  |
| real | Radius |  |
| boolean | Visible Only |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Point Hit |  |
| boolean | Return Value | Performs a raycast test against the point cloud. Returns the pointer if hit or nullptr otherwise. |
