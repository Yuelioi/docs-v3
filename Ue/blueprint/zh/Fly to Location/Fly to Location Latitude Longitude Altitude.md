---
display_name: Fly to Location Latitude Longitude Altitude
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Fly to Location](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FlytoLocation)

Begin a smooth camera flight to the given Latitude/Longitude destination such that the camera ends at the specified yaw and pitch.
The flight can be enforced or canceled if the user moves the pawn

Target is Round Planet Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | In Latitude |  |
| real | In Longitude |  |
| real | In Altitude |  |
| real | Yaw at Destination |  |
| real | Pitch at Destination |  |
| boolean | Can Interrupt by Moving |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
