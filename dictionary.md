```python
d = {
	"a": 1,
	"b": 2,
	"c": 3,
}
```

to

```go
m := map[string]int{
	"a": 1,
	"b": 2,
	"c": 3, // end , is nessesary here
}
```

```go
func likeMap(s string) int {
	switch s {
	case "a":
		return 1
	case "b":
		return 2
	case "c":
		return 3
	}
	panic("don't have the key")
}
```
