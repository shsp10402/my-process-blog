---
title: "Python Hex String"
date: 2026-05-08T11:21:07+08:00
draft: false
math: true
---

### Problem
I see 
```python
if user_input == "\x65"*1751:
```
and I don't know what's the condition.

### Solution
I write some simple program to figure out the meaning

>>> print("\x65")
e
>>> print("\x65" * 10) # 隨便乘個小數字測試
eeeeeeeeee

### Conclusion
```python
"\x65"*1751
```
means a "\x65" is a string "e", and *1751 means repeat it 1751 times.