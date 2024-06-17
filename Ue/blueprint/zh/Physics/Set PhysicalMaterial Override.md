---
title: Set PhysicalMaterial Override
order: 49
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Changes the current PhysMaterialOverride for this component.
Note that if physics is already running on this component, this will *not* alter its mass/inertia etc,
it will only change its surface properties like friction.

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | New Phys Material |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
