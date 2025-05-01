---
aliases:
  - node
  - nodes
  - Nodes
  - Node
---
[[Godot basics]]
A [[Scenes - Godot|scene]] is composed of one or more nodes. Nodes are your game's smallest building blocks that you arrange into [[Trees - Godot|trees]].  

Nodes are the **fundamental building blocks** of a Godot project

+ Nodes and scenes look the same in the editor
+ Together, nodes form a tree [[Trees - Godot|tree]]
+ A [[Trees - Godot|tree]] of nodes can be saved as a [[Scenes - Godot|scene]] - it shows as a single node, internal structure is hidden
+ Since different nodes have different functions, combining them produces more complex behavior

+ Nodes emit [[Signals - Godot|signals]] when some event occurs. This feature allows you to make nodes communicate without hard-wiring them in code. It gives you a lot of flexibility in how you structure your scenes.
	+ Signals are Godot's version of the _observer_ pattern
	+ For example, buttons emit a signal when pressed. You can connect a piece of code to this signal which will run in reaction to this event, like starting the game or opening a menu.

# Nodes characteristics

- A name.
- Editable properties.
- They receive callbacks to update every frame.
- You can extend them with new properties and functions.
- You can add them to another node as a child.

# Nodes basic workflow 

Nodes are your game's smallest building blocks. You combine them to create [[Scenes - Godot|scenes]] that you then combine and nest into the [[Scene Tree - Godot|scene tree]]. You can then use [[Signals - Godot|signals]] to make nodes react to events in other nodes or different [[Scene Tree - Godot|scene tree]] branches.

Godot offers many different types of objects called nodes, each with a specific purpose. Nodes are part of a [[Trees - Godot|tree]] and always inherit from their parents up to the [[Node class]]. Although the engine does feature some nodes like[[ collision shapes]] that a parent physics body will use, most nodes work independently from one another.

In other words, Godot's nodes do not work like components in some other game engines.

A game should have an entry point; for traditional applications, this is normally a "main" function. In Godot, it's a [[Main node]].

# Root node 

A single node that is at the base of a [[Scene Tree - Godot|scene tree]]

# Base Node types 

[[Node2D]]
[[AnimatedSprite2D]]
Sprite2D 
Node2D 
CanvasItem
Node