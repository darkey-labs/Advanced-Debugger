# Advanced-Debugger
Debug simple module for Python.

<img width="1440" height="700" alt="image" src="https://github.com/user-attachments/assets/17e37940-10cf-47bd-8406-d9364a14b6d4" />


Welcome to the official GitHub page of module.

**DOCUMENTATION OF MODULE**

<img width="1492" height="790" alt="image" src="https://github.com/user-attachments/assets/042beddc-0e1d-43f0-81d9-03a1d3441e51" />
**Get started**

Install module if not maked it yet:
```bash
pip install advdbg
```
And optional you can check did you have module:
```bash
pip show advdbg
```
(Should return data of ADVDBG module).

Import module to code:
```python
from advdbg import AdvDBG
```

**Create new category**
Define new category debug.

Use syntax:
```python
debug = AdvDEBUG.define('title of your debug')
```
Debug category has created. Now, we can interact with it.

<img width="1440" height="450" alt="image" src="https://github.com/user-attachments/assets/db753c66-8678-4af2-b324-6e9d64bcf3da" />


**Configure existing category**
Configure properties of existing category.

Haves same args like `define`.

**Print**
Show debug text.

To print, use:
```python
debug.type('text')
```

Available types:
`INFO`, `ERROR`, `WARN`

<img width="1440" height="450" alt="image" src="https://github.com/user-attachments/assets/3ff2aee0-6cc2-4c2c-94b8-6ad5accd99fd" />


**PYPI lastest version:**
https://pypi.org/project/advdbg/0.1.6
