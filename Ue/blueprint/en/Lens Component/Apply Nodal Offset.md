---
display_name: Apply Nodal Offset
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lens Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LensComponent)

Manually apply nodal offset to the specified component.
If bUseManualInputs is true, the input Focus and Zoom values will be used to evaluate the LensFile .
If bUseManualInputs is false, the LensFile be will evaluated based on the Lens Component's evaluation mode.

Target is Lens Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Component to Offset |  |
| boolean | Use Manual Inputs |  |
| real | Manual Focus Input |  |
| real | Manual Zoom Input |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
