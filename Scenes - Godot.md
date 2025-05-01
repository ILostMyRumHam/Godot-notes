---
aliases:
  - Scenes
  - Scene
  - scenes
  - scene
---
[[Godot basics]]
In Godot, you break down your game in reusable scenes. A scene can be a character, a weapon, a menu in the user interface, a single house, an entire level, or anything you can think of. 

Godot's scenes are flexible; they fill the role of both [[prefabs]] and scenes in some other game engines. 
+ (Such as Unity's usage of the term prefab)

+ Scenes can be nested - Parent and Child scenes

A scene is composed of one or more [[Nodes - Godot|nodes]]. Nodes are your game's smallest building blocks that you arrange into [[Trees - Godot|trees]]. 

All your game's scenes come together in the [[Scene Tree - Godot|scene tree]], literally a tree of scenes. And as scenes are trees of nodes, the scene tree also is a tree of nodes. But it's easier to think of your game in terms of scenes as they can represent characters, weapons, doors, or your user interface.

# Scenes characteristics 

1. Scenes act like nodes
2. They always have one root node, like the "Player" in our example.
3. You can save them to your local drive and load them later.
4. You can create as many instances of a scene as you'd like. You could have five or ten characters in your game, created from your Character scene.

# Scenes workflow 

When you organize [[Nodes - Godot|nodes]] in a [[Trees - Godot|tree]], like our character, we call this [[construct a scene]]. Once saved, scenes work like new [[node types]] in the [[Godot Editor|editor]], where you can add them as a child of an existing node. In that case, the instance of the scene appears as a single node with its internals hidden.

You can compose nodes to create custom and complex node types, like a game character that runs and jumps, a life bar, a chest with which you can interact, and more.

# [[Inheritance - Godot|Inheritance]]

"Inheritance allows you to derive from a [[Scenes - Godot|scene]]: A farmer inherits from the 'human' scene, therefore 'has-a' set of eyes, 'has-a' nose etc. The [[relationship]] is 'is-a'. The farmer 'is-a' human. But the farmer also 'has-a' hat and 'has-a' ability to harvest crops. Changes to the human aggregate to the farmer, but changes to the farmer aren't inherited to the human"
→ Source - godot docs user contributed note by github user "Falco-Boehnke", Jan 22, 2025