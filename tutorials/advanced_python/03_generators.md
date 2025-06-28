# Generators

Generators are a simple way of creating iterators.

**Example:**

```python
# A generator function that yields the square of numbers from 0 to 4
def square_generator(n):
    for i in range(n):
        yield i**2

# Create a generator object
squares = square_generator(5)

# Iterate over the generator
for square in squares:
    print(square)

# Output:
# 0
# 1
# 4
# 9
# 16
```
