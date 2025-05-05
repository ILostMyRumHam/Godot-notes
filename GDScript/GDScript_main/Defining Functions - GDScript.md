---
aliases:
  - Defining Functions
  - defining functions
  - Defining functions
---
 >Example: Defining a function
```gdscript

func take_damage(amount):
	health -= amount
	if health < 0:
		die()
```

A [[Functions - GDScript|function]] is a list of instructions with an exact name  

Functions are groups of instructions we reuse every time we [[Calling a function - GDScript|call]] the function

[[Calling a function - GDScript|Calling a function]] = signalling to the computer to execute a fuction

# Structure 

A function definition starts with the "func" keyword followed by a space, the function's name, parentheses, and a colon 

```gdscript 
func name():
	instruction_1
	instruction_2
	instruction3
```
[[Instructions - GDScript|Instructions]] within the [[Functions - GDScript|function]] must all be indented - tab or 4 spaces, tab is standard