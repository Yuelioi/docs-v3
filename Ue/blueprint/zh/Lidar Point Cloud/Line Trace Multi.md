---
display_name: Line Trace Multi
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

Performs a raycast test against the point cloud.
Populates OutHits array with the results.
If ReturnWorldSpace is selected, the points' locations will be converted into absolute value, otherwise they will be relative to the center of the cloud.
Returns true it anything has been hit.

Target is Lidar Point Cloud Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | Origin |  |
| vector | Direction |  |
| real | Radius |  |
| boolean | Visible Only |  |
| boolean | Return World Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Hits |  |
| boolean | Return Value | Performs a raycast test against the point cloud.Populates OutHits array with the results.If ReturnWorldSpace is selected, the points' locations will be converted into absolute value, otherwise they will be relative to the center of the cloud.Returns true it anything has been hit. |
