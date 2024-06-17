---
title: Get ECEF ENU Vectors At ECEF Location
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geo Referencing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing) > [ENU](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing/ENU)

Get the East North Up vectors at a specific location - Not in engine frame, but in pure ECEF Frame !

Target is Geo Referencing System

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | ECEFCoordinates |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | ECEFEast |  |
| vector | ECEFNorth |  |
| vector | ECEFUp |  |
