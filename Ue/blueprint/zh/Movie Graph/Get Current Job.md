---
display_name: Get Current Job
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Returns the internal job being used by the Movie Graph Pipeline, which is a duplicate of
the job provided originaly by Initialize. This allows scripting to mutate the job/configuration
without leaking changes into assets or the original user-defined queue entry.

Target is Movie Graph Pipeline

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Returns the internal job being used by the Movie Graph Pipeline, which is a duplicate ofthe job provided originaly by Initialize. This allows scripting to mutate the job/configurationwithout leaking changes into assets or the original user-defined queue entry. |
