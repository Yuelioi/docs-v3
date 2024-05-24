---
display_name: Set Wave Parameter
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Parameter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Parameter)

Sets the parameter matching the name indicated to the provided Wave. Provided for convenience/backward compatibility
with SoundCues (The parameter interface supports any object and is up to the system querying it to determine whether
it is a valid type).

Target is Audio Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Name | The name of the parameter to assign the wave to. |
| object | In Wave | The wave value to set. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
