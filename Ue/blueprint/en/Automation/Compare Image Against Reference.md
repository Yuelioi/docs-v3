---
display_name: Compare Image Against Reference
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Automation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Automation)

request image comparison.

Target is Automation Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Image File Path | Absolute path to the image location. All 8bit RGBA channels supported formats by the engine are accepted. |
| string | Comparison Name | Optional name for the comparison, by default the basename of ImageFilePath is used |
| enum | Comparison Tolerance |  |
| string | Comparison Notes |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if comparison was successfully enqueued |
