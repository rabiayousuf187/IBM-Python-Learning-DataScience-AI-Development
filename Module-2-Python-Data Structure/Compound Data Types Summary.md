
# Compound Data Types
A compound data type groups multiple individual items or values together into a single container variable structure.

### Core Containers Summary

| Data Type | Syntax | Ordered | Changeable (Mutable) | Duplicate Values | Best Configuration Use |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **List** | `[item1, item2]` | Yes | **Yes** | Allowed | Track general items that shift over time. |
| **Tuple** | `(item1, item2)` | Yes | **No** | Allowed | Lock structural, read-only data values. |
| **Dictionary**| `{"key": value}` | Yes* | **Yes** | Keys must be unique | Fast object lookups using named labels. |
| **Set** | `{item1, item2}` | No | **Yes** | **Not Allowed** | Deduplicate collections and run math sets. |

*\*Note: Dictionaries maintain insertion order starting in Python 3.7+.*

### Basic Structural Code Snippets

* ##  Lists (Modifiable collection)
shopping_cart = ["apple", "banana"]
shopping_cart[0] = "orange" 

* ##  Tuples (Protected fixed collection)
gps_coordinates = (40.7128, -74.0060)
### Note: Single item tuples require a trailing comma: single_item = ("data",)

* ##  Dictionaries (Labeled lookup collection)
user_profile = {"username": "coder123", "age": 25}
print(user_profile["username"])

* ## Sets (Unique distinct collection)
unique_ids = {101, 102, 101} # Automatically parses out duplicates down to {101, 102}

