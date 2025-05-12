---
aliases:
  - 2D Vector
  - 2d vector
  - 2D Vectors
  - 2D vector
  - 2D vectors
  - Vector2
---
In Godot 2D vectors are a common value type - called Vector2

Unlike plain numbers, they store two decimal numbers - one for x coordinates, one for y coordinates

Vectors allow you to represent the speed of an object, the direction of its movement, calculate the distance to a target and more

Some [[Variables - GDScript|Member variables]] such as scale or position have x and y [[Sub-variables - GDscript|sub-variables]] so Godot uses a Vector2 to store their values

To [[Calling a function - GDScript|call]] a Vector2 use parentheses after the name of the function and two [[Argument - GDScript|arguments]] inside the parentheses as in: 
```GDscript
func level_up():
	scale += Vector2(20, 0.2)

```
x = 20
y = 0.2

Vector two together with the scale and position functions + [[Sub-variables - GDscript|sub-variables]] 

```GDScript
func reset_robot():
	position = Vector2(0, 0)
	scale = Vector2(1.0, 1.0)
```