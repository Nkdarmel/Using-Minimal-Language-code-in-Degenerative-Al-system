# Using-Minimal-Language-code-in-Degenerative-Al-system

# Using Minimal Language Code in Degenerative AI Systems

A minimal Python module project for exploring lightweight language-code experiments in degenerative AI system workflows.

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
from my_module import add, greet, total

print(add(2, 3))
print(greet("World"))
print(total([1, 2, 3, 4]))
```

## Environment managers

The project includes lightweight environment manager utilities for creating Python environments used in experiments and evaluation pipelines.

```bash
python -m my_module env create demo-venv --type venv
python -m my_module env create demo-conda --type conda --python 3.12
python -m my_module env list --type venv
```

These helpers are available in the package as `VirtualEnvManager`, `CondaEnvManager`, and `create_environment()`.

## Purpose

This project demonstrates a compact, reusable Python foundation for testing minimal-language patterns and system degradation scenarios in AI-oriented workflows while keeping deployment, environment management, and command-line tooling simple.
