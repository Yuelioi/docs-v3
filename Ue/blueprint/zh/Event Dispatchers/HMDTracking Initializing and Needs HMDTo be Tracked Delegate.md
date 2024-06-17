---
title: HMDTracking Initializing and Needs HMDTo be Tracked Delegate
order: 36
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

This will be called on Morpheus if the HMD starts up and is not fully initialized (in NOT_STARTED or CALIBRATING states).
The HMD will stay in NOT_STARTED until it is successfully position tracked. Until it exits NOT_STARTED orientation
based reprojection does not happen. Therefore we do not update rotation at all to avoid user discomfort.
Instructions to get the hmd tracked should be shown to the user.
Sony may fix this eventually. (PS4 Only)
