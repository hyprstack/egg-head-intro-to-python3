## Formatting strings in python is similar to that of Javascript

*Differences from Javascript*

- Can be multiline

```python
	"Will's
	 ball is red
	 and bouncy"
```

- Can use triple quotation marks to ignore single quatation marks

```python
	"""Will's ball is red"""
```

*USING PLACEHOLDERS*

- Similar to javascript, we can use placeholders in string formatting

```python
	print("Will's %s is %s." % (item, color))
```

*USING THE **FORMAT** OPERATOR*

- Similar to using placeholders, python has the format operator. Note that the number inside of the curly brackets are positional operators

```python
	print("Will's {0} is {1}".format(item, color))
```
