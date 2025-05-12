---
aliases:
  - Functions that return a value
---
The result of a [[Calling a function - GDScript|function call]] can be assigned to a [[Variables - GDScript|variable]] - it can be reused

Some functions return values, some do not
# Built-in functions that return a value 

+ round() - takes a decimal number as an argument and returns a new number rounded to the nearest digit
+ lerp() - short for "linear interpolate" - calculates and returns a weighted average between two values - takes three arguments - two values to average, and a value between 1.0 and 0.0 to skew the result
	+ Often used to animate things - such as the position between an object and the mouse cursor