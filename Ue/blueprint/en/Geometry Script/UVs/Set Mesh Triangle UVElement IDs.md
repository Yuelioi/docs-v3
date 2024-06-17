---
title: Set Mesh Triangle UVElement IDs
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Sets the UV Element IDs for a given Triangle in the specified UV Channel, ie the "UV Triangle" indices.
This function does not create new UVs, the provided UV Elements must already.
The UV Triangle can only be set if the resulting topology would be valid, ie the Elements cannot be shared
between different base Mesh Vertices, so they must either be unused by any other triangles, or already associated
with the same mesh vertex in other UV triangles.
If any conditions are not met, bIsValidTriangle will be returned as false.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Triangle ID |  |
| struct | Triangle UVElements |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Triangle |  |
| object | Target Mesh | Sets the UV Element IDs for a given Triangle in the specified UV Channel, ie the "UV Triangle" indices.This function does not create new UVs, the provided UV Elements must already.The UV Triangle can only be set if the resulting topology would be valid, ie the Elements cannot be sharedbetween different base Mesh Vertices, so they must either be unused by any other triangles, or already associatedwith the same mesh vertex in other UV triangles.If any conditions are not met, bIsValidTriangle will be returned as false. |
