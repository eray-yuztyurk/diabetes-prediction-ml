<h1 align="center">Diabetes Prediction — End-to-End Machine Learning Pipeline</h1>  

This project demonstrates an end-to-end machine learning workflow for predicting diabetes outcomes using a clean, reproducible and well-documented Jupyter notebook. It walks through data understanding, preprocessing, exploratory analysis, feature engineering, model training and evaluation — all in a single notebook so you can follow the full pipeline step by step.

<table align="center">
  <tr>
    <!-- LEFT: TABLE OF CONTENTS -->
    <td align="left" width="60%" style="vertical-align: top;">
      <h3>📑 Table of Contents</h3>
      <ul>
        <li><a href="#project-overview">Project overview</a></li>
        <li><a href="#files-in-this-repo">Files in this repo</a></li>
        <li><a href="#technologies--libraries">Technologies & libraries</a></li>
        <li><a href="#quick-start">Quick start</a></li>
        <li><a href="#environment--installation">Environment & installation</a></li>
        <li><a href="#running-the-notebook">Running the notebook</a></li>
        <li><a href="#data-sources">Data sources</a></li>
        <li><a href="#machine-learning-summary">Machine learning summary</a></li>
        <li><a href="#results-and-evaluation">Results and evaluation</a></li>
        <li><a href="#reproducibility-notes">Reproducibility notes</a></li>
      </ul>
    </td>
    <!-- RIGHT: IMAGE -->
    <td align="center" width="40%">
      <img width="600" alt="diabetes-prediction"
           src="https://github.com/user-attachments/assets/e6b5d022-ba25-47d6-91fd-4491139908fb" />
    </td>
  </tr>
</table>

---

## Project overview

This notebook provides a practical demonstration of a diabetes prediction pipeline. The workflow includes:

- Loading and exploring the dataset  
- Cleaning and simple feature engineering  
- Statistical and visual exploratory data analysis (EDA)  
- Training multiple baseline models and comparing performance  
- Evaluating models using standard metrics and visualizations

The notebook is fully self-contained and ideal for learning, demonstrations, or quick prototyping.

---

## Files in this repo

- **`diabetes-project.ipynb`** — The complete end-to-end workflow (notebook with code, outputs and explanations).  
- **`README.md`** — This documentation.

This repository is intentionally notebook-first: no extra scripts or external data files are included.

---

## Technologies & libraries

- Python **3.8+**  
- Jupyter / JupyterLab  
- pandas, numpy  
- matplotlib, seaborn (optional: plotly)  
- scikit-learn (models, preprocessing, metrics)

Package versions are shown inside the notebook. For reproducible runs, pin them into a `requirements.txt` or `environment.yml`.

---

## Quick start

1. Clone the repository
```bash
git clone https://github.com/eray-yuztyurk/diabetes-prediction-ml.git
cd diabetes-prediction-ml
```

2. Create and activate a virtual environment

- macOS / Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

- Windows (PowerShell)
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

3. Install dependencies
```bash
pip install jupyterlab pandas numpy scikit-learn matplotlib seaborn
```

---

## Environment & installation

- Recommended Python version: **3.8** or newer.  
- Use a virtual environment to isolate dependencies.  
- For fully reproducible runs, consider creating a pinned `requirements.txt` (I can generate one from the notebook on request) or an `environment.yml` for Conda users.

---

## Running the notebook

Start Jupyter:

```bash
jupyter lab
# or
jupyter notebook
```

Open `diabetes-project.ipynb` and run the cells in order. The notebook is structured sequentially — running from top to bottom reproduces the full workflow.

Tips:
- Restart kernel → Run All for a clean, deterministic run.
- If the dataset is downloaded at runtime, ensure an active internet connection.

---

## Data sources

The notebook documents how the dataset is loaded. Common sources for diabetes prediction tutorials include the Pima Indians Diabetes dataset (UCI / Kaggle). Check the first cells of the notebook for the exact data source and loading code.

---

## Machine learning summary

The notebook covers:

- Data preprocessing (missing values, imputation, scaling)  
- Basic feature engineering where applicable  
- Baseline model training (e.g., Logistic Regression, Decision Tree, Random Forest)  
- Train/test evaluation and cross-validation where used  
- Metrics: accuracy, precision, recall, F1 score, and confusion matrices

All model details, hyperparameters and evaluation outputs are available in the notebook’s "Modeling" section.

---

## Results and evaluation

All plots, metric tables and discussions are embedded in the notebook. Typical outputs include:

- Model comparison table (scores for each algorithm)  
- Confusion matrix visualizations  
- Discussion of model strengths, weaknesses and next steps

Check the final evaluation cells for a concise performance summary.

---

## Reproducibility notes

For reliable, repeatable runs:

- Execute notebook cells sequentially.  
- Pin package versions (create `requirements.txt`).  
- Set random seeds in model training (the notebook includes seeds where applicable).  
- Save trained models and intermediate datasets to an `artifacts/` or `models/` folder if you plan to reuse them.

---
