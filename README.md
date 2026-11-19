# nullhutches-5k-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m nullhutches_5k_kit.cli --help
```

```python
from nullhutches_5k_kit.core import Nullhutches5kTool

tool = Nullhutches5kTool()
print(tool)
```

## Layout

```
nullhutches_5k_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 nullhutches-5k
