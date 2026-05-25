# Master Thesis

This repository contains the code and material for my thesis project.

## Install Packages

1. Create a virtual environment:

```powershell
python -m venv .venv
```

2. Activate the virtual environment:

Windows (PowerShell):

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source .venv/bin/activate
```

3. Install all required packages:

```bash
pip install -r requirements.txt
```

4. (Optional) Verify installation:

```bash
pip list
```

## Import Packages

After installing dependencies, you can import them in your Python files.

Example imports:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

If you want to import something specific from a package:

```python
from sklearn.model_selection import train_test_split
```

For your own project files, import from your module path, for example:

```python
from my_module import my_function
```