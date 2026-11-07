# Eastern Freight Logistics — Root-Cause Analysis

This is the starter folder structure for the fictional logistics analytics internship project.

## Folder guide

- `data/raw/` — original synthetic CSV files (shipments, routes, vehicles, warehouse scans, hub mapping).
- `data/cleaned/` — cleaned and analysis-ready datasets.
- `notebooks/` — Jupyter/Google Colab notebooks.
- `outputs/charts/` — exported charts and plots.
- `outputs/driver_tree/` — driver-tree diagrams and supporting calculations.
- `outputs/hypothesis_log/` — hypothesis test results and evidence.
- `reports/` — management memo and final report.

## Getting started in Google Colab

1. Extract this ZIP on your computer.
2. Upload the extracted `Eastern_Freight_Project` folder to Google Drive, or upload the ZIP to Drive and extract it there.
3. Open Google Colab and open/create your notebook inside `notebooks/`.
4. When using Colab, mount Google Drive and set the project path to the extracted folder.

Example:

```python
from google.colab import drive
drive.mount('/content/drive')

PROJECT_DIR = '/content/drive/MyDrive/Eastern_Freight_Project'
```

Adjust the path if you placed the folder somewhere else in Drive.

## Getting started in VS Code

1. Extract the ZIP.
2. Open VS Code.
3. Select **File → Open Folder**.
4. Choose the extracted `Eastern_Freight_Project` folder.
5. Open a terminal in VS Code and install Python/Jupyter support if needed.

## Important

The company and all planned data are fictional. No source datasets are included yet. We will generate clearly labeled synthetic data in a later project step. Do not present synthetic findings as real company results.
