---
display_name: Compute Render Capture Cameras for Box
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Sampling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSampling)

Compute a set of Render Capture Cameras to capture a scene within the given Box

Target is Geometry Script Library Mesh Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Box | Bounding Box containing the scene to be captured |
| struct | Options | Defines the Camera viewing directions into the box and other Camera parameters |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Cameras | Output Cameras with view frustums that contain the Box while maintaining the desired FOV |
