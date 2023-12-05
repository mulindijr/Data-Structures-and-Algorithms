# Data Structures and Algorithms

## Useful Python Functions

### 1. is_balanced Function

#### Description

The `is_balanced` function checks whether an input expression containing parentheses, curly braces, and square brackets is balanced. It returns `True` if the brackets are balanced, and `False` otherwise.

#### Usage
```python
from stacks import is_balanced

# Test cases
expression1 = "([]{})"
expression2 = "([)]"
print(is_balanced(expression1))  # Output: True
print(is_balanced(expression2))  # Output: False
```

### 2. remove_duplicates Function

### Description
The `remove_duplicates` function takes a sequence (list or tuple) and returns a new sequence with duplicate elements removed while maintaining the original order.

#### Usage
```python
from lists import remove_duplicates

# Test case
input_sequence = [2, 3, 2, 4, 5, 3, 6, 7, 5]
result = remove_duplicates(input_sequence)
print(result)  # Output: [2, 3, 4, 5, 6, 7]
```

### 3. word_frequency Function

### Description
The `word_frequency` function generates a dictionary containing the frequency of each word in a sentence. Punctuation is ignored, and words are treated in a case-insensitive manner.

#### Usage
```python

from dictionary import word_frequency

# Test case
sentence = "This is a test sentence. This sentence is a test."
result = word_frequency(sentence)
print(result)
