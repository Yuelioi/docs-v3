---
display_name: Link Anim Class Layers
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Linked Anim Graphs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/LinkedAnimGraphs)

Runs through all layer nodes, attempting to find layer nodes that are implemented by the specified class, then sets up a linked instance of the class for each.
Allocates one linked instance to run each of the groups specified in the class, so state is shared. If a layer is not grouped (ie. NAME_None), then state is not shared
and a separate linked instance is allocated for each layer node.
If InClass is null, then all layers are reset to their defaults.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
