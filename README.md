# Advanced-Debugger
Debug simple module for Python.

<img width="1440" height="700" alt="image" src="https://github.com/user-attachments/assets/90dbbd17-e817-4d55-a170-55f5e14d7a51" />

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
