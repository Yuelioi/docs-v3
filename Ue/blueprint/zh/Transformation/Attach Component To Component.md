---
display_name: Attach Component To Component
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Attach this component to another scene component, optionally at a named socket. It is valid to call this on components whether or not they have been Registered.

Target is Scene Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Parent | Parent to attach to. |
| name | Socket Name | Optional socket to attach to on the parent. |
| enum | Location Rule | How to handle translation when attaching. |
| enum | Rotation Rule | How to handle rotation when attaching. |
| enum | Scale Rule | How to handle scale when attaching. |
| boolean | Weld Simulated Bodies | Whether to weld together simulated physics bodies. This transfers the shapes in the welded object into the parent (if simulated), which can result in permanent changes that persist even after subsequently detaching. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if attachment is successful (or already attached to requested parent/socket), false if attachment is rejected and there is no change in AttachParent. |
