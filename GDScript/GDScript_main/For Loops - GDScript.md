---
aliases:
  - for
  - For
  - for loop
  - For loop
  - for loops
  - For loops
---

# Helper functions 

+ range()
Calling range(n) creates a list of numbers from 0 to n - 1

In a for loop, the computer takes each value inside a list, stores it in a temporary variable and executes the code in the loop once per value

The name of the temporary variable can be anything


```GDScript
func run():
	for element in range(5)
		print (element)
```
> In this case, "element" is the  temporary variable , range is the helper function that determines how long the loop will iterate

# Looping through arrays 

For each element inside the array, the for loops extracts it, stores it in a temporary variable, and executes the loop's code once

A for loop can also access arrays:

```
func run():
	for element in [0, 1, 2]:
		print (element) 
``` 

As Godot moves through the loop, it assigns each value of the [[Arrays - GDScript|array]] to that [[Variables - GDScript|variable]] 

Rather than constantly checking if some value is true or false like a while loop, the for loop knows how many times to check beforehand 