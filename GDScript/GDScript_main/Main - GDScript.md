[[GDScript X Other Languages]]

https://docs.godotengine.org/en/stable/getting_started/step_by_step/scripting_languages.html

[GDScript](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/index.html#doc-gdscript) is an object oriented and imperative programming language built for Godot. It's made by and for game developers to save you time coding games. Its features include:

- A simple syntax that leads to short files.
    
- Blazing fast compilation and loading times.
    
- Tight editor integration, with code completion for nodes, signals, and more information from the scene it's attached to.
    
- Built-in vector and transform types, making it efficient for heavy use of linear algebra, a must for games.
    
- Supports multiple threads as efficiently as statically typed languages.
    
- No garbage collection, as this feature eventually gets in the way when creating games. The engine counts references and manages the memory for you in most cases by default, but you can also control memory if you need to.
    
- Gradual typing. Variables have dynamic types by default, but you also can use type hints for strong type checks.
# [[Defining Functions - GDScript|Defining Functions]]
```
# GDScript 
func take_damage(amount):
	health -= amount
	if health < 0:
		die()
```


# [[Calling a function - GDScript|Calling a function]] 


# [[Variables - GDScript|Variables]]