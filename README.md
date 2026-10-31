# AI Programming Foundations Project

A complete, reproducible data workflow built in a single Jupyter notebook: the notebook loads the
Pima Indians Diabetes Database from CSV, cleans it with reusable functions that repair the
physiologically impossible zero values the file uses for missing measurements, explores it with
summary, grouping and correlation functions, and produces three labelled visualisations of how
glucose, BMI and the other variables relate to a diabetes diagnosis. No machine learning model is
trained. Dataset: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/kumargh/pimaindiansdiabetescsv)
(768 rows, 9 columns), included here as `diabetes.csv`.

## Requirements

Python 3.9 or higher.

## Install dependencies

```
pip install -r requirements.txt
```

## Run the notebook

```
jupyter notebook data_workflow.ipynb
```

Then run all cells from the top (Kernel > Restart Kernel and Run All Cells). JupyterLab or the VS Code
Jupyter extension work the same way. Keep `diabetes.csv` in the same folder as the notebook, since it
is loaded with a relative path. The three figures are written to `figures/` when the notebook runs.

## Files

- `data_workflow.ipynb` - the workflow: ingestion, cleaning, exploratory analysis, visualisations, summary
- `diabetes.csv` - the dataset
- `figures/` - the three figures exported as PNG
- `module_summary.pdf` - the written report
- `requirements.txt` - pinned dependencies
