As we have just seen, in Python there are numbers, boolean values and strings:

| Data type | It represents	| Example           | Operations	                               |
|-----------|---------------|-------------------|--------------------------------------------|
|Numbers	  | amounts	      | `4947`            | `+`, `-`, `*`, `/`, `<`, etc.              |
|Booleans  	| truth values	| `True`            | `and`, `or`, etc.                          |
|Strings    | text	        | `"hello Python!"` | `str.upper`, `str.startswith`, `len`, etc. |


In addition, there are operations that work for all _data types_, for example:

* `==`: tells us if two values are equal;
* `!=`: tells us if two values are different.

**It's important to use the right operations with the right data types**, e.g. it doesn't make sense to add two boolean values or do boolean operations with numbers. **If you use operations that don't match, very strange and bad things can happen**. :confused:

> Try the following in the console:
>
>``` python
ム5 + 6
```
>
>``` python
ム5 == "5"
```
>
>``` python
ム8 > 6
```
>
>``` python
ムFalse / True
```
>
>``` python
ム'hello' or 'bye'
```
> Do all these operations make sense?
