# LIT Platform Releases

Pre-built wheels for the LIT Platform. Install via pip:

```bash
# Linux (Python 3.12)
pip install https://github.com/Positronic-AI/lit-releases/releases/download/v0.1.20/positronic_lit-0.1.20-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl

# Windows (Python 3.12)
pip install https://github.com/Positronic-AI/lit-releases/releases/download/v0.1.20/positronic_lit-0.1.20-cp312-cp312-win_amd64.whl
```

Replace `cp312` with your Python version (`cp310`, `cp311`, `cp312`, `cp313`).

## Available Platforms

| Platform | Wheel suffix |
|----------|-------------|
| **Linux x86_64** | `manylinux_2_17_x86_64.manylinux2014_x86_64` |
| **Windows AMD64** | `win_amd64` |

## Python Versions

Python 3.10, 3.11, 3.12, and 3.13.

## Quick Start

```bash
pip install <wheel-url>
lit serve           # Linux/macOS
python -m lit serve # Windows (if Scripts not in PATH)
```

Open [http://localhost:8080](http://localhost:8080) and follow the setup wizard.

## All Releases

See the [Releases](https://github.com/Positronic-AI/lit-releases/releases) page for all versions.
