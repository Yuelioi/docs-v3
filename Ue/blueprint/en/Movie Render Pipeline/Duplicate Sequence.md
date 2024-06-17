---
title: Duplicate Sequence
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Duplicates the specified sequence using a medium depth copy. Standard duplication will only duplicate
the top level Sequence (since shots and sub-sequences are other standalone assets) so this function
recursively duplicates the given sequence, shot and subsequence and then fixes up the references to
point to newly duplicated sequences.

Use at your own risk. Some features may not work when duplicated (complex object binding arrangements,
blueprint GetSequenceBinding nodes, etc.) but can be useful when wanting to create a bunch of variations
with minor differences (such as swapping out an actor, track, etc.)

This does not duplicate any assets that the sequence points to outside of Shots/Subsequences.

Target is Movie Pipeline Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Outer | The Outer of the newly duplicated object. Leave null for TransientPackage(); |
| object | In Sequence | The sequence to recursively duplicate. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The duplicated sequence, or null if no sequence was provided to duplicate. |
