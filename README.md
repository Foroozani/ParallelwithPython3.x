# Parallel computing with Python 

[![](https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue)](https://www.python.org/)

Deep dive in to Python, My note:

### Dynamic typing vs Static typing

Some languages (Java, C++, Swift) are **statically** typed. Once the variable type is assigned you are not able to change it later. Python, in contrast, is **dynamically** typed.

```python
my_var = ‘hello’
```
The variable` my_var` is purely a reference to a string object with value "hello". No type is “attached” to `my_var`. 

```python
my_var = 10
```
The variable `my_var` is now pointing to an integer object with value 10. We can use the built-in `type()` function to determine the type of the object currently referenced by a variable. Instead, when we call `type(my_var)` Python looks up the object `my_var` is referencing (pointing to), and returns the type of the object at that memory location.

The term shared reference is the concept of two variables referencing the same object in memory (i.e. having the same memory address). 

![](https://github.com/Foroozani/ParallelwithPython3.x/blob/main/memory.png)

---
High-Performance Computing with Python 3.x

- Parallel programing with Python using multiprocessing and multithreading
- Optimizing Python Code using Cython
- Speeding up your python code using Numba
- Distributed programing using Dask 

