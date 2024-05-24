---
display_name: Make Path Relative To
order: 60
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Paths](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Paths)

Assuming both paths (or filenames) are relative to the same base dir, converts InPath to be relative to InRelativeTo

Target is Blueprint Paths Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | In Path | Path to change to be relative to InRelativeTo |
| string | In Relative To | Path to use as the new relative base |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Out Path |  |
| boolean | Return Value | true if OutPath was changed to be relative |
