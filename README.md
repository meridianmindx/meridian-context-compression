# Meridian Context Compression

[![PyPI version](https://img.shields.io/pypi/v/meridian-context-compression.svg)](https://pypi.org/project/meridian-context-compression/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://github.com/meridianmindx/meridian-context-compression/actions/workflows/build.yml/badge.svg)](https://github.com/meridianmindx/meridian-context-compression/actions/workflows/build.yml)

**LLM context compression utilities for AI agent pipelines.** Reduce token usage while preserving semantic meaning.

## Installation

```bash
pip install meridian-context-compression
```

## Quick Start

```python
from meridian_context_compression import compress

# Compress a long text
compressed = compress(text, ratio=0.5)
print(f"Reduced from {len(text)} to {len(compressed)} tokens")
```

## Features

- Lossless and lossy compression strategies
- Token optimization for OpenAI and Anthropic models
- Automatic summarization fallback for extreme compression
- Zero dependency Python package

## Package Metadata

- **PyPI**: `meridian-context-compression`
- **License**: MIT
- **Python**: >=3.8

## Development

```bash
pip install -e ".[dev]"
pytest
```

## License

MIT © Meridian
