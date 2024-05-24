---
display_name: Montage Set Next Section
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Relink new next section AFTER SectionNameToChange in run-time
You can link section order the way you like in editor, but in run-time if you'd like to change it dynamically,
use this function to relink the next section
For example, you can have Start->Loop->Loop->Loop.... but when you want it to end, you can relink
next section of Loop to be End to finish the montage, in which case, it stops looping by Loop->End.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Section Name to Change | : This should be the name of the Montage Section after which you want to insert a new next section |
| name | Next Section | : new next section |
| object | Montage |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
