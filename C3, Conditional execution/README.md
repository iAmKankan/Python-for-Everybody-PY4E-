### ⬛ Conditional execution
### 🔲 Boolean expressions
A Boolean expression is an expression that is either true or false. The following examples use the operator **`==`**, which compares two operands and produces **`True`** if they are equal and **`False`** otherwise:
```Python
>>> 5 == 5
True
>>> 5 == 6
False
```
**`True`** and **`False`** are special values that belong to the class **`bool`**; they are not strings:

```Python
>>> type(True)
<class 'bool'>
>>> type(False)
<class 'bool'>
```
The **`==`** operator is one of the comparison operators; the others are:
```Python
x != y               # x is not equal to y
x > y                # x is greater than y
x < y                # x is less than y
x >= y               # x is greater than or equal to y
x <= y               # x is less than or equal to y
x is y               # x is the same as y
x is not y           # x is not the same as y
```
Although these operations are probably familiar to you, the Python symbols are different from the mathematical symbols for the same operations. A common error is to use a single equal sign (**`=`**) instead of a double equal sign (**`==`**). Remember that **`=`** is an assignment operator and **`==`** is a comparison operator. There is no such thing as **`=<`** or **`=>`**.


### 🔲 Logical operators

There are three logical operators: `and`, `or`, and `not`. The semantics (meaning) of these operators is similar to their meaning in English. For example,

`x > 0` and `x < 10`

is true only if `x` is greater than 0 and less than 10.


`n%2 == 0` or `n%3 == 0` is true if either of the conditions is true, that is, if the number is divisible by 2 or 3.

Finally, the `not` operator negates a boolean expression, so `not (x > y)` is true if `x > y` is false.
```Python
>>> x = 1
>>> y = 2
>>> x > y
False
>>> not (x > y)
True
```
Strictly speaking, the operands of the logical operators should be boolean expressions, but Python is not very strict. Any nonzero number is interpreted as “true.”

```Python
>>> 17 and True
True
```
This flexibility can be useful in some situations, but there are some subtleties to it that might be confusing. You might want to avoid it until you are sure you know what you are doing.

### 🔲 Conditional execution

In order to write useful programs, we almost always need the ability to check conditions and change the behavior of the program accordingly. Conditional statements give us this ability. The simplest form is the `if` statement:
```Python
if x > 0 :
    print('x is positive')
```
The boolean expression after the `if` statement is called the condition. We end the `if` statement with a colon character (:) and the line(s) after the if statement are indented.

<p align="center">
<img width="293" height="200" alt="image" src="https://github.com/user-attachments/assets/d4805d1f-c86f-4bd4-a36c-4e4112bd8bbc" />
  <br><b><ins><i>if</i> Logic</ins></b>
</p>



















