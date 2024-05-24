---
display_name: Capture Niagara Sim Cache Immediate
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraSimCache)

Captures the simulations current frame data into the SimCache.
This happens immediately so you may need to be careful with tick order of the component you are capturing from.
The return can be invalid if the component can not be captured for some reason (i.e. not active).
When AdvanceSimulation is true we will manually advance the simulation one frame using the provided AdvanceDeltaTime before capturing.

Target is Niagara Sim Cache Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sim Cache |  |
| struct | Create Parameters |  |
| object | Niagara Component |  |
| boolean | Advance Simulation |  |
| real | Advance Delta Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Sim Cache |  |
| boolean | Success | Captures the simulations current frame data into the SimCache.This happens immediately so you may need to be careful with tick order of the component you are capturing from.The return can be invalid if the component can not be captured for some reason (i.e. not active).When AdvanceSimulation is true we will manually advance the simulation one frame using the provided AdvanceDeltaTime before capturing. |
