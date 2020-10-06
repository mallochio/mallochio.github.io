---
layout: post
title: Python - The stranger things
comments: true
---

*Edit: This is going to be a live post, updated whenever I run into / remember things I find strange about the python programming language.*

---

Although I consider myself an expert at the python programming language, I wasn't one of those people who started writing code while still in the crib. In fact, I started programming while in university. I was taught the C programming language to start. Thinking back, the best analogy I can come up with is one about 'being thrown in the deep end of the pool'. 

Learning Python changed all that. I taught myself Python after I graduated college. Python was a revelation. Coding programs became a breeze, there is a distinct lack of boilerplate code, with the finished product reading like pseudocode. Easy to debug, with a rich suite of libraries that make you feel like you have superpowers. Nowadays I automate large parts of my life by writing neat little scripts. I scrape webpages with [urllib](https://docs.python.org/3.7/library/urllib.html#module-urllib) and [requests](https://requests.readthedocs.io/en/master/), rename and rearrange files with [shutil](https://docs.python.org/3/library/shutil.html) and [os](https://docs.python.org/3/library/os.html?highlight=os#module-os).

Now, after many years of programming, I find some things strange with the language. What follows is a list of those *stranger things*.


&nbsp;

### 1. <ins>The Strange Case of the Hanging Comma</ins>

Here's how you define a tuple in python, by wrapping stuff in round brackets () . Let's call the tuple `t`


```python
>>> t = (1,2,3)
>>> print(f"t = {t}; Type of t = {type(t)}") 

# t = 1; Type of t = <class 'int'>
```

Let's put a single number inside the brackets to make a tuple


```python
>>> t = (1)
>>> print(f"t = {t}; Type of t = {type(t)}") 

# t = 1; Type of t = <class 'int'>
```

Huh.? Now `t` is an int, instead of a tuple.

Let's add a hanging comma after the single number


```python
>>> t = (1,)
>>> print(f"t = {t}; Type of t = {type(t)}") 

# t = 1; Type of t = <class 'tuple'>
```

So, adding a comma after the single number changes it back into a tuple. Strange.


---
Edit: For a more polished list of strange python, check [this](https://github.com/satwikkansal/wtfpython) out 
