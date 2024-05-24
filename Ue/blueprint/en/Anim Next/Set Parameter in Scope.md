---
display_name: Set Parameter in Scope
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Anim Next](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimNext)

Sets a parameter's value in the supplied scope.

Target is Anim Next Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Scope | Scopes corresponding to an existing scope in a schedule, or "None". Passing "None" will apply the parameter to the whole schedule. |
| enum | Ordering | Where to apply the parameter in relation to the supplied scope. Ignored for scope "None". |
| name | Name | The name of the parameter to apply |
| wildcard | Value | The value to set the parameter to |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
