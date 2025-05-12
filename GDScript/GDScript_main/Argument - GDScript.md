---
aliases:
  - arguments
  - argument
  - Arguments
  - Argument
---
# [[Functions - GDScript#Function arguments|Function]] arguments

After defining a [[Functions - GDScript|function]], arguments can be added inside the parentheses when calling it - indented inside the function 

```
func run():
	rotate(0.3)
```
Rotates a given [[Nodes - Godot|node]]/[[Scenes - Godot|scene]] by 0.3 radians, the default GDScript unit for rotation

The part inside the parentheses (0.3) =  the function's [[Argument - GDScript|argument]]

Arguments fine-tune the effect of the function call

Sometimes arguments are necessary for a function to work - the rotate function would call an [[Errors - GDScript|error]] without a valid argument

```
func run():
	move_local_x(20)
	move_local_y(30)
```
These complementary functions take the argument inside the parentheses and offset a given entity by that number of pixels