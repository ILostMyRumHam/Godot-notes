---
aliases:
  - parameters
  - Parameters
  - Parameter
  - parameter
---
Parameters are labels you give to values passed to the [[Functions - GDScript|function]] 

The parameter name = label used to refer to a value

The value can be: numbers, strings, etc.

You can give a function parameters when writing its definition - [[Defining Functions - GDScript|Defining Functions]]

Names of functions and parameters cannot contain spaces - use underscores or capitalization past the initial word instead as in
+ func move_forward(size)
+ func moveForward(size)

template syntax:
```gdscript 
func function_name(function_parameter):
```

Colon at the end → indicated the start of a new code block

Functions can have multiple parameters - separated by a comma

```gdscript 
func function_name(function_parameter1, function_parameter2, ...):