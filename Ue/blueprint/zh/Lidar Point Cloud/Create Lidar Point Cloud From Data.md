---
title: Create Lidar Point Cloud From Data
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

- Returns new Point Cloud object created from the data provided.
- Warning: If using Async, make sure the data does not get invalidated during processing!

Target is Lidar Point Cloud Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Points |  |
| boolean | Use Async |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Success |  |
| exec | Failure |  |
| real | Progress |  |
| object | Point Cloud |  |
