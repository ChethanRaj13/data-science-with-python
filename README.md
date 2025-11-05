# Data Science with Python

This repository contains a set of Jupyter notebooks and example JSON datasets focused on data cleaning, exploratory data analysis, and simple suggestion / recommendation workflows. It is built to help you explore data science concepts using Python, experiment with preprocessing and heuristics, and serve as a foundation for more advanced analyses or models.

---

## Contents

- `cleaning_data.ipynb` — Notebook demonstrating how to load raw JSON data, handle missing values, clean/format data, and perform basic preprocessing.  
- `pagessug.ipynb` — Notebook exploring suggestion logic at the “page/item” level, e.g., recommending pages or items based on similarity, counts or other heuristic methods.  
- `peoplesug.ipynb` — Notebook focused on “people” suggestion: a friend/match style recommendation workflow using available JSON data.  
- `miniproject.ipynb` — A mini-project notebook that combines cleaned data with one or more workflows to showcase an end-to-end data-science cycle (load → clean → explore → suggest).  
- JSON datasets (e.g., `cleaned_data.json`, `data2.json`, `massive.json`, `people.json`) — Example data files used by the notebooks; serve both as raw and intermediate data for cleaning and analysis.

---

## Why this repository

The goal of this project is to provide:

- A hands-on sandbox where you can practice data-science fundamentals: cleaning, handling JSON data, EDA and suggestion heuristics.  
- A foundation you can build on: once you're comfortable with the notebooks, you can enhance them by adding feature engineering, machine learning models, or more advanced recommendation algorithms.  
- A self-contained learning resource: the notebooks and datasets live together, so you can clone the repo and start exploring without needing large external dependencies.

---

## Getting started

1. Clone the repository:  
   ```bash
   git clone https://github.com/ChethanRaj13/data-science-with-python.git
   cd data-science-with-python
   ```
2. (Optional but recommended) Create and activate a virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate        # on Linux/macOS
.venv\Scripts\activate           # on Windows PowerShell
```
3. Launch Jupyter Notebook or JupyterLab and open one of the .ipynb files:
```bash
jupyter lab
```
