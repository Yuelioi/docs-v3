---
display_name: Resolve with Stage Actor
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Dynamic Binding](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/DynamicBinding)

Resolves a Sequencer Dynamic Binding described on Params, returning the actor or component that the Sequencer
should bind to

Target is Usd Dynamic Binding Resolver Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Params | The binding to resolve |
| string | Stage Actor IDName Filter | The "ID Name"/FName of a AUsdStageActor to restrict our search for actor and components to. Can be empty. |
| string | Root Layer Filter | The root layer file path to restrict our search for actor and components to. This should match what is shown on the Stage Actor's RootLayer property. Can be empty. |
| string | Prim Path | The path to the prim that generates the actor or component that this binding should resolve to (e.g. '/cube') |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The result struct containing the resolved UObject |
