---
title: dict_key_from_value
tags: dictionary,keys,values
---

- iterate through dictionary using dict.items()
- return where desired value matches value in dictionary

```py
def dict_key_from_value(d,val):
  for i,j in d.items():
    if j==val:
      return i
```

```py
d = {'one': 1, 'three': 3, 'five': 5, 'two': 2, 'four': 4}
dict_key_from_value(d,3) # three
```
