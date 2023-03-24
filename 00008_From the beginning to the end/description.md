As we've seen, `in` can tell us whether a string is included in another. There are two special cases of this operation: when one string starts or ends with another.

The syntax of these operations is _a little_ :ok_hand: different from what we have seen up to now: you have to prefix them with `str.`. For example, the operation that returns whether one string starts with another is `str.startswith`, while the one that tells us if it ends with another is `str.endswith`. :eyes:

> Try these operations in the console by typing the following expressions:
>
>``` python
ムstr.startswith("Foundation and empire", "Foundation")
```
>
>``` python
ムstr.endswith("Foundation and empire", "empire")
```
>
>``` python
ムstr.endswith("Foundation and empire", "Foundation")
```
