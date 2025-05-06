---
aliases:
  - Defining variables
  - defining variables
  - Defining a variable
  - defining a variable
---
Variables can be stored, retrieved and updated

Variables can be saved, changed, and read later

Variables are labels used to keep track of values that vary over time.

```
func run():
	var health = 5 
	health = health - 1
	print(jhhealth)
```

To use a [[Variables - GDScript|variable]] that is not predefined, it must be defined so that the engine recognises its name 

Variables are case-sensitive 

A variable's name must be unique inside a given code file 

The keyword var is used to initially define a variable - to call a variable later, simply write its name

Variable names should describe the value they contain

Can be defined outside and inside a function, depending on context

+ [[Script-wide variables - GDScript|Script-wide variables]] = Variables defined outside of functions can be re-used in different functions 
+ Variables inside function - can only be used by that function, as long as the variable is defined before it is called

```gdscript
var variable_name = value
```

[[Variable types]]