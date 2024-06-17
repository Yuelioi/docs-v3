---
title: Get World Location
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Calibration](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Calibration)

Returns the World location of the subpoint (or the component) specified by name

Target is Calibration Point

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| string | In Point Name | Name of the point or subpoint. If not namespaced the component name will have priority over subpoint name. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Location | World location of the specified subpoint. |
| boolean | Return Value | True if successful. |
