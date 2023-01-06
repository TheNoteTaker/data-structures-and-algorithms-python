# Section 2: ~~Classes and~~ Pointers

```python
num1 = 11
num2 = num2

# When you set `num2` to `num1`, it becomes a pointer pointing at the same value
# that `num1` is pointing at.
print(f"The ID of num1 is: {num1}")
print(f"The ID of num2 is: {num2}")

num2 = 22

# The ID is now different.
print(f"The ID of num2 is: {num2}")
```

- **Integers** are **Immutable**, and variables are bound to a place in memory.
  Shallow copies are created when doing like above.
- If there are no pointers pointing to a value, garbage collection will remove
  it.

