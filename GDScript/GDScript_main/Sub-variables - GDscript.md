---
aliases:
  - sub-variables
  - sub-variable
  - Sub-variable
  - Sub-variables
---
[[Variables - GDScript|Member variables]] can have [[Sub-variables - GDscript|sub-variables]]:
>such as the sub-variables **x** and **y** for the **position** and **scale** variables

To assign a value to a variable - use the = sign

In Godot, the y-axis is positive going down

```gdscript
func run():
	scale.x = 1.5
	scale.y = 1.5
```

Use a dot between the variable name and the sub-variable name to access the sub-variable