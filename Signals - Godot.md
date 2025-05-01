---
aliases:
  - signal
  - signals
  - Signals
  - Signal
---
[[Godot basics]]
+ [[Nodes - Godot|Nodes]] emit [[Signals - Godot|signals]] when some event occurs. This feature allows you to make nodes communicate without hard-wiring them in code. It gives you a lot of flexibility in how you structure your scenes.
	+ Signals are Godot's version of the _observer_ pattern
	+ For example, buttons emit a signal when pressed. You can connect a piece of code to this signal which will run in reaction to this event, like starting the game or opening a menu.