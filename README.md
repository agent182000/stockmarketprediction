# stockmarketprediction
# From Point to Probabilistic: Mitigating Attention Collapse in Transformer-Based Stock Forecasting

This repository contains the codebase, research report, and presentation for a quantitative finance study predicting Nifty 50 volatility using a Temporal Fusion Transformer (TFT). 

## 📊 Project Highlights
* **Probabilistic Forecasting:** Transitioned from deterministic LSTM point-forecasting to an 80% confidence interval "Cone of Uncertainty" using a TFT architecture.
* **Curing Attention Collapse:** Mathematically diagnosed and mitigated network failure by enforcing stationarity via Logarithmic Return transformations, cutting the baseline error in half to a **0.94% Test MAPE**.
* **Global XAI Discoveries:** Utilized the Variable Selection Network to prove that macroeconomic systemic fear (**India VIX**) captures >60% of predictive importance, completely dethroning individual trading volume.
* **Live MLOps Deployment:** Engineered an automated paper-trading engine that executes probabilistic inference on live Yahoo Finance data to generate risk-adjusted trading signals.

## 📂 Repository Contents
*  The Google Colab implementation and live trading engine scripts.
*  The complete LaTeX source code and compiled Mid-Semester PDF report.
*  The slide deck used for the academic defense.
*  Core foundational papers on XAI, Transformers, and financial econometrics referenced in this study.

## 🚀 Reproducibility
The full Python implementation can be run directly via Google Colab:
[Link to your Colab Notebook]
