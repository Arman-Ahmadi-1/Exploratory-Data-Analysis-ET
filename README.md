# Exploratory-Data-Analysis-ET

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Feature importance analysis** (Pearson correlation, mutual information, and machine learning) and **trend analysis** of evapotranspiration (ET) and its driving factors in California. This repo contains cleaned, reproducible code from:

> **Ahmadi et al., 2022** – *Meteorological driving forces of reference evapotranspiration and their trends in California.*  
> Science of The Total Environment.  
> [Paper Link](https://doi.org/10.1016/j.scitotenv.2022.157823)

---

## 🚀 Quickstart

Tested with **Python 3.13** (core stack).  

```bash
# 1) Create and activate a local environment
python -m venv .venv
# PowerShell (Windows):
.\.venv\Scripts\activate
# macOS/Linux:
# source .venv/bin/activate

# 2) Install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt

# 3) Run the notebook
# VS Code: open notebooks/ and run cells
# Jupyter: jupyter notebook notebooks/
```
Expected runtime: <1 minute with sample data.


## 📂 Repository Structure

```
exploratory-data-analysis-et/
│
├── data/
│   └── sample/              <- sample CSVs for quick demo (two CIMIS sites)
│
├── notebooks/
│   └── EDA_ET.ipynb         <- reproducible notebook
│
├── outputs/                 <- generated artifacts for the demo run
│
├── src/                     <- placeholder – future refactor of helper functions
├── docs/                    <- placeholder – project documentation
├── tests/                   <- placeholder – future unit tests
│
├── requirements.txt         <- dependencies
├── LICENSE
└── README.md
```

## 📊 What’s Inside
The sample notebook demonstrates:

- Loading & preprocessing CIMIS micro-meteorological data
- Initial data exploration and visualization
- Feature importance analysis (Pearson, mutual information, random forest)
- Trend analysis

> For full-scale experiments and exact figures in the paper, follow the methods and data sources described in the manuscript.

## 📁 Data
- This repo includes only two CIMIS sites in data/sample/ to ensure reproducibility.
- Full data must be obtained from their original sources ([CIMIS Website](https://cimis.water.ca.gov/)).
- Replace data/sample with the full dataset to reproduce paper-level results.

## ⚙️ Environment & Compatibility
- **Primary:** Python 3.13, core stack (numpy, pandas, scikit-learn, matplotlib, seaborn).

## 📖 Citation

If you use this repository or build upon the methods, please cite:

> Ahmadi, A., Daccache, A., Snyder, R.L., & Suvočarev, K. (2022). Meteorological driving forces of reference evapotranspiration and their trends in California. *Science of The Total Environment.*
https://doi.org/10.1016/j.scitotenv.2022.157823

**BibTeX**
```bibtex
@article{Ahmadi2022-Exploratory-Data-Analysis-ET,
  author  = {Ahmadi, Arman and Daccache, Andre and Snyder, Richard and Suvočarev, Kosana},
  title   = {Meteorological driving forces of reference evapotranspiration and their trends in California},
  journal = {Science of The Total Environment},
  year    = {2022},
  volume  = {849},
  pages   = {157823},
  doi     = {10.1016/j.scitotenv.2022.157823}
}
```

## 📜 License
Licensed under the [MIT License](LICENSE).

## ✉️ Contact
**Arman Ahmadi**  
📧 a.ahmadi@berkeley.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/arman-ahmadi/) · [Google Scholar](https://scholar.google.com/citations?user=oRpYGmIAAAAJ&hl=en&oi=ao)
