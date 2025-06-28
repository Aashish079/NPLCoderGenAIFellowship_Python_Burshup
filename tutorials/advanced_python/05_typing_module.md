# Typing Module

The `typing` module provides support for type hints.

**Example:**

```python
from typing import List

def get_names(names: List[str]) -> None:
    for name in names:
        print(name)

get_names(["Alice", "Bob", "Charlie"])
```
