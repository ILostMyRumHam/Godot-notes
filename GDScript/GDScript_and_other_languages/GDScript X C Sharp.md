# [[Defining Functions - GDScript|Defining Functions]]
```GDScript
func _init():
	print("Hello, world!")
```

```c#
public MySprite2D()
{
    GD.Print("Hello, world!");
}
```

# [[Defining variables - GDscript|Defining variables]]

```GDScript
extends Sprite2D

var speed = 400
var angular_speed = PI


func _process(delta):
'''Rotate and move a Sprite2D in circles'''
	rotation += angular_speed * delta

	var velocity = Vector2.UP.rotated(rotation) * speed

	position += velocity * delta
```

```C#
using Godot;
using System;

public partial class MySprite2D : Sprite2D
{
    private int _speed = 400;
    private float _angularSpeed = Mathf.Pi;

    public override void _Process(double delta)
    '''Rotate and move a Sprite2D in circles'''
    {
        Rotation += _angularSpeed * (float)delta;
        var velocity = Vector2.Up.Rotated(Rotation) * _speed;

        Position += velocity * (float)delta;
    }
}
```

