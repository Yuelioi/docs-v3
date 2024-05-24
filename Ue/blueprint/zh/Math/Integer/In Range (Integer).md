---
display_name: In Range (Integer)
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Integer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Integer)

Returns true if value is between Min and Max (V >= Min && V \<= Max)
If InclusiveMin is true, value needs to be equal or larger than Min, else it needs to be larger
If InclusiveMax is true, value needs to be smaller or equal than Max, else it needs to be smaller

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Value |  |
| integer | Min |  |
| integer | Max |  |
| boolean | Inclusive Min |  |
| boolean | Inclusive Max |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if value is between Min and Max (V >= Min && V \<= Max)If InclusiveMin is true, value needs to be equal or larger than Min, else it needs to be largerIf InclusiveMax is true, value needs to be smaller or equal than Max, else it needs to be smaller |
