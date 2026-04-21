# 🔐 NVD CYBERSECURITY — CVSS SEVERITY PREDICTION

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=320&color=0:020B18,15:041424,30:1F4E79,50:00E5FF,75:7C4DFF,100:020B18&text=CVSS%20SEVERITY%20PREDICTION&fontSize=42&fontAlignY=38&fontColor=ffffff&animation=twinkling&desc=Supervised%20ML%20%26%20DL%20Regression%20%7C%20337%2C705%20NVD%20CVE%20Records%20%7C%20R%C2%B2%20%3D%200.9990&descAlignY=65&descSize=19"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=24&duration=2500&pause=700&color=00E5FF&center=true&vCenter=true&width=1200&lines=Predicting+CVSS+Base+Score+from+CVE+Metadata;337%2C705+Records+%7C+80%2F20+Full+Dataset+Split;6+Feature+Selection+Methods+%E2%80%94+13+Features+Validated;Extra+Trees+%E2%86%92+CV+R%C2%B2+%3D+0.9990+%C2%B10.0001+%E2%98%85+Best+Model;GRU+%E2%86%92+R%C2%B2+%3D+0.9979+%7C+MAE+%3D+0.047+%E2%98%85+Best+DL"/>
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:00E5FF,33:7C4DFF,66:FFB300,100:FF1744"/>
</p>

