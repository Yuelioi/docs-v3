---
display_name: Get Point Id
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Google ARCore](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GoogleARCore) > [Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GoogleARCore/PointCloud)

Returns the point Id of the point at the given index.

Each point has a unique identifier (within a session) that is persistent
across frames. That is, if a point from point cloud 1 has the same id as the
point from point cloud 2, then it represents the same point in space.

Target is Google ARCore Point Cloud

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Returns the point Id of the point at the given index.Each point has a unique identifier (within a session) that is persistentacross frames. That is, if a point from point cloud 1 has the same id as thepoint from point cloud 2, then it represents the same point in space. |
