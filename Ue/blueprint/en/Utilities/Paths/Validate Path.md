---
display_name: Validate Path
order: 87
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Paths](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Paths)

Validates that the parts that make up the path contain no invalid characters as dictated by the operating system
Note that this is a different set of restrictions to those imposed by FPackageName

Target is Blueprint Paths Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | In Path | path to validate |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Did Succeed | Whether the path could be validated |
| text | Out Reason | If validation fails, this is filled with the failure reason |
