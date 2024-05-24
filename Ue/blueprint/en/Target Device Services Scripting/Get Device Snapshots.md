---
display_name: Get Device Snapshots
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Target Device Services Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TargetDeviceServicesScripting)

Fetches snapshots of devices that are available in the network.

Target is Target Device Services BPFunction Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | A dictionary of devices' informational snapshots that are grouped by device type (device type string is used as a key). |
