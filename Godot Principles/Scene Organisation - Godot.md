---
aliases:
  - scene organisation
  - Scene organisation
  - Scene Organisation
  - scene organization
  - Scene organization
  - Scene Organization
---

When possible, utilize focused, singular-purpose [[classes]] with [[loose coupling]] to other parts of the codebase

If possible, [[Scenes - Godot|scenes]] should have no dependencies 

+ Scenes should be self-reliant 
+ Scenes should only rely on data internal to the scene
+ Scenes operate best when they operate alone


Key to scene organization: 

+ Considering the [[Scene Tree - Godot|Scene tree]] in **relational** terms rather than **spatial** terms. 

# Key questions for effective scene organization

+ Are the nodes dependent on their parent's existence? 
  
>If not, then they can thrive all by themselves somewhere else. 
>
>If they are dependent, then it stands to reason that they should be children of that parent (and likely part of that parent's scene if they aren't already).
>[[Parent-child relationships - Godot|Parent-child relationships]] 

+ Are nodes themselves components? 
>Not at all. Godot's [[Nodes - Godot|node]] [[Trees - Godot|trees]] form an [[Aggregation - Godot|aggregation]] relationship, not one of composition. 
>But while you still have the flexibility to move nodes around, it is still best when such moves are unnecessary by default.