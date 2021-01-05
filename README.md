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

## Python Conditions

```If elif else Nested If ```

```python
if x < y:
  print('x is less than y')
elif x > y:
  print('x is greater than y')
else:
  print('x and y are equal')
```

#### Short If else

```python
a = 2
b = 330
print("A") if a > b else print("B")
```

#### Pass Statement

if statements cannot be empty, but if you for some reason have an if statement with no content, put in the pass statement to avoid getting an error.

```python
if b > a:
  pass
  ```