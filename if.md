if-else

```python
# python
if s == "the string":
	return True
else:
	return False
```

```go
// go
if s == "the string" {
	return true
} else {
	return false
}
```

if-elif-else

```python
# python
if i > 0 :
	return "positive"
elif i < 0:
	return "negative"
else:
	return "zero"
```

```go
// go
if i > 0 {
	return "positive"
} else if i < 0 {
	return "negative"
} else {
	return "zero"
}
```

if-elif-else (chain)
```python
# python
if fruit == "apple":
	color = "red"
else if fruit == "banana" or fruit == "mango":
	color = "yellow"
else if fruit == "melon":
	color = "green"
else:
	color = "unknown"
```

```go
// go
var color string
switch fruit {
case "apple":
	color = "red"
case "banana", "mango":
	color = "yellow"
case "melon":
	color = "green"
default:
	color = "unknown"
}
```
