---
aliases:
  - Defining Functions
  - defining functions
  - Defining functions
---
 >Example: Defining a function
```
# GDScript 
func take_damage(amount):
	health -= amount
	if health < 0:
		die()
```

A [[Functions - GDScript|function]] is a list of instructions with an exact name  

Functions are groups of instructions we reuse every time we [[Calling a function - GDScript|call]] the function

[[Calling a function - GDScript|Calling a function]] = signalling to the computer to execute a fuction