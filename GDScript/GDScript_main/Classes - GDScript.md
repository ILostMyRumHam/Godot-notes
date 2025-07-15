---
aliases:
  - class
  - Classes
  - classes
  - Class
  - OOP
---
GDScript is an Object-oriented language.

Every [[Scripts - Godot|script]] in Godot represents a class and extends one of the engine's built-in classes.

The node types your classes inherit from give you access to properties, such as `rotation` and `position` in our sprite's case.

Godot provides several virtual [[Functions - GDScript|functions]] you can define to connect your class with the engine. These include `_process()`, to apply changes to the [[Nodes - Godot|node]] every frame, and `_unhandled_input()`, to receive [[Player Input - Godot|input]] events like key and button presses from the users. There are quite a few more.