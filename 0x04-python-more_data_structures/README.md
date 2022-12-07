# 0x04. Python - More Data Structures: Set, Dictionary
## About
An introductory project on:
- Sets and how to use them
- The most common set methods and how to use them
- How to iterate through a ser
- When to use sets versus lists versus dictionaries
- Dictionary and how to use them
- What is a key in a dictionary
- How to iterate through a dictionary
- What is a lambda function
- What are map and reduce
## Requirements
- Python 3.4
- pep8 1.7
## File Descriptions
### Mandatory
**[0-square_matrix_simple.py](0-square_matrix_simple.py)** - Write a function that computes the square value of all integers of a matrix.
- Prototype: `def square_matrix_simple(matrix=[]):`
- `matrix` is a 2 dimensional array
- Returns a new matrix:
  - Same size as `matrix`
  - Each value should be the square of the value of the input
- Initial matrix should not be modified
- You are not allowed to import any module
- You are allow to use regular loops, `map`, etc.

**[1-search_replace.py](1-search_replace.py)** - Write a function that replaces all occurrences of an element by another in a new list.
- Prototype: `def search_replace(my_list, search, replace):`
- `my_list` is the initial list
- `search` is the element to replace in the list
- `replace` is the new element
- You are not allowed to import any module

**[2-uniq_add.py](2-uniq_add.py)** - Write a function that makes the addition of all unique integers in a list (only one time each integer).
- Prototype: `def uniq_add(my_list=[]):`
- You are not allowed to import any module

**[3-common_elements.py](3-common_elements.py)** - Write a function that returns a set of common elements in two sets.
- Prototype: `def common_elements(set_1, set_2):`
- You are not allowed to import any module

**[4-only_diff_elements.py](4-only_diff_elements.py)** - Write a function that returns a set of all elements present in only one set.
- Prototype: `def only_diff_elements(set_1, set_2):`
- You are not allowed to import any module

**[5-number_keys.py](5-number_keys.py)** - Write a function that returns the number of keys in a dictionary.
- `Prototype: def number_keys(a_dictionary):`
- You are not allowed to import any module

**[6-print_sorted_dictionary.py](6-print_sorted_dictionary.py)** - Write a function that prints a dictionary by ordered keys.
- Prototype: `def print_sorted_dictionary(a_dictionary):`
- You can assume that all keys are string
- Keys should be sorted by alphabetic order
- Only sort keys of the first level (don’t sort keys of a dictionary inside the main dictionary)
- Dictionary values can have any type
- You are not allowed to import any module

**[7-update_dictionary.py](7-update_dictionary.py)** - Write a function that replaces or adds key/value in a dictionary.
- Prototype: `def update_dictionary(a_dictionary, key, value):`
- `key` argument will be always a string
- `value` argument will be any type
- If a key exists in the dictionary, the value will be replaced
- If a key doesn’t exist in the dictionary, it will be created
- You are not allowed to import any module

**[8-simple_delete.py](8-simple_delete.py)** - Write a function that deletes a key in a dictionary.
- Prototype: `def simple_delete(a_dictionary, key=""):`
- `key` argument will be always a string
- If a key doesn’t exist, the dictionary won’t change
- You are not allowed to import any module

**[9-multiply_by_2.py](9-multiply_by_2.py)** - Write a function that returns a new dictionary with all values multiplied by 2
- Prototype: `def multiply_by_2(a_dictionary):`
- You can assume that all values are only integers
- Returns a new dictionary
- You are not allowed to import any module

**[10-best_score.py](10-best_score.py)** - Write a function that returns a key with the biggest integer value.
- Prototype: `def best_score(a_dictionary):`
- You can assume that all values are only integers
- If no score found, return `None`
- You can assume all students have a different score
- You are not allowed to import any module

**[11-mutiply_list_map.py](11-mutiply_list_map.py)** - Write a function that returns a list with all values multiplied by a number without using any loops.
- Prototype: `def mutiply_list_map(my_list=[], number=0):`
- Returns a new list:
  - Same length as `my_list`
  - Each value should be multiplied by `number`
- Initial list should not be modified
- You are not allowed to import any module
- You have to use `map`
- Your file should be max 3 lines
### Advanced
**[100-weight_average.py](100-weight_average.py)** - Write a function that returns the weighted average of all integers tuple `(<score>, <weight>)`
- Prototype: `def weight_average(my_list=[]):`
- Returns 0 if the list is empty
- You are not allowed to import any module

**[101-square_matrix_map.py](101-square_matrix_map.py)** - Write a function that computes the square value of all integers of a matrix using `map`
- Prototype: `def square_matrix_map(matrix=[]):`
- `matrix` is a 2 dimensional array
- Returns a new matrix:
  - Same size as `matrix`
  - Each value should be the square of the value of the input
- Initial matrix should not be modified
- You are not allowed to import any module
- You have to use `map`
- You are not allowed to use `for` or `while`
- Your file should be max 3 lines

**[102-complex_delete.py](102-complex_delete.py)** - Write a function that deletes keys with a specific value in a dictionary.
- Prototype: `def complex_delete(a_dictionary, value):`
- If the value doesn’t exist, the dictionary won’t change
- All keys having the searched value have to be deleted
- You are not allowed to import any module
