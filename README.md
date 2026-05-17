# active-probe

BoundaryProbe + ConsistencyProbe + CoverageProbe + TerrainMap — active sonar for constraint discovery

## Dependencies

servo-mind

## Usage

```python
from core.active_probe import ...
```

## Shell Loading

This tool can be loaded into any PLATO shell environment:

```python
# Neo loads this tool from the weapon rack
from plato_shell_bridge import PlatoShell
shell = PlatoShell("agent-shell")
shell.load_tool("active-probe")
```

## Tests

```bash
python3 -m pytest tests/test_active_probe.py -v
```

## License

MIT — Part of the Cocapn Fleet Intelligence System
