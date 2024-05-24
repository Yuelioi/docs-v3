---
display_name: Navigation Raycast
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

Performs navigation raycast on NavigationData appropriate for given Querier.

Target is Navigation System V1

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Ray Start |  |
| vector | Ray End |  |
| class | Filter Class |  |
| object | Querier | if not passed default navigation data will be used |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Hit Location | if line was obstructed this will be set to hit location. Otherwise it contains SegmentEnd |
| boolean | Return Value | true if line from RayStart to RayEnd was obstructed. Also, true when no navigation data present |
