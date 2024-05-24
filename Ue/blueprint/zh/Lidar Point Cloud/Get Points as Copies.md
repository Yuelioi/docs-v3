---
display_name: Get Points as Copies
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

Returns an array with copies of points from the tree
If ReturnWorldSpace is selected, the points' locations will be converted into absolute value, otherwise they will be relative to the center of the cloud.

Target is Lidar Point Cloud

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Return World Space |  |
| integer | Start Index |  |
| integer | Count |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Returns an array with copies of points from the treeIf ReturnWorldSpace is selected, the points' locations will be converted into absolute value, otherwise they will be relative to the center of the cloud. |
