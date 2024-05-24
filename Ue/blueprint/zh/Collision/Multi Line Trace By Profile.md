---
display_name: Multi Line Trace By Profile
order: 53
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Trace a ray against the world using a specific profile and return overlapping hits and then first blocking hit
Results are sorted, so a blocking hit (if found) will be the last element of the array
Only the single closest blocking result will be generated, no tests will be done after that

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start | Start of line segment. |
| vector | End | End of line segment. |
| name | Profile Name | The 'profile' used to determine which components to hit |
| boolean | Trace Complex | True to test against complex collision, false to test against simplified collision. |
| object | Actors to Ignore |  |
| enum | Draw Debug Type |  |
| boolean | Ignore Self |  |
| linearcolor | Trace Color |  |
| linearcolor | Trace Hit Color |  |
| real | Draw Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Hits |  |
| boolean | Return Value | True if there was a blocking hit, false otherwise. |
