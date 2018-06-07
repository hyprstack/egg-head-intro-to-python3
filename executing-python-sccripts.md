## Executing python scripts

Create a file called *hello.py*

In the file write:

```python
	print("Hello world")
```

Then to run the script (with python 3 as the print fuction is a function in python3)

`python3 hello.py`

To make it a standalone executable file, in the *hello.py* script, write at the top of the file"

`#! /usr/bin/env python` and then in the command line we need to change the file permissions to be an executable - `chmod +x hello.py`

The you can run the file directly with `./hello.py`
