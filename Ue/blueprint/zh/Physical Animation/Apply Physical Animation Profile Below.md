---
title: Apply Physical Animation Profile Below
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physical Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicalAnimation)

Applies the physical animation profile to the body given and all bodies below.

Target is Physical Animation Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Body Name | The body from which we'd like to start applying the physical animation profile. Finds all bodies below in the skeleton hierarchy. None implies all bodies |
| name | Profile Name | The physical animation profile we'd like to apply. For each body in the physics asset we search for physical animation settings with this name. |
| boolean | Include Self | Whether to include the provided body name in the list of bodies we act on (useful to ignore for cases where a root has multiple children) |
| boolean | Clear Not Found | If true, bodies without the given profile name will have any existing physical animation settings cleared. If false, bodies without the given profile name are left untouched. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
