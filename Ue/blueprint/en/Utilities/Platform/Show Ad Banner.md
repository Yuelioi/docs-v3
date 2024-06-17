---
title: Show Ad Banner
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Platform)

Will show an ad banner (iAd on iOS, or AdMob on Android) on the top or bottom of screen, on top of the GL view (doesn't resize the view)
(iOS and Android only)

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Ad Id Index | The index of the ID to select for the ad to show |
| boolean | Show on Bottom Of Screen | If true, the iAd will be shown at the bottom of the screen, top otherwise |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
