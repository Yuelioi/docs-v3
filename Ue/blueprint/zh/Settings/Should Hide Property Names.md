---
title: Should Hide Property Names
order: 140
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Determines if the public properties on the query class will have their names hidden in the details panel. Returns
false by default. Most query subclasses will only have one property and do not need to clutter the UI with the
property name (eg, the "Actor Name" query only shows one text box with entries for the actor names, no need to
show the property name).

Target is Movie Graph Condition Group Query Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Determines if the public properties on the query class will have their names hidden in the details panel. Returnsfalse by default. Most query subclasses will only have one property and do not need to clutter the UI with theproperty name (eg, the "Actor Name" query only shows one text box with entries for the actor names, no need toshow the property name). |
