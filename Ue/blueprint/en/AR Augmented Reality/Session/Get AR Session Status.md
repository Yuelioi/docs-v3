---
display_name: Get AR Session Status
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/Session)

It is intended that you check the status of the Augmented Reality session on every frame and take action accordingly.
e.g. if the session stopped for an unexpected reason, you might give the user a prompt to re-start the session

Target is ARBlueprint Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The status of a current Augmented Reality session: e.g. Running or Not running for a specific reason. |
