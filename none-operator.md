##None (Javascript Null)

In python NULL variables are known as *None*

To check if a variable is None we use the *is* operator

```python
	foo = None
	if foo is None:
		print("It's not there")

	if foo == None:
		print("It's still not there")
```

In python a viariable is assigned an id

```python
	id(foo) //--> <someId anumber>
```

The *is* operator is faster and the correct way to check for comparison as it does an id comparison. Using the double *==* operator requires a
dictionary to be used and all values to be iterated to find the match

