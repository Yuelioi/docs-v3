---
display_name: Get Components By Class
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Actor)

Gets all the components that inherit from the given class.
Currently returns an array of UActorComponent which must be cast to the correct type.
This intended to only be used by blueprints. Use GetComponents() in C++.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| class | Component Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets all the components that inherit from the given class.Currently returns an array of UActorComponent which must be cast to the correct type.This intended to only be used by blueprints. Use GetComponents() in C++. |
