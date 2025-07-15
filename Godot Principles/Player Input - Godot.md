---
aliases:
  - input
  - inputs
  - Player Input
  - player input
  - Player input
---
Main source: https://docs.godotengine.org/en/stable/getting_started/step_by_step/scripting_player_input.html

Two main tools to process the player's input in Godot:

1. The built-in input callbacks, mainly `_unhandled_input()`. Like `_process()`, it's a built-in virtual function that Godot calls every time the player presses a key. It's the tool you want to use to react to events that don't happen every frame, like pressing Space to jump. 

2. The `Input` singleton. A singleton is a globally accessible object. Godot provides access to several in scripts. It's the right tool to check for input every frame.
	+  The `Input` singleton allows you to react to the players' input anywhere in your code. In particular, you'll get to use it in the `_process()` loop.