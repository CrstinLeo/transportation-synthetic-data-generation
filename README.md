# Transportation Synthetic Data Generation

Generative modeling experiments for transportation tabular data, including CTGAN-style workflows.

## Overview

from torch.utils.data import DataLoader from torchvision import datasets from torchvision.transforms import ToTensor from torch.utils.data import DataLoader from torchvision import datasets from torchvision.transforms import ToTensor

## Repository Structure

- `notebooks/`: cleaned Jupyter/Colab notebooks with descriptive filenames.
- `src/`: standalone Python scripts where available.
- `requirements.txt`: inferred Python dependencies.
- `SOURCE_MAP.md`: traceability back to original Google Drive files.

## Key Files

- `notebooks/transportation-ctgan.ipynb` from `Transportation CTGAN.ipynb`
- `notebooks/transportation-infromation-generate.ipynb` from `Transportation infromation generate.ipynb`

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Open notebooks with JupyterLab, VS Code, or Google Colab. Some notebooks expect external public datasets and may need path updates before execution.

## Data Notes

Large datasets, raw CSV exports, screenshots, PDFs, private download URLs, and assignment prompt files were intentionally excluded from this public-ready package.

## Suggested GitHub Repository

`transportation-synthetic-data-generation`

## Main Dependencies

- `matplotlib`
- `numpy`
- `pandas`
- `scikit-learn`
- `torch`
- `torchvision`
