---
title: Is Named Resolution Valid
order: 56
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Utility function for checking if a given resolution profile name is valid, since NamedResolutionFromProfile
will throw a kismet exception, but blueprints can't actually try/catch them.

Target is Movie Graph Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| name | In Resolution Profile Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Utility function for checking if a given resolution profile name is valid, since NamedResolutionFromProfilewill throw a kismet exception, but blueprints can't actually try/catch them. |
