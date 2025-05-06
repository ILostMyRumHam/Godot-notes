---
aliases:
  - Member variable
  - Member variables
  - member variables
  - member variable
  - variable
  - Variable
  - Variables
  - variables
---
Variables can be stored, retrieved and updated

Variables can be saved, changed, and read later

Variables are labels used to keep track of values that vary over time.

[[Functions - GDScript|function]] [[Parameters - GDScript|parameters]] are a type of variable

Member variables = variables built into Godot 

To work out of the bounds of the predefined variables → [[Defining variables - GDscript|Defining variables]]

# Basic member variables 

+ position
+ rotation
+ scale

Member variables can have [[Sub-variables - GDscript|sub-variables]]
>such as the sub-variables **x** and **y** for the **position** and **scale** variables

To assign a value to a variable - use the = sign

In Godot, the y-axis is positive going down

```gdscript
func run():
	scale.x = 1.5
	scale.y = 1.5
```


## Position + draw_rectangle

```gdscript
func run():
	position.x = 100
	position.y = 100
	draw_rectangle(100, 100)
	position.x = 300
	position.y = 100
	draw_rectangle(100, 100)
	position.x = 500
	position.y = 100
	draw_rectangle(100, 100)
```