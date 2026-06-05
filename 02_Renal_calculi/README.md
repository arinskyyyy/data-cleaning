# Renal Calculi Medical Dataset Cleaning Pipeline

**Objective:** Clean and preprocess a medical dataset on kidney stone 
(renal calculi) patients for ML-ready output.

**Domain:** Healthcare & Medicine  
**Tools:** Python, Pandas, NumPy, Jupyter Notebook  
**Associated with:** IIT Ropar Minor in Artificial Intelligence

## Problem Statement
Raw medical data contained missing values, duplicate patient records, 
inconsistent feature formats, and outliers that would corrupt 
any downstream ML model.

## What Was Done
- Removed duplicate patient entries
- Handled missing values via median/mode imputation
- Standardized medical feature naming conventions
- Merged herbal drug and phytochemical datasets
- Removed irrelevant identifier columns
- Produced a clean, ML-ready CSV output

## Files
- `cleaning_pipeline.ipynb` — Main cleaning notebook
- `cleaned_merged_renal_calculi.csv` — Final cleaned output
- `herbal_drugs.csv` — Source dataset 1
- `phytochemicals.csv` — Source dataset 2

## Result
Fully cleaned dataset ready for classification or regression modeling.