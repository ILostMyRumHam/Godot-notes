---
aliases:
  - Type hints
  - type
  - type hints
---
By default, Godot is a dynamically-typed languages. Variables can be assigned values of different types over the course of the program.

This can sometimes cause Type errors when the computer expects a different type from a variable 

GDScript has optional (but preferred) type hints 

To specify the type a variable can accept, you can write a colon and [[Value types - GDScript|type]] after the name when defining a [[Variables - GDScript|variable]] 

```GDScript
var health: int = 100
var player_name: String = "hiya"
var cell_size: Vector2 = Vector2(50.0, 50.0)
var inventory: dict = {"scroll" : 1, "trousers" : 2}
```

→ [[Defining variables - GDscript]] 

GDScript by default utilizes type inference - in many cases, the computer can figure out the type of a variable on its own