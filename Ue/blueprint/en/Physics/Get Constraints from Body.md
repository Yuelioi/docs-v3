---
display_name: Get Constraints from Body
order: 70
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Gets all the constraints attached to a body

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Body Name | name of the body to get the attached constraints from |
| boolean | Parent Constraints | return constraints where BodyName is the child of the constraint |
| boolean | Child Constraints | return constraints where BodyName is the parent of the constraint |
| boolean | Includes Terminated |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Constraints | returned list of constraints matching the parameters |
