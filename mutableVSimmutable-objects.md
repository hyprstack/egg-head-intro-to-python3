## Mutable Vs Immutable objects in python

Everything is pythnon has an id and a value

```python
	b = []
	id(b) // --> 23456
	b.append(3)
	b // --> 3
	id(b) // --> 23456
```

This list *b* is an example of a mutable object as it returned the same **id** although it's **value** was changed. The same is true for *dictionaries*

Immutable objects can't be altered

Objects that are immutable in python are *strings*, *integers* and *tuples*

```python
	a = 4
	id(a) // --> 6789
	a = a + 1
	id(a) // --> 9876
```
