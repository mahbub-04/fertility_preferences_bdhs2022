# Fertility-limiting preferences among currently married women in Bangladesh

Code for the paper "Predictors of fertility-limiting preferences among currently married women in Bangladesh: an interpretable machine learning analysis of the 2022 Demographic and Health Survey".

## Data

The 2022 Bangladesh Demographic and Health Survey (BDHS) individual recode file (BDIR81SV, SPSS format) is available on request from the DHS Program (https://dhsprogram.com/data/). The data are not included in this repository.

Place `BDIR81FL.SAV` in `../data/BDIR81SV/` relative to this repository, and create an empty `output/` folder in the repository.

## Notebooks

Run in order:

1. `notebooks/01_data_preparation.ipynb`: sample selection, variable coding and bivariate analysis
2. `notebooks/02_machine_learning.ipynb`: model training, evaluation, sensitivity analyses and SHAP

Python 3.13.6; package versions are listed in `requirements.txt`.
