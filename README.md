# LIT Platform Releases

Pre-built wheels for the LIT Platform. Install via pip:

```bash
# Linux (Python 3.12)
pip install https://github.com/Positronic-AI/lit-releases/releases/download/v0.1.20/positronic_lit-0.1.20-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl

# macOS Apple Silicon (Python 3.12)
pip install https://github.com/Positronic-AI/lit-releases/releases/download/v0.1.20/positronic_lit-0.1.20-cp312-cp312-macosx_11_0_arm64.whl

# macOS Intel (Python 3.12)
pip install https://github.com/Positronic-AI/lit-releases/releases/download/v0.1.20/positronic_lit-0.1.20-cp312-cp312-macosx_10_13_x86_64.whl

# Windows (Python 3.12)
pip install https://github.com/Positronic-AI/lit-releases/releases/download/v0.1.20/positronic_lit-0.1.20-cp312-cp312-win_amd64.whl
```

Replace `cp312` with your Python version (`cp310`, `cp311`, `cp312`, `cp313`).

## Available Platforms

| Platform | Wheel suffix |
|----------|-------------|
| **Linux x86_64** | `manylinux_2_17_x86_64.manylinux2014_x86_64` |
| **macOS Apple Silicon** | `macosx_11_0_arm64` |
| **macOS Intel** | `macosx_10_9_x86_64` (3.10-3.11) / `macosx_10_13_x86_64` (3.12-3.13) |
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
