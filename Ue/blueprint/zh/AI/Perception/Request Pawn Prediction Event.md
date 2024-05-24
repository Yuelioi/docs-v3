---
display_name: Request Pawn Prediction Event
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Perception](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Perception)

Asks perception system to supply Requestor with PredictedActor's predicted location in PredictionTime seconds
Location is being predicted based on PredicterActor's current location and velocity

Target is AISense Prediction

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Requestor |  |
| object | Predicted Actor |  |
| real | Prediction Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
