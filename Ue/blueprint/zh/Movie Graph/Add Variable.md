---
display_name: Add Variable
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Adds a new variable member with default values to the graph. The new variable will have a base name of
"Variable" unless specified in InCustomBaseName. Returns the new variable on success, else nullptr.

Target is Movie Graph Config

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Custom Base Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a new variable member with default values to the graph. The new variable will have a base name of"Variable" unless specified in InCustomBaseName. Returns the new variable on success, else nullptr. |
