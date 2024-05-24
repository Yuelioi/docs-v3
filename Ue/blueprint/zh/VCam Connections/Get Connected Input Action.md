---
display_name: Get Connected Input Action
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [VCam Connections](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VCamConnections)

- Gets the Connected Input Action for the given VCam Connection
- The returned Input Action is only guaranteed to be valid if both IsConnected() is true AND the VCam Connection is set to require an Input Action
- If the VCam Connection doesn't require an Input Action then this may still return a valid Action if the Connection Point
- had an associated Input Action however you will need to test for this manually

Target is VCam UIFunction Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Connection |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | *Gets the Connected Input Action for the given VCam Connection* The returned Input Action is only guaranteed to be valid if both IsConnected() is true AND the VCam Connection is set to require an Input Action *If the VCam Connection doesn't require an Input Action then this may still return a valid Action if the Connection Point* had an associated Input Action however you will need to test for this manually |
