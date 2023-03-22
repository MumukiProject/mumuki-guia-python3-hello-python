We have already learned about numbers and booleans in Python, but there is more!

Often we want to write programs that work with text :page_facing_up:: we want to know how many words are in a book, or convert lowercase letters to uppercase, or know whether a text is inside another one.

For these kinds of problems we have _strings_:

* `'Iron helps us play'`
* `"Hello Joe!"`
* `"I call the big one Bitey"`


As you can see, all strings are enclosed in single or double quotes. It doesn't matter if you use one or the other! But be consistent: if you opened a double quote, for example, you must also close a double quote. Furthermore, a string can consist of (almost) any character: letters, numbers, symbols, spaces, etc.

And what can we do with strings? For example, they can be compared, just like any other value...


```python
ム"hi" == "Hi"
False
ム"everyone" == "everyone"
True
```

…and also concatenated, that is, obtaining a string by the union of others. :chains:

> Try the following in the console:
>
>
> ```python
ム'Butter' + 'fly'
```
>
> ```python
ム"Hello, " + "how are you?" # notice the extra space after the comma
```
>
> ```python
ム"I need " + str(5)
```
>