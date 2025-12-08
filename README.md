# Advanced-Debugger
Debug simple module for Python.

Welcome to the official GitHub page of module.

**DOCUMENTATION OF MODULE**

**Get Started**
Install module to your environment with using following PIP command:
```bash
pip install advdbg 
```
And import it to your Python code:
```python
from advdbg import AdvDEBUG
```

**Create new category**
Define new category debug.

Use syntax:
```python
debug = AdvDEBUG.define('title of your debug')
```
Debug category has created. Now, we can interact with it.

Arguments:
title (STRING) || REQUIRED: Title OR name of category
activated (BOOLEAN), DEFAULT True: Is activated a category
notify (BOOLEAN), DEFAULT False: Notificates when category disactivated and tryed to call OUTPUT function

**Configure existing category**
Configure properties of existing category.

Haves same args like `define`.

**Print**
Show debug text.

Arguments:
text (STRING) || REQUIRED: Text to shown.

**PYPI lastest version:**
https://pypi.org/project/advdbg/0.1.1
