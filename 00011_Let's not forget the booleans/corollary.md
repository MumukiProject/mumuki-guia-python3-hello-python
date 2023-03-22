Did you spot the pattern? :grimacing:

For `and` to return `True`, both conditions must be true. That's why...

``` python
ム8 < 10 and 8 > 9
```

... returns `False`, because 8 is less than 10 but not greater than 9. Put another way, `8 < 10` is `True` but `8 > 9` is `False` 👎. Instead when trying...

``` python
ムstr.startswith("butterfly", "butter") and str.endswith("butterfly", "fly")
```

...we get `True`, since both conditions are true 👍. In summary:

```python
ムFalse and False
False
ムTrue and False
False
ムFalse and True
False
ムTrue and True
True
```
