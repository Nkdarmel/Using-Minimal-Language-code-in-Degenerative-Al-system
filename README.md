# Using-Minimal-Language-code-in-Degenerative-Al-system

# my-module

A minimal Python module project template.

## Quick start

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .[dev]
python -m pytest
```

## Example

```python
from my_module import add, greet

print(add(2, 3))
print(greet("World"))
```

## Environment managers

The project includes lightweight environment manager utilities for creating Python environments.

```bash
python -m my_module env create demo-venv --type venv
python -m my_module env create demo-conda --type conda --python 3.12
python -m my_module env list --type venv
```

These helpers are available in the package as `VirtualEnvManager`, `CondaEnvManager`, and `create_environment()`.
