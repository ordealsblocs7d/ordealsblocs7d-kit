# ordealsblocs7d-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m ordealsblocs7d_kit.cli --help
```

```python
from ordealsblocs7d_kit.core import Ordealsblocs7dTool

tool = Ordealsblocs7dTool()
print(tool)
```

## Layout

```
ordealsblocs7d_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 ordealsblocs7d
