---
title: LineTraceMultiForLidarPointCloud
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lidar Point Cloud](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LidarPointCloud)

Does a collision trace along the given line and returns all hits encountered up to and including the first blocking hit.

Target is Lidar Point Cloud Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Origin |  |
| vector | Direction |  |
| real | Radius |  |
| boolean | Visible Only |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Hits |  |
| boolean | Return Value | Does a collision trace along the given line and returns all hits encountered up to and including the first blocking hit. |
