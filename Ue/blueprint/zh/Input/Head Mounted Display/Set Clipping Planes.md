---
display_name: Set Clipping Planes
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

Sets near and far clipping planes (NCP and FCP) for stereo rendering. Similar to 'stereo ncp= fcp' console command, but NCP and FCP set by this
call won't be saved in .ini file.

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Near | (in) Near clipping plane, in centimeters |
| real | Far | (in) Far clipping plane, in centimeters |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
