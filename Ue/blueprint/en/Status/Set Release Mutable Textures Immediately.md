---
display_name: Set Release Mutable Textures Immediately
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Status](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Status)

If set to true, Mutable will release Mutable-generated textures immediately when they are no longer used without waiting for GC
IMPORTANT!!! Do NOT keep references to any Mutable generated textures or skeletal meshes if this is enabled,
they are owned by Mutable and will be destroyed without notice

Target is Customizable Object System

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Release Textures |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
