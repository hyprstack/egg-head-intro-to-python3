## Manipulating and searching strings with python methods

- Check if a string ends with a set of characters

```python
	my_string = "The ball is red"
	substring = "red"
	my_string.endswith(substring) // true
```

- Find the position of a substring or -1 if it doesn't exist

```python
	"The ball is red".find("is") // 9
	"The ball is red".find("foo") // -1
```

- Join a list of words to form a string

```python
	"".join(["the", "ball", "is", "red"]) // the ball is red
```

- Strip white space from the start and end of a string

```python
	" Will ".strip() // 'Will'
```

- Strip the whitespace from the end of a string

```python
	" Will ".lstrip() // ' Will'
```

- Strip the whitespace from the start of a string

```pyton
	" Will ".rstrip // 'Will '
```


- To get a list of all possible methods you can do with string in python

```python
	dir('Will') // List of all methods for strings
```
