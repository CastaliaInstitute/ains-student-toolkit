# Python Basics

Python is a programming language. In these courses, you will often meet it inside a notebook, where short pieces of code (called **cells**) can be run one at a time.

## Your first notebook habits

- Read the text around a code cell before running it.
- Run cells from the top of the notebook in order. Later cells may use values created earlier.
- A cell’s output appears underneath it. Output may be text, a table, a number, or a chart.
- Change only the value the instructions identify. Then rerun the cell and compare the result.
- If a cell reports an error, read the last line first. It often names the problem.

## A few building blocks

```python
# A value can have a name so you can use it again.
score = 0.8

# Text is written inside quotation marks.
name = "sample model"

# A list holds several values in order.
results = [0.8, 0.6, 0.9]

# print displays a value below the cell.
print(name, score)
```

A **variable** is a name attached to a value. A **string** is text. A **list** holds multiple values. You do not need to memorize these definitions before beginning a guided lab; use this page as a reference while you work.

## Reading a simple comparison

```python
threshold = 0.7
score = 0.8
print(score >= threshold)
```

The expression asks whether `score` is greater than or equal to `threshold`. The result is `True` or `False`. Try changing `score` as an activity directs and explain what decision changes.

## Functions and imports

A **function** is a named set of steps that can be used again. Python libraries provide functions for common tasks.

```python
from math import sqrt
print(sqrt(9))
```

Here, `sqrt` is imported from Python’s `math` library and returns the square root of 9. In course notebooks, imports are often already prepared for you.

## Common errors

- **NameError:** a name has not been defined, or a cell that defines it was skipped. Run cells from the top.
- **SyntaxError:** Python could not read the code’s structure. Check quotes, parentheses, and colons.
- **ModuleNotFoundError:** a library is unavailable in the current environment. Follow the course setup instructions; do not install random packages.
- **Unexpected result:** check which cells ran and whether a previous value was changed.

See [Troubleshooting](troubleshooting.md) and the glossary entries for [cell](../glossary/README.md#cell), [variable](../glossary/README.md#variable), and [runtime](../glossary/README.md#runtime).
