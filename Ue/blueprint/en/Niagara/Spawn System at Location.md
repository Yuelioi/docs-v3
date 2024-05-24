---
display_name: Spawn System at Location
order: 80
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Spawns a Niagara System at the specified world location/rotation

Target is Niagara Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | System Template |  |
| vector | Location |  |
| rotator | Rotation |  |
| vector | Scale |  |
| boolean | Auto Destroy |  |
| boolean | Auto Activate |  |
| enum | Pooling Method |  |
| boolean | Pre Cull Check |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The spawned UNiagaraComponent |
