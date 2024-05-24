---
display_name: In Range (Float)
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Float](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Float)

Returns true if value is between Min and Max (V >= Min && V \<= Max)
If InclusiveMin is true, value needs to be equal or larger than Min, else it needs to be larger
If InclusiveMax is true, value needs to be smaller or equal than Max, else it needs to be smaller

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| real | Value |  |
| real | Min |  |
| real | Max |  |
| boolean | Inclusive Min |  |
| boolean | Inclusive Max |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if value is between Min and Max (V >= Min && V \<= Max)If InclusiveMin is true, value needs to be equal or larger than Min, else it needs to be largerIf InclusiveMax is true, value needs to be smaller or equal than Max, else it needs to be smaller |
