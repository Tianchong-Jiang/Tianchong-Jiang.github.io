---
title: Python Cheat Sheet
date: 2022-11-22 22:29:00 -500
categories: [python]
tags: [python]     # TAG names should always be lowercase
---

# Array/List/Tensor operations

```python
list = [item for item in list if condition]
```

### Appending variables to a empty tensor

```python
try:
    elements = torch.cat((elements, element[None,:]), 0)
except:
    elements = element[None,...]
```