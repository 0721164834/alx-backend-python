# Element Length Function

This Python project contains a type-annotated function `element_length` that takes an iterable of sequences and returns a list of tuples. Each tuple contains a sequence and its corresponding length.

## Features

- The function accepts a variety of sequence types such as strings, lists, and tuples.
- The return value is a list of tuples where:
  - The first element of each tuple is the sequence.
  - The second element is the length of the sequence.

## Usage

To use this function in your project:

1. Clone the repository to your local machine.
2. Ensure you have Python 3 installed.
3. Run the function with any iterable of sequences.

### Example

```python
from element_length import element_length

lst = ["hello", "world", [1, 2, 3], (4, 5)]
result = element_length(lst)
print(result)
# Output: [('hello', 5), ('world', 5), ([1, 2, 3], 3), ((4, 5), 2)]

