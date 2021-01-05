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
#### To create a variable with global scope
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
## Python Type Casting

``` int() ``` - constructs an integer number from an integer literal, a float literal (by rounding down to the previous whole number), or a string literal (providing the string represents a whole number)

```float()``` - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)

```str()``` - constructs a string from a wide variety of data types, including strings, integer literals and float literals

