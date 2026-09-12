# Project

A project repository for UBC dsci-toolbox assignment 6. It demonstrates file naming conventions,
project organization, and reproducible computational environments using Conda.

## Repository structure

- `data/` contains the dataset used in analysis
- `docs/` contains reports, supporting documents, and weekly meeting minutes
- `images/` contains the dataset visualization and prediction plots
- `reports/` contains the analysis notebook
- `src/` contains the Python scripts, numbered in the order they are run

## Scripts

The scripts in `src/` are run in sequence:

1. `01_generate-data.py` generates the dataset
2. `02_visualize-data.py` plots the dataset
3. `03_plot-predictions.py` plots the predictions

## Environment

The computational environment is defined in `environment.yaml`. To recreate it:

```
conda env create -f environment.yaml
conda activate project-env
```

## License

This project is licensed under the MIT License. See `LICENSE` for details.
