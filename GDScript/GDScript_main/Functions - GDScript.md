---
aliases:
  - Functions
  - Function
  - functions
  - function
---
Function =  a list of instructions with an exact name  

+ Functions are named sequences of instructions
+ Functions are groups of [[Instructions - GDScript|instructions]] we reuse every time we [[Calling a function - GDScript|call]] the function.
+ You can modify a functions behaviour using [[Parameters - GDScript|parameters]]

[[Identifier - GDScript|Identifier]] = the name of these sequences

[[Instructions - GDScript|Instructions]] = operations the computer recognizes, must be nested within a function (indented)

[[Calling a function - GDScript|Calling a function]] = giving the computer instructions to execute a function

>To call a function in GDScript, you write its exact name followed by an open and closed parenthesis

Creating a function is necessary to execute instructions in GDScript

In GDScript, code is written inside of custom functions - the example used here is the "run()" function

# Basic Functions 

+ show() = makes something visible 
```
func run():
	show()
```
+ hide() = makes something invisible
```
func run():
	show()
```
+ rotate(radians) = rotates an entity - positive numbers lead to clockwise rotation, negative numbers lead to a counterclockwise rotation 
```
func run():
	rotate(0.5)
```

# Function arguments 

After defining a function, arguments can be added inside the parentheses when calling it - indented inside the function 

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
