string to int

```python
# python
s = "1"
i = int(s)

s = "a"
try:
	i = int(s) # it will raise exception
except:
	# do somthing here
```

```go
// go
s := "1"
i := strconv.Atoi(s)

s := "a"
i, err := strconv.Atoi(s)
if err != nil {
	// do something here
}
```

int to string

```python
# python
i = 1
s = string(i)
```

```go
// go
i := 1
s := strconv.Itoa(i)
```
