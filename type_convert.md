string to int

```python
s = "1"
i = int(s)

s = "a"
try:
	i = int(s) # it will raise exception
except:
	# do somthing here
```
>>

```go
s := "1"
i := strconv.Atoi(s)

s := "a"
i, err := strconv.Atoi(s)
if err != nil {
	// do something here
}
