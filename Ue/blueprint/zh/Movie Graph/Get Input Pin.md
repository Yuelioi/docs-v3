---
display_name: Get Input Pin
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Gets the input pin with the specified name, or nullptr if one could not be found. Most pins on a node are
"built-in", meaning they ship with the node. Dynamic pins (pins which are not built-in) can potentially have the
same name as a built-in (eg, the option pins on the Select node). To disambiguate between built-in and dynamic
pins, specify bIsBuiltInPin = false if trying to fetch a pin that is not built-in.

Target is Movie Graph Node

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | In Pin Label |  |
| enum | Pin Requirement |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets the input pin with the specified name, or nullptr if one could not be found. Most pins on a node are"built-in", meaning they ship with the node. Dynamic pins (pins which are not built-in) can potentially have thesame name as a built-in (eg, the option pins on the Select node). To disambiguate between built-in and dynamicpins, specify bIsBuiltInPin = false if trying to fetch a pin that is not built-in. |
