---
display_name: Add Input Profile with Currently Active Mappings
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [VCam Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VCamInput)

Tries to add a new Input Profile to the VCam Input Settings and populates it with any currently active player mappable keys
Note: The set of currently active player mappable keys may be larger than the set of mappings in this component's Input Profile

Optionally this function can update an existing profile, this will only add any mappable keys that don't currently exist in the profile but will not remove any existing mappings
Returns whether the profile was successfully added or updated

Target is VCam Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Profile Name |  |
| boolean | Update if Profile Already Exists |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | Tries to add a new Input Profile to the VCam Input Settings and populates it with any currently active player mappable keysNote: The set of currently active player mappable keys may be larger than the set of mappings in this component's Input ProfileOptionally this function can update an existing profile, this will only add any mappable keys that don't currently exist in the profile but will not remove any existing mappingsReturns whether the profile was successfully added or updated |
