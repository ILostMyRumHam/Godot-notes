---
aliases:
  - array
  - arrays
  - Array
  - Arrays
---
A list of values that stores them - stacks of data

The types of value can be mixed

The don't need to follow one another

Arrays themselves are a [[Value types - GDScript|value type]]

Arrays can be assigned to variables 

You can pass arrays in a [[Functions - GDScript|function]] [[Calling a function - GDScript|call]] as arguments

```GDScript
var numbers_array = [1, 2, 6, 7]
var vectors_and_numbers = [Vector2(0, 0), Vector2(4, 3), 5, -1.0]
```
A mix of Vector2, ints and floats

Example 
+ Pathfinding algorithms that use arrays of Vetor2 coordinates to represent the path

# Looping over arrays

A [[For Loops - GDScript|for]] loop can be used to iterate through any array

For each element inside the array, the for loops extracts it, stores it in a temporary variable, and executes the loop's code once


```
func run():
	for element in [0, 1, 2]:
		print (element) 
``` 
+ (This is effectively writing out the helper function "range(3)")
+ Why is 3 not included in the array then? Because the number that determines the range is non-inclusive. For iterating up to 3, it would have to be "range(4)"

The array can also be stored in a variable for easy access

```
var array_of_numbers = [0, 1, 2]
for number in array_of_numbers:
	print(number)
```
+ "number" is the temporary variable of the for loop, "array_of_numbers" is the local variable assigned to the array storing three numbers 0, 1 and 2. The function will extract each of the numbers from the array sequentially and print them out on a separate line

# Array functions 

+ append() - appends a new value at the end of an array 
>	variable.append(different_variable)
+ pop_front() - removes a value from the beginning of an array - first value
+ pop_back - removes a value from the end of an array - last value