# Summary: Python Basics

## 1. String Slicing and Strides
To extract specific parts of a string, use the format `string[start:stop:step]`.
* **Example:** `e[0::2]` prints every second character.
* **Reversing:** `e[::-1]` reverses the entire string.

## 2. Finding Substrings
You can find the position of a substring using two main methods:
* **`str.find()`**: Best for simple, exact text lookups. Returns `-1` if not found.
* **`re.search()`**: Best for complex patterns (Regular Expressions). Returns a Match object.

## 3. String Indexing
Python is a zero-indexed language, meaning counting starts at `0`.
* **Positive Indexing:** Counts from left to right (`0` to `len-1`).
* **Negative Indexing:** Counts backward from right to left (the last character is always `[-1]`).
