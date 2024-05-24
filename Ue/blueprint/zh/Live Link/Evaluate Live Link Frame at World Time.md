---
display_name: Evaluate Live Link Frame at World Time
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LiveLink)

Attempts to Get a LiveLink Frame from a subject using a given Role

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Subject | Live Link Subject Name Structure SubjectThe Live Link Subject Name to get a frame from |
| class | Role | Live Link Role Class Reference RoleThe Live Link Role the data will be converted to. |
| real | World Time | Float (double-precision) World TimeThe World Time the subject will be evaluated to |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Valid Frame |  |
| exec | Invalid Frame |  |
| wildcard | Data Result | Wildcard Data ResultThe data struct, if a frame was present for the given role |
