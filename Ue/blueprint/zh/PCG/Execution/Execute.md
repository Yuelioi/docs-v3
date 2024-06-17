---
title: Execute
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PCG](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG) > [Execution](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG/Execution)

Main execution function that will contain the logic for this PCG Element. Use GetContext to have access to the context.

Target is PCGBlueprint Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Input | Input collection containing all the data passed as input to the node. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Output | Data collection that will be passed as the output of the node, with pins matching the ones provided during the execution. |
