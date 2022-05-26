# pre-commit-pyproject

Do `pre-commit` read `pyproject.toml`?
- `isort`: yes;
- `black`: option `extend-exclude` does not work, see [this issue](https://github.com/psf/black/issues/1985) but `force-exclude` does;