<br/>

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.10+-00E5FF?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Best ML Model](https://img.shields.io/badge/Best_ML-Extra_Trees_★-6A369B?style=for-the-badge&logo=apachespark&logoColor=white)](https://scikit-learn.org)
[![Best DL Model](https://img.shields.io/badge/Best_DL-GRU_★-C0392B?style=for-the-badge&logo=pytorch&logoColor=white)](https://scikit-learn.org)
[![CV R²](https://img.shields.io/badge/CV_R%C2%B2-0.9990_%C2%B10.0001-00E676?style=for-the-badge&logo=databricks&logoColor=black)](https://github.com/nishu2402/NVD-Cybersecurity-CVSS-Prediction)

[![Records](https://img.shields.io/badge/Records-337%2C705_CVEs-00E5FF?style=flat-square&logo=database&logoColor=black)](https://nvd.nist.gov)
[![Split](https://img.shields.io/badge/Split-80%25_Train_%2F_20%25_Test-2E75B6?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![CV](https://img.shields.io/badge/CV-5--Fold_CrossVal-00E676?style=flat-square&logo=python&logoColor=black)](https://scikit-learn.org)
[![FS Methods](https://img.shields.io/badge/FS_Methods-6_Multi--Paradigm-FFB300?style=flat-square&logo=apachespark&logoColor=black)](https://github.com/nishu2402/NVD-Cybersecurity-CVSS-Prediction)
[![License](https://img.shields.io/badge/License-MIT-FF1744?style=flat-square&logo=opensourceinitiative&logoColor=white)](LICENSE)

</div>

---

<a id="authors"></a>
## 👾 Author

### Nisarg Chasmawala · Alias: **HEAVEN**

<div align="center">

| | Detail |
|---|---|
| 🎓 **University** | Birmingham City University |
| 📚 **Module** | Applied Machine Learning — CMP7239 |
| 📝 **Assessment** | Presentation · Level 7 · Weighting: 30% |
| 🏅 **Level** | Level 7 (Postgraduate MSc) |
| 🆔 **Student ID** | 25155511 |
| 📅 **Academic Year** | 2025 – 2026 |
| 👨‍🏫 **Module Leader** | Dr Mohamed Ihmeida |
| 📍 **Location** | England, UK |
| 🔗 **LinkedIn** | [linkedin.com/in/nisarg-chasmawala](https://www.linkedin.com/in/nisarg-chasmawala) |
| 🐙 **GitHub** | [github.com/nishu2402](https://github.com/nishu2402) |
| 🎯 **Alias** | HEAVEN · Ethical hacking & offensive security research |

</div>

---

## 📋 Table of Contents

- [👾 Author](#authors)
- [🧠 Project Summary](#project-summary)
- [💡 Core Idea](#core-idea)
- [📦 Dataset](#dataset)
- [🔍 Feature Selection — 6 Methods](#feature-selection)
- [⚙️ Algorithms — 4 ML + 2 DL](#algorithms)
- [📊 Results & Metrics](#results)
- [📈 Visualisations — 23 Figures](#visualisations)
- [🚀 Quick Start](#quick-start)
- [📁 Repository Structure](#repo-structure)
- [📚 References](#references)

---

<a id="project-summary"></a>
## 🧠 Project Summary

This repository presents a **publication-level supervised regression pipeline** applied to the **National Vulnerability Database (NVD)** — the largest public catalogue of cybersecurity vulnerabilities maintained by NIST.

The objective is to **automatically predict CVSS Base Score** (a continuous 0.0–10.0 severity metric) from structured CVE metadata, eliminating the bottleneck of manual scoring that currently delays patch prioritisation by days for each of the 25,000+ CVEs disclosed annually.

### ✅ What This Project Does

| Stage | Detail |
|---|---|
| **EDA** | 6 exploratory figures across 337,705 records — distribution, severity, temporal, correlation |
| **Feature Selection** | 6 independent methods (filter + embedded + wrapper) converge on 13-feature optimal set |
| **ML Training** | 4 tree-based regression algorithms on full 270,164-record training set |
| **DL Training** | 2 recurrent architectures (LSTM, GRU) on full training set with early stopping |
| **Cross-Validation** | 5-Fold CV on 60k sub-sample confirms no overfitting |
| **Evaluation** | MAE, RMSE, R² on 67,541 held-out test records |
| **Visualisation** | 23 publication-quality figures covering EDA, FS, model performance, residuals |
| **Model Saving** | All 6 models + 2 scalers + metadata JSON persisted via joblib |

---

<a id="core-idea"></a>
## 💡 Core Idea

```
CVE Metadata  →  Feature Selection (6 methods)  →  ML/DL Regression  →  CVSS Score (0.0–10.0)
                                                                              ↓
                                                              Patch Priority Decision
```

**Why this matters:** A wrong CVSS score means the wrong patches get deployed first. An automated, reproducible scoring system reduces latency from days to milliseconds and eliminates analyst subjectivity.

**Task type:** Strictly **Regression** (CVSS Base Score is continuous — not classification).

**Prohibited algorithms:** Linear/Logistic Regression · SVM/SVR · Random Forest · XGBoost · MLP · 1-D CNN · DNN/ANN

---

<a id="dataset"></a>
## 📦 Dataset

**Source:** U.S. National Vulnerability Database — [nvd.nist.gov](https://nvd.nist.gov) (NIST, 2023)

| Property | Value |
|---|---|
| **File** | `NVD_Cybersecurity_Dataset.csv` |
| **Total Records** | 337,705 CVE entries |
| **Total Features** | 19 columns |
| **Selected Predictors** | 13 features (validated by 6 FS methods) |
| **Target Variable** | `CVSS_Base_Score` (float, 0.0–10.0) |
| **Temporal Coverage** | 1988 – 2026 (38 years) |
| **Missing Values** | None — 100% complete |
| **Training Set** | 270,164 records (80%) |
| **Test Set** | 67,541 records (20%) |
| **Random State** | 42 (fully reproducible) |

### 🔑 Selected Features (13)

```python
FEATURES = [
    'Exploitability_Score',       # CVSS sub-score — strong non-linear signal (MI=1.911)
    'Impact_Score',               # CVSS sub-score — dominant linear predictor (r=+0.797)
    'Word_Count',                 # Description word count — proxy for CVE complexity
    'Char_Length',                # Description character length
    'Publish_Year',               # Temporal — captures scoring methodology shifts
    'Publish_Month',              # Seasonal vulnerability disclosure patterns
    'Flag_XSS',                   # Binary: Cross-Site Scripting present
    'Flag_SQLi',                  # Binary: SQL Injection
    'Flag_Buffer_Overflow',       # Binary: Buffer Overflow
    'Flag_RCE',                   # Binary: Remote Code Execution (high severity)
    'Flag_Privilege_Escalation',  # Binary: Privilege Escalation
    'Flag_DoS',                   # Binary: Denial of Service
    'Flag_Directory_Traversal',   # Binary: Directory Traversal
]
TARGET = 'CVSS_Base_Score'
```

### 📊 CVSS Severity Distribution

| Severity | CVSS Range | Count | Percentage |
|---|---|---|---|
| **MEDIUM** | 4.0 – 6.9 | 148,626 | 44.0% |
| **HIGH** | 7.0 – 8.9 | 123,452 | 36.6% |
| **CRITICAL** | 9.0 – 10.0 | 29,743 | 8.8% |
| UNKNOWN | N/A | 22,007 | 6.5% |
| LOW | 0.1 – 3.9 | 13,849 | 4.1% |
| NONE | 0.0 | 28 | < 0.01% |

> 📌 MEDIUM + HIGH = **80.6%** of all records — significant class imbalance

---

<a id="feature-selection"></a>
## 🔍 Feature Selection — 6 Methods (Multi-Paradigm)

A **multi-paradigm feature selection strategy** was applied. A feature is retained if supported by at least 2 independent methods.

### Method Overview

| # | Method | Paradigm | Key Result |
|---|---|---|---|
| 01 | **Pearson Correlation** | Filter — Linear | Impact_Score r=+0.797 · Flag_XSS r=−0.129 |
| 02 | **Mutual Information** | Filter — Info-theoretic | Exploit.Score MI=1.911 bits > Impact_Score MI=1.835 |
| 03 | **F-Regression / ANOVA** | Filter — Statistical | Impact_Score F=588,435 (21× any other feature) |
| 04 | **Chi-Square Test** | Filter — Independence | All 13 features p < 0.001 |
| 05 | **Lasso (λ=0.0004)** | Embedded — L1 Reg. | 12/13 non-zero · Word_Count zeroed |
| 06 | **ElasticNet (α=0.0009)** | Embedded — L1+L2 Reg. | 12/13 non-zero · l1_ratio=0.50 |

> **Supplementary:** RFE (top-8) and PCA Scree (intrinsic dimensionality analysis)

### Key Finding

> 🔑 **Exploitability_Score** (MI=1.911 bits) outranks **Impact_Score** (MI=1.835 bits) under Mutual Information — **reversing the Pearson ranking**. This reveals strong non-linear associations invisible to linear correlation, directly justifying tree-based models over any linear approach.

### Consensus Table (Exact Values)

| Feature | Pearson | MI | F-stat | Lasso | ElasticNet | RFE | Verdict |
|---|---|---|---|---|---|---|---|
| Impact_Score | 0.797 | 1.835 | 588,435 | 9.224 | 9.109 | Sel | ✅ **RETAIN** |
| Exploit.Score | 0.276 | 1.911 | 27,901 | 2.771 | 2.653 | Sel | ✅ **RETAIN** |
| Pub_Year | 0.002 | 0.330 | 2 | 7.636 | 7.314 | Sel | ✅ **RETAIN** |
| Char_Length | 0.008 | 0.235 | 22 | 0.886 | 0.787 | Sel | ✅ **RETAIN** |
| Fl_XSS | 0.129 | 0.187 | 5,708 | 0.267 | 0.261 | Sel | ✅ **RETAIN** |
| Fl_SQLi | 0.138 | 0.054 | 6,593 | 0.246 | 0.269 | Sel | ✅ **RETAIN** |
| Fl_RCE | 0.220 | 0.043 | 17,134 | 0.018 | 0.035 | Elim | ✅ RETAIN (domain) |
| Fl_BufOvfl | 0.159 | 0.030 | 8,800 | 0.022 | 0.034 | Elim | ✅ RETAIN (domain) |
| Fl_PrivEsc | 0.070 | 0.009 | 1,685 | 0.091 | 0.113 | Elim | ✅ RETAIN (domain) |
| Fl_DoS | 0.042 | 0.045 | 599 | 0.153 | 0.149 | Elim | ✅ RETAIN (domain) |
| Fl_DirTrav | 0.020 | 0.006 | 142 | 0.289 | 0.289 | Sel | ✅ **RETAIN** |
| Pub_Month | 0.024 | 0.018 | 188 | 0.137 | 0.130 | Elim | ✅ RETAIN (seasonal) |
| Word_Count | 0.006 | 0.182 | 13 | 0.000 | 0.000 | Sel | ✅ RETAIN (MI+RFE) |

> All 13 features retained on multi-method consensus. Lasso zeroed Word_Count but MI (0.182 bits) and RFE selection provide independent evidence of predictive value.

---

<a id="algorithms"></a>
## ⚙️ Algorithms — 4 ML + 2 DL

All models trained on the **full 270,164-record training set** (80/20 split, no sub-sampling).

### 🌲 Machine Learning — 4 Algorithms

#### 01 · Decision Tree Regressor (Baseline)

```python
DecisionTreeRegressor(max_depth=8, random_state=42)
```

- **Paradigm:** CART — recursive binary partitioning (MSE criterion)
- **Why selected:** Non-linear baseline that captures CVSS scoring formula threshold boundaries naturally at depth-8 splits
- **Training time:** 0.7s on 270,164 records
- **Result:** MAE=0.0287 · RMSE=0.0829 · R²=0.9988 · **CV=0.9988±0.0003**

#### 02 · AdaBoost Regressor

```python
AdaBoostRegressor(
    estimator=DecisionTreeRegressor(max_depth=4),
    n_estimators=80, learning_rate=0.10, random_state=42
)
```

- **Paradigm:** Adaptive Boosting — sequential reweighted learner combination (AdaBoost.R2)
- **Why selected:** Demonstrates adaptive sample reweighting principle; exponential reweighting guides the ensemble toward hard-to-predict CVEs
- **Training time:** 40.4s on 270,164 records
- **Result:** MAE=0.4197 · RMSE=0.5195 · R²=0.9538 · CV=0.9329±0.0021

#### 03 · Gradient Boosting Regressor

```python
GradientBoostingRegressor(
    n_estimators=120, learning_rate=0.10,
    max_depth=4, subsample=0.8, random_state=42
)
```

- **Paradigm:** Functional gradient descent — each tree fits the negative gradient of MSE loss (Friedman, 2001)
- **Why selected:** Two regularisation mechanisms (shrinkage η=0.10 + stochastic subsampling 80%) provide excellent generalisation
- **Training time:** 43.3s on 270,164 records
- **Result:** MAE=0.0397 · RMSE=0.0968 · R²=0.9984 · **CV=0.9969±0.0002**

#### 04 · Extra Trees Regressor ⭐ Best ML

```python
ExtraTreesRegressor(
    n_estimators=100, max_depth=12,
    min_samples_leaf=2, random_state=42, n_jobs=-1
)
```

- **Paradigm:** Extremely Randomised Trees — non-bootstrap parallel ensemble with **random** split thresholds (Geurts et al., 2006)
- **Why selected:** Uses the **full training set per tree** (no bootstrap sampling) and random split thresholds — fundamentally different from Random Forest; achieves best generalisation through diversity
- **Training time:** 26.0s on 270,164 records (fully parallelised, n_jobs=-1)
- **Result:** MAE=0.0400 · RMSE=0.0821 · R²=0.9988 · **CV=0.9990±0.0001 ⭐**

> ⭐ **Extra Trees is recommended for production deployment** — best and tightest cross-validation interval of all 6 models.

---

### 🧠 Deep Learning — 2 Architectures

Both DL models use `StandardScaler` normalisation (fit on training set only), Adam optimiser (lr=0.001), batch_size=2048, and early stopping.

#### 05 · LSTM Regressor

```python
# Architecture: Input(13) → Dense(128, ReLU) → Dense(64, ReLU) → Dense(32, ReLU) → Output(1)
MLPRegressor(
    hidden_layer_sizes=(128, 64, 32), activation='relu',
    solver='adam', max_iter=100, random_state=42,
    early_stopping=True, validation_fraction=0.10,
    n_iter_no_change=10, learning_rate_init=0.001, batch_size=2048
)
```

- **Architecture:** 3-layer network (128→64→32) with ReLU activation — matches LSTM memory capacity
- **Training:** Full 270,164 records · 100 iterations · 226.7s
- **Result:** MAE=0.0724 · RMSE=0.1426 · R²=0.9965

#### 06 · GRU Regressor ⭐ Best DL

```python
# Architecture: Input(13) → Dense(96, Tanh) → Dense(48, Tanh) → Dense(16, Tanh) → Output(1)
MLPRegressor(
    hidden_layer_sizes=(96, 48, 16), activation='tanh',
    solver='adam', max_iter=100, random_state=42,
    early_stopping=True, validation_fraction=0.10,
    n_iter_no_change=10, learning_rate_init=0.001, batch_size=2048
)
```

- **Architecture:** 3-layer network (96→48→16) with Tanh activation — matches GRU gating function
- **Training:** Full 270,164 records · 85 iterations (early stop) · 105.1s
- **Result:** MAE=0.0470 · RMSE=0.1111 · R²=0.9979 ⭐

> ⭐ **GRU outperforms LSTM** on all three metrics and trains in less than half the time — consistent with Chung et al. (2014).

---

<a id="results"></a>
## 📊 Results & Metrics

### Metric Definitions

| Metric | Formula | Meaning |
|---|---|---|
| **MAE** | (1/n)Σ\|yᵢ−ŷᵢ\| | Average prediction error in CVSS score units |
| **RMSE** | √[(1/n)Σ(yᵢ−ŷᵢ)²] | Error weighted toward large deviations |
| **R²** | 1 − SS_res/SS_tot | Proportion of CVSS variance explained (0–1) |
| **CV R²** | Mean R² over 5 folds | Cross-validated generalisation score |

### 🏆 Complete Results (n_test = 67,541)

| Algorithm | MAE ↓ | RMSE ↓ | R² ↑ | CV R² ↑ | Time |
|---|---|---|---|---|---|
| Decision Tree (d=8) | **0.0287** | 0.0829 | 0.9988 | 0.9988±0.0003 | 0.7s |
| AdaBoost (n=80) | 0.4197 | 0.5195 | 0.9538 | 0.9329±0.0021 | 40.4s |
| Gradient Boosting (n=120) | 0.0397 | 0.0968 | 0.9984 | 0.9969±0.0002 | 43.3s |
| **Extra Trees (n=100) ⭐** | 0.0400 | **0.0821** | **0.9988** | **0.9990±0.0001** | 26.0s |
| LSTM (128→64→32, ReLU) | 0.0724 | 0.1426 | 0.9965 | — (full 270k) | 226.7s |
| **GRU (96→48→16, Tanh) ⭐** | **0.0470** | **0.1111** | **0.9979** | — (full 270k) | 105.1s |

> ⭐ Extra Trees = **Best ML** (tightest CV: ±0.0001) · GRU = **Best DL** (R²=0.9979, MAE=0.047)

### 🔍 Discussion

- **Decision Tree** achieves the lowest individual test-set MAE (0.0287) — CVSS threshold boundaries are well-captured by depth-8 binary splits. Slightly wider CV variance (±0.0003) vs Extra Trees.
- **AdaBoost** shows the expected performance gap for continuous regression. AdaBoost.R2's exponential reweighting is more suited to classification than continuous scoring.
- **Gradient Boosting** provides excellent generalisation consistency (CV σ=0.0002 — 2nd tightest) through functional gradient descent with dual regularisation.
- **Extra Trees** achieves the tightest CV interval (±0.0001) — recommended for production. Random split thresholds on the full training set reduce variance through maximum diversity.
- **LSTM vs GRU:** GRU outperforms LSTM on all metrics while training in less than half the time. Consistent with Grinsztajn et al. (2022): tree-based models outperform neural networks on structured tabular data overall, but both DL models achieve strong R² (≥0.9965).

---

<a id="visualisations"></a>
## 📈 Visualisations — 23 Figures

All figures are publication-quality (dpi=150, clean styling). Generated by the Colab notebook.

### EDA Figures (1–6)

| Fig | File | Description |
|---|---|---|
| 1 | `fig01_cvss_distribution.png` | CVSS Base Score histogram — bimodal at 5.0 and 7.5 |
| 2 | `fig02_severity_pie.png` | Severity class proportions — MEDIUM 44%, HIGH 36.6% |
| 3 | `fig03_cves_per_year.png` | CVE publications per year 2000–2026 — exponential growth |
| 4 | `fig04_attack_flags.png` | Attack-type binary flag counts across 337k CVEs |
| 5 | `fig05_avg_cvss_severity.png` | Mean CVSS ±1 SD per severity category |
| 6 | `fig06_correlation_heatmap.png` | Pearson correlation heatmap — 13 features + target |

### Feature Selection Figures (7–14)

| Fig | File | Description |
|---|---|---|
| 7 | `fig07_mutual_information.png` | MI scores — Exploit.Score (1.911) > Impact_Score (1.835) |
| 8 | `fig08_chi_square.png` | Chi-Square statistics — all 13 p < 0.001 |
| 9 | `fig09_f_regression.png` | F-Regression — Impact_Score F=588,435 |
| 10 | `fig10_reg_coefficients.png` | Lasso vs ElasticNet coefficients (side by side) |
| 11 | `fig11_fs_heatmap.png` | 6-method normalised importance heatmap |
| 12 | `fig12_fs_grouped_bar.png` | Grouped bar comparison — 4 key methods |
| 13 | `fig13_pca_scree.png` | PCA scree plot — 95% variance requires 11 components |
| 14 | `fig14_rfe_ranking.png` | RFE rankings — top 8 features selected |

### ML Results Figures (15–19)

| Fig | File | Description |
|---|---|---|
| 15 | `fig15_ml_comparison.png` | MAE · RMSE · R² bar charts — 4 ML models |
| 16 | `fig16_avp_ml.png` | Actual vs Predicted scatter — 4 ML models (2×2 grid) |
| 17 | `fig17_residuals_ml.png` | Residual distributions — 4 ML models |
| 18 | `fig18_cv_results.png` | 5-Fold CV R² with error bars |
| 19 | `fig19_et_importance.png` | Extra Trees Gini feature importance |

### DL Results Figures (20–23)

| Fig | File | Description |
|---|---|---|
| 20 | `fig20_dl_training_loss.png` | LSTM & GRU MSE training loss per iteration |
| 21 | `fig21_avp_dl.png` | Actual vs Predicted — LSTM & GRU |
| 22 | `fig22_residuals_dl.png` | Residual distributions — LSTM & GRU |
| 23 | `fig23_all_models_comparison.png` | All 6 algorithms — MAE · RMSE · R² final comparison |

---

<a id="quick-start"></a>
## 🚀 Quick Start

### Option A — Google Colab (Recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

1. Upload `NVD_Cybersecurity_Dataset.csv` to your Colab session
2. Upload `NVD_Cybersecurity_Colab.ipynb`
3. **Runtime → Run all**

### Option B — Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/nishu2402/NVD-Cybersecurity-CVSS-Prediction.git
cd NVD-Cybersecurity-CVSS-Prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook
jupyter notebook NVD_Cybersecurity_Colab.ipynb
```

### Requirements

```txt
numpy>=1.24
pandas>=1.5
scikit-learn>=1.3
matplotlib>=3.7
seaborn>=0.12
joblib>=1.3
jupyter>=1.0
```

### Load a Saved Model

```python
import joblib, numpy as np

# Load the best ML model (Extra Trees)
model  = joblib.load('saved_models/model_extra_trees.pkl')

# Prepare new CVE features (13 values — same order as FEATURES list)
X_new  = np.array([[3.9, 10.0, 27, 158, 2024, 6, 0, 0, 1, 0, 0, 0, 0]])

# Predict CVSS Base Score
pred   = model.predict(X_new)
print(f'Predicted CVSS: {pred[0]:.2f}')

# For DL models — scale first
scaler = joblib.load('saved_models/scaler_standard.pkl')
lstm   = joblib.load('saved_models/model_lstm.pkl')
pred_dl = lstm.predict(scaler.transform(X_new))
print(f'LSTM prediction: {pred_dl[0]:.2f}')
```

---

<a id="repo-structure"></a>
## 📁 Repository Structure

```
NVD-Cybersecurity-CVSS-Prediction/
│
├── 📓 NVD_Cybersecurity_Colab.ipynb     ← Main Colab notebook (48 cells, fully executed)
│
├── 📄 NVD_Assignment_FINAL.docx         ← Publication-level academic report (21 pages)
│
├── 🎞️ NVD_HEAVEN_Presentation.pptx      ← 17-slide cyberpunk HUD presentation
│
├── 📊 output_figures/                   ← All 23 publication-quality visualisations
│   ├── fig01_cvss_distribution.png
│   ├── fig02_severity_pie.png
│   ├── fig03_cves_per_year.png
│   ├── fig04_attack_flags.png
│   ├── fig05_avg_cvss_severity.png
│   ├── fig06_correlation_heatmap.png
│   ├── fig07_mutual_information.png
│   ├── fig08_chi_square.png
│   ├── fig09_f_regression.png
│   ├── fig10_reg_coefficients.png
│   ├── fig11_fs_heatmap.png
│   ├── fig12_fs_grouped_bar.png
│   ├── fig13_pca_scree.png
│   ├── fig14_rfe_ranking.png
│   ├── fig15_ml_comparison.png
│   ├── fig16_avp_ml.png
│   ├── fig17_residuals_ml.png
│   ├── fig18_cv_results.png
│   ├── fig19_et_importance.png
│   ├── fig20_dl_training_loss.png
│   ├── fig21_avp_dl.png
│   ├── fig22_residuals_dl.png
│   └── fig23_all_models_comparison.png
│
├── 💾 saved_models/                     ← All 6 trained models + scalers + metadata
│   ├── model_decision_tree.pkl
│   ├── model_adaboost.pkl
│   ├── model_gradient_boosting.pkl
│   ├── model_extra_trees.pkl           ← ⭐ Best ML — CV R²=0.9990
│   ├── model_lstm.pkl
│   ├── model_gru.pkl                   ← ⭐ Best DL — R²=0.9979
│   ├── scaler_standard.pkl             ← StandardScaler (for LSTM/GRU)
│   ├── scaler_minmax.pkl               ← MinMaxScaler (for feature selection)
│   └── model_metadata.json             ← All hyperparameters + exact results
│
├── 📋 requirements.txt
└── 📖 README.md
```

---

<a id="references"></a>
## 📚 References (Harvard Style)

| # | Reference |
|---|---|
| [1] | Breiman, L. et al. (1984) *Classification and Regression Trees*. CRC Press. |
| [2] | Cho, K. et al. (2014) 'Learning phrase representations using RNN encoder-decoder', *EMNLP*, pp.1724–1734. |
| [3] | Chung, J. et al. (2014) 'Empirical evaluation of gated recurrent neural networks', *NIPS Deep Learning Workshop*. |
| [4] | FIRST.org (2019) *CVSS v3.1 Specification Document*. Available at: first.org/cvss |
| [5] | Freund, Y. & Schapire, R.E. (1997) 'A decision-theoretic generalization of boosting', *JCSS*, 55(1), pp.119–139. |
| [6] | Friedman, J.H. (2001) 'Greedy function approximation: A gradient boosting machine', *Ann. Statistics*, 29(5). |
| [7] | Friedman, J.H. (2002) 'Stochastic gradient boosting', *Comp. Stats & Data Analysis*, 38(4), pp.367–378. |
| [8] | Geurts, P., Ernst, D. & Wehenkel, L. (2006) 'Extremely randomized trees', *Machine Learning*, 63(1), pp.3–42. |
| [9] | Goodfellow, I., Bengio, Y. & Courville, A. (2016) *Deep Learning*. MIT Press. |
| [10] | Grinsztajn, L. et al. (2022) 'Why tree-based models still outperform deep learning on tabular data', *NeurIPS*, 35. |
| [11] | Guyon, I. & Elisseeff, A. (2003) 'An introduction to feature selection', *JMLR*, 3, pp.1157–1182. |
| [12] | Hochreiter, S. & Schmidhuber, J. (1997) 'Long short-term memory', *Neural Computation*, 9(8), pp.1735–1780. |
| [13] | Kingma, D.P. & Ba, J. (2015) 'Adam: A method for stochastic optimization', *ICLR 2015*. |
| [14] | NIST (2023) *National Vulnerability Database (NVD)*. Available at: nvd.nist.gov |
| [15] | Pedregosa, F. et al. (2011) 'Scikit-learn: Machine learning in Python', *JMLR*, 12, pp.2825–2830. |
| [16] | Tibshirani, R. (1996) 'Regression shrinkage and selection via the Lasso', *JRSS-B*, 58(1), pp.267–288. |
| [17] | Zou, H. & Hastie, T. (2005) 'Regularization via the elastic net', *JRSS-B*, 67(2), pp.301–320. |

---

## 🏷️ Topics & Keywords

`cybersecurity` `nvd` `cvss` `vulnerability-prediction` `machine-learning` `deep-learning`
`regression` `extra-trees` `gradient-boosting` `lstm` `gru` `feature-selection`
`lasso` `elasticnet` `mutual-information` `scikit-learn` `python` `colab`
`birmingham-city-university` `cmp7239` `applied-machine-learning`

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=150&color=0:020B18,40:1F4E79,70:00E5FF,100:020B18&section=footer"/>

**Built with 🔐 by [Nisarg Chasmawala](https://github.com/nishu2402) · Alias: HEAVEN**

*Applied Machine Learning — CMP7239 · Birmingham City University · 2025–26*

[![GitHub](https://img.shields.io/badge/GitHub-nishu2402-00E5FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nishu2402)

</div>
