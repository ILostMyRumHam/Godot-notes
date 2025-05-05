---
aliases:
  - Identifier
  - identifier
  - identifiers
  - Identifiers
---
[[Defining Functions - GDScript]]
[[Functions - GDScript|Functions]] are sequences of instructions we give a name 

Identifier = the name of a given sequence 

+ Identifiers are unique; the same name cannot be reused in a given space of code 
	+ If two functions have the same identifier, GDScript will raise an [[Errors - GDScript|error]]
+ Identifiers cannot contain spaces - use underscores instead
	+ example: "func take_damage(amount):" → [[Defining Functions - GDScript|Defining Functions]] 
	+ and/or use capital letters to start words - except the first one 
		+ example: "func takeDamage(amount):"
+ Identifiers have to start with a letter or an underscore
+ Identifiers cannot begin with a number, but they can be used after the first character