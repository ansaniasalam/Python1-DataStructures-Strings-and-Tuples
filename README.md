# Data Structures - Strings and Tuples

This Jupyter notebook contains hands-on Python exercises with strings and tuples. It demonstrates how to combine and work with text, and how to create, combine, repeat, and access tuple elements.

## Concepts Used

### User Input
`input()` reads text from the user at runtime and always returns a string.

### String Concatenation
The `+` operator joins strings into a new one. Strings are immutable, so the original strings are never modified.

### Indexing
Each character has a position. Positive indexes start at `0` from the left, and negative indexes start at `-1` from the right.

### Slicing
`string[start:stop:step]` extracts a portion of a string. The stop index is excluded, and a step of `-1` reverses the string.

### find() Method
Returns the starting index of a substring (or `-1` if not found). It is used with slicing to extract a word dynamically.

### Case Methods
`upper()`, `lower()` and `capitalize()` change the case of a string.

### Method Chaining
Applying one method to the result of another, e.g. `lower().capitalize()`.

### count() Method
Counts occurrences of a character or substring (case-sensitive).

### replace() Method
Returns a new string with all occurrences of a substring replaced.

### Tuples
Ordered, immutable collections created with `()`. Their elements cannot be changed after creation.

### Tuple Concatenation
`+` combines two tuples into a new one.

### Tuple Repetition
`*` repeats a tuple's elements a given number of times.

### Tuple Indexing & Slicing
Works the same way as with strings, e.g. `t[2]`, `t[:3]`, `t[-3:]`.

### print() Function
Displays labelled output for readability.

## Running the Code

Open the notebook in Jupyter Notebook or JupyterLab and run the cells in order.

To run it from a terminal instead, execute the notebook with:

```bash
jupyter nbconvert --to notebook --execute "Python1.Data_Structures-Strings&Tuples.ipynb"
```
