### Variables, expressions, and statements
### 🔲 Values and types
A value is one of the basic things a program works with, like a letter or a number. The values we have seen so far are 1, 2, and “Hello, World!”

These values belong to different types: 2 is an integer, and “Hello, World!” is a string, so called because it contains a “string” of letters. You (and the interpreter) can identify strings because they are enclosed in quotation marks.

The print statement also works for integers. We use the python command to start the interpreter.

```Python
python
>>> print(4)
4
```
### 🔲 Variables

### 🔲 Variable names and keywords

```Python
False      await      else       import     pass
None       break      except     in         raise
True       class      finally    is         return
and        continue   for        lambda     try
as         def        from       nonlocal   while
assert     del        global     not        with
async      elif       if         or         yield
```


### 🔲 Statements

A statement is a unit of code that the Python interpreter can execute. We have seen two kinds of statements: print being an expression statement and assignment.


When you type a statement in interactive mode, the interpreter executes it and displays the result, if there is one.

A script usually contains a sequence of statements. If there is more than one statement, the results appear one at a time as the statements execute.

For example, the script
```
print(1)
x = 2
print(x)
```
```
produces the output

1
2
```
The assignment statement produces no output.

### 🔲 Operators and operands

Operators are special symbols that represent computations like **addition** and **multiplication**. The values the operator is applied to are called **operands**.

The operators **`+`**, **`-`**, **`*`**, **`/`**, and **`**`** perform **addition**, **subtraction**, **multiplication**, **division**, and **exponentiation**, as in the following examples:
```Python
20+32
hour-1
hour*60+minute
minute/60
5**2
(5+9)*(15-7)
```
There has been a change in the division operator between Python 2 and Python 3. In Python 3, the result of this division is a floating-point result:

```Python
>>> minute = 59
>>> minute/60
0.9833333333333333
```
The division operator in Python 2 would divide two integers and truncate the result to an integer:

```Python
>>> minute = 59
>>> minute/60
0
```
To obtain the same answer in Python 3 use floored ( **`//`** integer) division.
```Python
>>> minute = 59
>>> minute//60
0
```
In Python 3 integer division functions much more as you would expect if you entered the expression on a calculator.


















