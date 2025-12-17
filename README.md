# nvdiffrast Pre-built Wheels (Full)

Pre-compiled CUDA wheels for [nvdiffrast](https://github.com/NVlabs/nvdiffrast) - NVIDIA's modular differentiable rasterizer for high-performance rendering.

## Installation

```bash
pip install nvdiffrast --find-links https://PozzettiAndrea.github.io/nvdiffrast-full-wheels/
```

## Supported Configurations

| CUDA | PyTorch | Python |
|------|---------|--------|
| 12.4 | 2.5.1 | 3.10, 3.11, 3.12 |
| 12.6 | 2.6.0 | 3.10, 3.11, 3.12, 3.13 |
| 12.6 | 2.8.0 | 3.10, 3.11, 3.12, 3.13 |
| 12.8 | 2.8.0 | 3.10, 3.11, 3.12, 3.13 |
| 12.8 | 2.9.1 | 3.10, 3.11, 3.12, 3.13 |

- **Platforms:** Linux (x86_64), Windows (amd64)
- **GPU:** RTX 20/30/40/50 series (SM 7.5+)

## Building

Wheels are automatically built via GitHub Actions on push to main. To trigger a manual build:

1. Go to Actions tab
2. Select the workflow for the CUDA version you want
3. Click "Run workflow"

## License

The wheel build scripts are MIT licensed. nvdiffrast retains its original license from [NVlabs/nvdiffrast](https://github.com/NVlabs/nvdiffrast).
