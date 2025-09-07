# Option Pricing Beyond Black–Scholes: Empirical Evidence of Fat Tails

## 📖 Project Overview
This project explores the theoretical foundation of the Black–Scholes–Merton (BSM) model and critically evaluates its assumptions through empirical data analysis.  
Using long-term historical data from the S&P 500 (1927–2024), the study highlights the mismatch between the model’s assumptions (constant volatility, Gaussian returns, frictionless trading) and real-world financial dynamics.  

The empirical investigation shows clear evidence of **fat tails** in return distributions, suggesting that extreme events are much more frequent than predicted by the Gaussian framework.  
This motivates the need for richer stochastic models, such as **Lévy α-stable processes** or other fat-tailed approaches, in option pricing.

---

## 📂 Repository Structure
- **`beyond_bs_model.pdf`** → Main report (theory + empirical analysis).  
- **`SP500_R.pdf`** → Complementary analysis done in R (visualizations and statistical tests).  
- **`SP500_Data-Copy1.ipynb`** → Jupyter Notebook with Python code for data collection and empirical analysis.  

---

## 🔑 Key Features
- Derivation of the Black–Scholes PDE via stochastic calculus and hedging arguments.  
- Historical S&P 500 analysis (1927–2024).  
- Empirical tests for distributional assumptions:
  - Histogram & Black Monday case study.  
  - Zipf plots for tail behavior.  
  - QQ-plot against the exponential distribution.  
  - Mean Excess Function (MEF).  
  - Maximum-to-Sum (MS) plot for moment analysis.  
- Evidence that higher-order moments (3rd, 4th) may not exist → limitations of Gaussian inference.  
- Discussion of potential extensions: jump-diffusion models, stochastic volatility, and **fat-tailed distributions**.  

---
