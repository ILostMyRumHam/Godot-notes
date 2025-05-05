[[GDScript X Other Languages]]

# Defining Functions

```gdscript
# GDScript 
func take_damage(amount):
	health -= amount
	if health < 0:
		die()
```

```js
// Javascript 
function take_damage(amount) {
	health -= amount
	if (health < 0) {
		die()
	}
}
```
