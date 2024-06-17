---
title: Create Controls and Body Modifiers from Limb Bones
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a collections of controls and body modifiers for a character, based on the description passed in.
This makes:

- World-space controls
- Parent-space controls
- Body modifiers
  for all the body parts. In addition, they get added to sets, so they can be referenced later. Each control
  is added to three sets:
- "All"
- "ControlType - i.e. "WorldSpace" or "ParentSpace", each of which will end up containing all controls of that type
- "ControlType_LimbName" - e.g. "WorldSpace_ArmLeft" or "ParentSpace_Head"
  Each body modifier is added to "All" and a set named after the limb - e.g. "Spine" or "LegRight".
  It is also possible to specify a mesh component to use for the "world" object - so that the world controls can
  be made to work in the space of another object (or a bone if that is a skeletal mesh component)

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component |  |
| struct | Limb Setup Data |  |
| struct | World Space Control Data |  |
| struct | Parent Space Control Data |  |
| struct | Body Modifier Data |  |
| object | World Component |  |
| name | World Bone Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | All World Space Controls |  |
| name | Limb World Space Controls |  |
| struct | All Parent Space Controls |  |
| name | Limb Parent Space Controls |  |
| struct | All Body Modifiers |  |
| name | Limb Body Modifiers |  |
