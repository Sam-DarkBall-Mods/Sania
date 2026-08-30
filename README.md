# Sania

[![CI](https://github.com/Sam-DarkBall-Mods/Sania/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Sania/actions/workflows/ci.yml)

Sania adds portable Sania and Volnorez UAV jammers. They can be carried in
bags, placed on the ground, attached to an object, switched between operating
modes and packed again. A crate is included for mission makers.

## Requirements

- Arma 3 2.22 or newer
- CBA_A3

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The `sania` prefix and existing jammer class names remain unchanged.

## License

Code and configs use GPL-2.0-or-later. Original models, textures and materials
use APL-SA. See [LICENSES.md](LICENSES.md).
