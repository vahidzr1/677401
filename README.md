# US-Hybrid-DSGE-LSTM

Replication package for the paper  
"A Hybrid DSGE-LSTM Approach to Macroeconomic Forecasting with Financial Frictions"  
(under review – Empirical Economics)

## Contents
- data/ – raw and cleaned quarterly U.S. data (2000Q1–2024Q4) + sources  
- dynare/ – DSGE model (.mod) and estimation log  
- python/ – data cleaning script, LSTM training notebook, requirements  
- figures/ – Figure 1 (both panels) and Table 3  

## Quick start
```bash
pip install -r python/requirements.txt
python python/01_clean_data.py
# then open python/02_train_hybrid_model.ipynb


All results in the paper are reproduced.

## Permanent archive (Zenodo)
![DOI (https://zenodo.org/badge/DOI/10.5281/zenodo.17707792.svg)](https://doi.org/10.5281/zenodo.17707792)

## License
MIT License
