---
display_name: Add Tracked Point with Name
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality)

Manually add a tracked point with name and world transform.
@WorldTransform: transform in the world space where the point should be created.
@PointName: the name of the created point, must be non-empty.
@bDeletePointsWithSameName: if existing points with the same name should be deleted.

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| transform | World Transform |  |
| string | Point Name |  |
| boolean | Delete Points with Same Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | if the operation succeeds. Note that this is an async operation - the added point won't be available until a few frames later. |
