---
display_name: Copy to Cine Camera Actor
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1)

Copies all properties from a CineCameraComponent to a CineCameraActor and ensure the root actor transform is updated so the CameraComponents end up in the same World Space position

Target is VCam Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Source Camera Component |  |
| object | Target Camera Actor |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Copies all properties from a CineCameraComponent to a CineCameraActor and ensure the root actor transform is updated so the CameraComponents end up in the same World Space position |
