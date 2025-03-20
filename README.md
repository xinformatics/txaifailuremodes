# TXAI Failure Modes Analysis

This repository contains notebooks and resources for analyzing failure modes of time-series explainability methods for critical care applications.

---

## **Directory Structure**

```text
.
├── 00_Causal_Crossformer.ipynb # Notebook implementing the causal crossformer model.
├── 01_Circ_hirid_xai.ipynb     # Notebook implementing time-series interpretation methods from captum and time_interpret libraries.
├── 02_DynaMask.ipynb           # Notebook using the DynaMask explainability technique
├── 03_ExtremalMask.ipynb       # Notebook using the ExtremalMask explainability technique
├── 04_Figure_Plotter.ipynb     # Notebook for generating plots and visualizations of results
├── data/                       # Folder containing one sample dataset
├── model/                      # Folder for storing trained models
├── scores/                     # Folder with interpretability attribution scores for each method
└── README.md                   # Project description and usage instructions

### Required packages are available in the requirements.txt file
