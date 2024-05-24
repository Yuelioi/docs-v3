---
display_name: Update Connection Targets
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [VCam Connections](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VCamConnections)

- Looks through the set of Connections on this widget and if a matching connection name is found will attempt to update the connection target.
- If the new target is the same as the old target then no update is performed.
- This function will optionally reinitialize the widget connections if 1 or more targets were updated.
  \*
- Note: If a connection name in the NewConnectionTargets map is not found in the Widget Connections then it is ignored
- no new connections will be created and no connections will be removed

Target is VCam Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | New Connection Targets |  |
| boolean | Reinitialize on Successful Update |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Did Update Connections |  |
| exec | No Connections Updated |  |
