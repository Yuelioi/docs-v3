---
title: Get Skeletal Mesh Embedded Positions
order: 86
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Get the current positions of the transformation hierarchy from \\c TargetDeformationSkeleton,
deformed by the tetrahedral mesh. Results can be in world space postions/deltas, component space
positions/deltas, or bone space positions/deltas. If a bone space is desired \\p TargetBone
must indicate which bone to use. TargetDeformationSkeletonOffset is an offset transform that moves
the \\c TargetDeformationSkeleton to be co-located with the flesh mesh.

Target is Deformable Tetrahedral Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Format |  |
| transform | Target Deformation Skeleton Offset |  |
| name | Target Bone |  |
| real | Simulation Blend Weight |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Get the current positions of the transformation hierarchy from \\c TargetDeformationSkeleton,deformed by the tetrahedral mesh. Results can be in world space postions/deltas, component spacepositions/deltas, or bone space positions/deltas. If a bone space is desired \\p TargetBonemust indicate which bone to use. TargetDeformationSkeletonOffset is an offset transform that movesthe \\c TargetDeformationSkeleton to be co-located with the flesh mesh. |
