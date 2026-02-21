### ⬛ Functions
### 🔲 Function calls
In the context of programming, a function is a named sequence of statements that performs a computation. When you define a function, you specify the name and the sequence of statements. Later, you can “call” the function by name. We have already seen one example of a function call:
```Python
>>> type(32)
<class 'int'>
``` 
The name of the function is type. The expression in parentheses is called the argument of the function. The argument is a value or variable that we are passing into the function as input to the function. The result, for the type function, is the type of the argument.

It is common to say that a function “takes” an argument and “returns” a result. The result is called the return value.


### 🔲 Built-in functions
Python provides a number of important built-in functions that we can use without needing to provide the function definition. The creators of Python wrote a set of functions to solve common problems and included them in Python for us to use.

The max and min functions give us the largest and smallest values in a list, respectively:
```Python
>>> max('Hello world')
'w'
>>> min('Hello world')
' '
>>>
``` 
The max function tells us the “largest character” in the string (which turns out to be the letter “w”) and the min function shows us the smallest character (which turns out to be a space).

Another very common built-in function is the len function which tells us how many items are in its argument. If the argument to len is a string, it returns the number of characters in the string.
```Python
>>> len('Hello world')
11
>>>
``` 
These functions are not limited to looking at strings. They can operate on any set of values, as we will see in later chapters.

You should treat the names of built-in functions as reserved words (i.e., avoid using “max” as a variable name).
