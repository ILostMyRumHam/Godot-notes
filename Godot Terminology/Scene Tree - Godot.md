---
aliases:
  - scene tree
  - Scene tree
  - Scene trees
  - scene trees
---
[[Godot basics]]
All your game's [[Scenes - Godot|Scenes]] come together in the **scene tree**: a [[Trees - Godot|tree]] of scenes. And as scenes are trees of nodes, the scene tree also is a tree of nodes. But it's easier to think of your game in terms of scenes as they can represent characters, weapons, doors, or your user interface.

[[Root Node - Godot|Root node]] = A single node that is at the base of a [[Scene Tree - Godot|scene tree]] 

Each subsystem within your game should have its own section within the SceneTree. You should use [[parent-child relationships]] only in cases where nodes are effectively elements of their parents.