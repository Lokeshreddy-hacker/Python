# Python Key Cheet

#### To get quick overview of python syntax,tips and tricks

## Python Data Types

```pyython
Text Type:	   str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	    set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
```
#### To use create a variable global scope
```python
# Example 1
x = "awesome"
def myfunc():
  global x
  x = "fantastic"
myfunc()
print("Python is " + x) # Python is fantastic

# Example 2
def myfunc():
  global x
  x = "fantastic"
myfunc()
print("Python is " + x)  #Python is fantastic

```
