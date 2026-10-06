# class_exercise

## Python and Jupyter setup

From the project directory, create and activate the virtual environment in PowerShell:

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Use the activated environment to run Python scripts with `python script.py` or start Jupyter with `jupyter notebook`. In VS Code, select `.venv` as the Python interpreter and the `Python 3 (ipykernel)` kernel for notebooks.
