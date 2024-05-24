---
display_name: Set Niagara System Asset
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Switch which asset the component is using.
This requires Niagara to wait for concurrent execution and the override parameter store to be synchronized with the new asset.
By default existing parameters are reset when we call SetAsset, modify bResetExistingOverrideParameters to leave existing parameter data as is.

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Asset |  |
| boolean | Reset Existing Override Parameters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
