Did you find the differences? :nerd:

We said that `and` only returns `True` when both booleans are `True`. On the other hand, for `or` to be true it is sufficient that at least one of the booleans is true. Put another way, both conditions must be false for it to return `False`. For example in...

``` python
ムstr.upper("mumuki") == "Mumuki" or "love" in "romance"
```

... both `str.upper("mumuki") == "Mumuki"` and `"love" in "romance"` return `False`. If we test directly with the booleans we’ll see that:

```python
ムFalse or False
False
ムTrue or False
True
ムFalse or True
True
ムTrue or True
True
```
