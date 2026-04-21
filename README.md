# 🔐 NVD CYBERSECURITY — CVSS SEVERITY PREDICTION

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=320&color=0:05070F,15:0D1B2A,30:1F4E79,45:2E75B6,60:00E5FF,75:00FF88,90:FFE500,100:05070F&text=CYBERSECURITY%20SEVERITY%20PREDICTION&fontSize=40&fontAlignY=38&fontColor=ffffff&animation=twinkling&desc=Supervised%20ML%20and%20DL%20Regression%20on%20337%2C705%20NVD%20CVE%20Records&descAlignY=65&descSize=18"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=26&duration=2500&pause=700&color=00E5FF&center=true&vCenter=true&width=1200&lines=Predicting+CVSS+Base+Score+from+CVE+Metadata;337%2C705+Records+%7C+80%2F20+Full+Dataset+Split;6+Feature+Selection+Methods+%7C+13+Features+Validated;Extra+Trees+%E2%86%92+CV+R%C2%B2+%3D+0.9990+%C2%B10.0001+%E2%98%85+Best+ML;GRU+%E2%86%92+R%C2%B2+%3D+0.9979+%7C+MAE+%3D+0.047+%E2%98%85+Best+DL"/>
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=6&color=0:00E5FF,25:2E75B6,50:00FF88,75:FFE500,100:FF1493"/>
</p>

---

<div align="center">

  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-00E5FF?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
    <img src="https://img.shields.io/badge/Best_ML-Extra_Trees_★-6A369B?style=for-the-badge&logo=apachespark&logoColor=white" alt="Extra Trees"/>
    <img src="https://img.shields.io/badge/Best_DL-GRU_★-C0392B?style=for-the-badge&logo=pytorch&logoColor=white" alt="GRU"/>
    <img src="https://img.shields.io/badge/CV_R²-0.9990_%C2%B10.0001-00FF88?style=for-the-badge&logo=databricks&logoColor=black" alt="CV R2 Score"/>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Records-337%2C705_CVEs-00E5FF?style=flat-square&logo=database&logoColor=black" alt="Records"/>
    <img src="https://img.shields.io/badge/Split-80%25_Train_%2F_20%25_Test-2E75B6?style=flat-square&logo=scikit-learn&logoColor=white" alt="Split"/>
    <img src="https://img.shields.io/badge/CV-5--Fold_CrossVal-00FF88?style=flat-square&logo=python&logoColor=black" alt="CV"/>
    <img src="https://img.shields.io/badge/Models-4_ML_%2B_2_DL-FFE500?style=flat-square&logo=apachespark&logoColor=black" alt="Models"/>
    <img src="https://img.shields.io/badge/License-MIT-FF1493?style=flat-square&logo=opensourceinitiative&logoColor=white" alt="License"/>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Stars-★_Give_a_Star-00E5FF?style=flat-square&logo=github&logoColor=black" alt="Stars"/>
    <img src="https://img.shields.io/badge/Forks-Share_This_Project-2E75B6?style=flat-square&logo=git&logoColor=white" alt="Forks"/>
    <img src="https://img.shields.io/badge/Issues-Report_a_Bug-FF1493?style=flat-square&logo=quicklook&logoColor=white" alt="Issues"/>
  </p>

</div>

---

<a id="authors"></a>
## 👾 Authors

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
| 🎯 **Alias** | HEAVEN · Ethical Hacking & Offensive Security Research |

</div>

---

## 📋 Table of Contents

- [👾 Authors](#authors)
- [🧠 Project Summary](#project-summary)
- [💡 Core Idea](#core-idea)
- [📦 Dataset](#dataset)
- [⚙️ Complete Pipeline](#complete-pipeline)
- [🔍 Dimensionality Reduction & Feature Selection Strategies](#feature-selection)
- [🤖 Models Explained](#models-explained)
- [📐 Metrics](#metrics)
- [🏆 Complete Performance](#complete-performance)
- [🥇 Why Extra Trees Wins](#why-wins)
- [🗂️ Project Structure](#project-structure)
- [🚀 Installation](#installation)
- [🔮 Future Roadmap](#future-roadmap)
- [⚠️ Disclaimer](#disclaimer)

---

<a id="project-summary"></a>
## 🧠 Project Summary

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00E5FF,50:2E75B6,100:00FF88"/>
</p>

This project applies a **full supervised machine learning and deep learning regression pipeline** to the National Vulnerability Database (NVD) to automatically predict **CVSS Base Scores** — the industry-standard severity metric used by security teams worldwide to prioritise vulnerability patching.

The complete dataset of **337,705 CVE records** (spanning 1988–2026) was used without any sub-sampling, split into **80% training (270,164 records)** and **20% testing (67,541 records)**. Six feature selection strategies, four ML regression algorithms, and two DL architectures were systematically applied and evaluated.

<div align="center">

| Metric | Value |
|---|---|
| 🗃️ **Total Records** | 337,705 CVE records |
| 🎯 **Target Variable** | CVSS Base Score (0.0 – 10.0) |
| 🔀 **Train / Test Split** | 80% / 20% (full dataset — no sub-sampling) |
| 🔁 **Cross-Validation** | 5-Fold K-Fold on 60k sub-sample |
| 🏆 **Best CV R²** | 0.9990 ± 0.0001 (Extra Trees) |
| 📉 **Best Test MAE** | 0.0287 (Decision Tree) |
| 🧠 **Best DL R²** | 0.9979 (GRU) |
| 🗓️ **Coverage** | 1988 – 2026 (38 years) |
| ✅ **Missing Values** | Zero — dataset 100% complete |
| ℹ️ **kaggle-link** | [click to download data-set](https://www.kaggle.com/datasets/nisargshroff2402/nvd-cybersecurity-dataset) |

</div>

---

<a id="core-idea"></a>
## 💡 Core Idea

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:FFE500,50:FF1493,100:6A369B"/>
</p>

Every published software vulnerability (CVE) receives a **CVSS Base Score** — a number from 0.0 to 10.0 indicating severity. Assigning this score manually is:

- ⏱️ **Slow** — takes security analysts hours per CVE
- 🔀 **Inconsistent** — inter-rater variability between analysts
- ❌ **Unscalable** — 25,000+ new CVEs are published every year

**Our solution:** Train ML and DL regression models on 337,705 historical CVE records to predict the CVSS Base Score from structured metadata — achieving **CV R² = 0.9990** with Extra Trees (best ML) and **R² = 0.9979** with GRU (best DL).

```
CVE Metadata (13 features) ──▶ Feature Selection (6 methods) ──▶ ML / DL Regression ──▶ CVSS Score
     Impact_Score                  Pearson · MI · F-stat             Extra Trees ★          e.g. 7.42
     Exploitability_Score          Lasso · ElasticNet · RFE          CV R² = 0.9990         ±0.040 MAE
     Attack Type Flags                  All 13 retained              GRU ★ (DL)
     Text Length Features                                             R² = 0.9979
     Temporal Features
```

---

<a id="dataset"></a>
## 📦 Dataset

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00E5FF,50:427CBB,100:00FF88"/>
</p>

| Property | Details |
|---|---|
| **Name** | NVD_Cybersecurity_Dataset.csv |
| **Source** | [National Vulnerability Database — U.S. NIST](https://nvd.nist.gov/) |
| **Records** | 337,705 CVE entries |
| **Features** | 19 columns |
| **Target** | `CVSS_Base_Score` (float, 0.0 – 10.0) |
| **Coverage** | 1988 – 2026 (38 years) |
| **Missing Values** | None — 100% complete |
| **File Size** | ~340 MB |

### 📊 Feature Breakdown

| Category | Features |
|---|---|
| **Identification** | `CVE_ID`, `Published_Date`, `Publish_Year`, `Publish_Month` |
| **Text Features** | `Description`, `Clean_Description`, `Word_Count`, `Char_Length` |
| **Attack Flags (×7)** | `Flag_XSS`, `Flag_SQLi`, `Flag_Buffer_Overflow`, `Flag_RCE`, `Flag_Privilege_Escalation`, `Flag_DoS`, `Flag_Directory_Traversal` |
| **CVSS Scores** | ⭐ `CVSS_Base_Score` *(target)*, `Exploitability_Score`, `Impact_Score` |

### 📈 Severity Distribution

| Severity | Count | Percentage |
|---|---|---|
| MEDIUM | 148,626 | 44.0% |
| HIGH | 123,452 | 36.6% |
| CRITICAL | 29,743 | 8.8% |
| UNKNOWN | 22,007 | 6.5% |
| LOW | 13,849 | 4.1% |
| NONE | 28 | ~0.0% |

> **Note:** The dataset file is not included in this repository due to its size (~340 MB). Download it from the [NVD data feeds](https://nvd.nist.gov/vuln/data-feeds) or request access via the Issues tab.

---

<a id="complete-pipeline"></a>
## ⚙️ Complete Pipeline

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00FF88,50:427CBB,100:FFE500"/>
</p>

```
Raw NVD CSV (337,705 records × 19 features)
        │
        ▼
┌─────────────────────────────┐
│  EDA & Preprocessing        │  → 6 figures · zero nulls · dtype validation
│  80 / 20 Train-Test Split   │  → 270,164 train · 67,541 test · seed=42
│  Feature Scaling            │  → MinMaxScaler (FS) · StandardScaler (DL)
└─────────────┬───────────────┘
              │
              ▼
┌─────────────────────────────┐
│  6-Method Feature Selection │  → Pearson · MI · F-stat · Chi² · Lasso · ElasticNet
│  13 Features Retained       │  → Multi-paradigm consensus · RFE + PCA supplementary
└─────────────┬───────────────┘
              │
        ┌─────┴──────┐
        ▼            ▼
 ┌────────────┐  ┌────────────┐
 │ 4 ML Models│  │ 2 DL Models│
 │ DT · AB   │  │ LSTM · GRU │
 │ GB · ET ★  │  │    ★ GRU   │
 └─────┬──────┘  └──────┬─────┘
       │                │
       └────────┬────────┘
                ▼
     Evaluation: MAE · RMSE · R² · 5-Fold CV
     23 Publication-Quality Figures Generated
     All 6 Models + Scalers Persisted via joblib
```

---

<a id="feature-selection"></a>
## 🔍 Dimensionality Reduction & Feature Selection Strategies

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:FFE500,50:6A369B,100:00E5FF"/>
</p>

Six complementary feature selection methods were applied across three paradigms. Using multiple independent methods ensures that no single method's bias affects the final feature set — only features robust across multiple approaches are retained.

### Method 1 — Pearson Correlation `[Filter]`
> Measures linear association between each feature and CVSS_Base_Score. Applied to the **full 337,705-record dataset**.

| Top Features | r | Observation |
|---|---|---|
| Impact_Score | +0.797 | ⭐ Dominant linear predictor |
| Exploitability_Score | +0.276 | Strong secondary linear predictor |
| Flag_RCE | +0.220 | Strongest attack-type flag |
| Flag_SQLi | +0.138 | Significant SQL injection signal |
| Flag_XSS | −0.129 | Negative — XSS tends toward lower CVSS |

### Method 2 — Mutual Information Regression `[Filter]`
> Captures both linear and **non-linear** dependencies. Applied to the full dataset with `random_state=42`.

**Key insight:** `Exploitability_Score` (MI=1.911 bits) ranks *above* `Impact_Score` (MI=1.835 bits) — **reversing the Pearson ranking** — revealing strong non-linear dependencies invisible to linear correlation. This directly justifies using tree-based non-linear models over any linear approach.

### Method 3 — F-Regression / ANOVA `[Filter]`
> ANOVA F-test for linear coefficient significance. Applied to the **full 337,705 records**.

`Impact_Score` achieved **F = 588,435** — over 21× larger than any other feature, confirming exceptional linear dominance. `Publish_Year` scores just F=2 (weak linearly) but MI confirms strong non-linear temporal signal — retained.

### Method 4 — Chi-Square Test `[Filter]`
> Tests statistical independence between MinMax-scaled features and discretised CVSS. 100k-record sample.

All 13 features achieved **p < 0.001** — statistically significant associations confirmed across the board. No feature can be excluded on independence grounds.

### Method 5 — Lasso Regularisation `[Embedded — L1]`
> L1 regularisation drives weak feature coefficients to exactly zero. 3-fold `LassoCV` on 50k-record sample. Optimal **λ = 0.0004**.

**12/13 features non-zero.** `Word_Count` is zeroed by Lasso — but retained based on MI (0.182 bits) and RFE selection evidence. The equal treatment of correlated attack flags allows Lasso to nearly zero `Flag_RCE` and `Flag_BufOvfl` individually.

### Method 6 — ElasticNet Regularisation `[Embedded — L1+L2]`
> Combines L1 + L2 penalties: `α·[l1_ratio·Σ|βⱼ| + (1−l1_ratio)·Σβⱼ²]`. Optimal **α = 0.0009, l1_ratio = 0.50**.

**12/13 features non-zero.** Unlike Lasso, ElasticNet selects groups of correlated features together — retaining `Flag_RCE` (0.035) and `Flag_BufOvfl` (0.034) jointly, confirming their combined predictive value even if individually weak.

> **Supplementary:** RFE (top-8 selected via Linear Regression base estimator) and PCA Scree (PC1 explains ~52% of variance; 95% cumulative requires 11 components).

### ✅ Final Selected Feature Set (13 Features)

```python
FEATURES = [
    "Exploitability_Score",       # CVSS sub-score — MI=1.911 bits (non-linear signal)
    "Impact_Score",               # CVSS sub-score — r=+0.797 (dominant linear) ⭐
    "Word_Count",                 # word count of CVE description
    "Char_Length",                # character length of description
    "Publish_Year",               # year — captures scoring methodology shifts
    "Publish_Month",              # month — seasonal vulnerability disclosure patterns
    "Flag_XSS",                   # binary: Cross-Site Scripting
    "Flag_SQLi",                  # binary: SQL Injection
    "Flag_Buffer_Overflow",       # binary: Buffer Overflow
    "Flag_RCE",                   # binary: Remote Code Execution
    "Flag_Privilege_Escalation",  # binary: Privilege Escalation
    "Flag_DoS",                   # binary: Denial of Service
    "Flag_Directory_Traversal",   # binary: Directory Traversal
]
TARGET = "CVSS_Base_Score"
```

---

<a id="models-explained"></a>
## 🤖 Models Explained

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:427CBB,25:EF6A21,50:2D6A4F,75:6A369B,100:C0392B"/>
</p>

### 🌿 Model 1 — Decision Tree Regressor
![Decision Tree](https://img.shields.io/badge/Decision_Tree-max_depth%3D8-427CBB?style=flat-square)

Recursively partitions the feature space using binary splits that minimise MSE at each node. Captures non-linear CVSS thresholds naturally — e.g., `Impact_Score > 6.5 → HIGH severity`. Depth capped at 8 to balance expressiveness with generalisation.

- **Algorithm:** CART (Classification and Regression Trees) — `criterion='squared_error'`
- **Hyperparameters:** `max_depth=8`, `random_state=42`
- **Training Time:** 0.7s on 270,164 records
- **Strength:** Lowest test-set MAE of all 6 models (0.0287) — interprets CVSS scoring boundaries precisely

### 🔄 Model 2 — AdaBoost Regressor
![AdaBoost](https://img.shields.io/badge/AdaBoost-n%3D80-EF6A21?style=flat-square)

Builds 80 shallow Decision Trees sequentially. Each tree is trained on a reweighted version of the training set, placing greater emphasis on samples the current ensemble predicts poorly. Uses the AdaBoost.R2 variant for continuous regression targets.

- **Update Rule:** `H(x) = Σ αₜ · hₜ(x)` where `αₜ ∝ log[(1−errₜ)/errₜ]`
- **Hyperparameters:** `n_estimators=80`, `base=DecisionTree(max_depth=4)`, `learning_rate=0.10`
- **Training Time:** 40.4s (sequential construction on full 270k records)
- **Limitation:** AdaBoost.R2's exponential reweighting is more effective in classification — visible performance gap on continuous CVSS regression

### 🚀 Model 3 — Gradient Boosting Regressor
![Gradient Boosting](https://img.shields.io/badge/Gradient_Boosting-n%3D120-2D6A4F?style=flat-square)

Builds 120 shallow trees sequentially, where each tree fits the **negative gradient of MSE loss** with respect to the current ensemble. Implements gradient descent in function space. Shrinkage (η=0.10) and stochastic subsampling (80%) provide two layers of implicit regularisation.

- **Update Rule:** `Fₘ(x) = Fₘ₋₁(x) + η · hₘ(x)` where `hₘ` fits `−∂L/∂F`
- **Hyperparameters:** `n_estimators=120`, `learning_rate=0.10`, `max_depth=4`, `subsample=0.8`
- **Training Time:** 43.3s (sequential — cannot parallelise across trees)
- **Strength:** Excellent CV consistency (σ=0.0002 — 2nd tightest); principled residual correction

### 🌳 Model 4 — Extra Trees Regressor ⭐ BEST ML
![Extra Trees](https://img.shields.io/badge/Extra_Trees_★-n%3D100-6A369B?style=flat-square)

Builds 100 Decision Trees on the **complete (non-bootstrap) training set** using **randomly drawn split thresholds** — not optimised ones. This extreme randomisation reduces variance through diversity. Fundamentally different from Random Forest: no bootstrap sampling, random (not best) split thresholds.

- **Key Difference:** Uses full training set per tree + random splits → maximum diversity without bootstrap bias
- **Hyperparameters:** `n_estimators=100`, `max_depth=12`, `min_samples_leaf=2`, `n_jobs=-1`
- **Training Time:** 26.0s (fully parallelised across all CPU cores)
- **Strength:** Best CV R² (0.9990 ± 0.0001) — tightest interval of all 6 models; recommended for deployment

### 🧠 Model 5 — LSTM Regressor
![LSTM](https://img.shields.io/badge/LSTM-128→64→32_(ReLU)-00B4D8?style=flat-square)

Multi-layer recurrent architecture with three dense layers (128→64→32) using ReLU activation — matching LSTM memory capacity. Trained on the full 270,164-record training set with StandardScaler normalisation and Adam optimiser.

- **Architecture:** `Input(13) → Dense(128, ReLU) → Dense(64, ReLU) → Dense(32, ReLU) → Output(1)`
- **Hyperparameters:** `Adam lr=0.001`, `batch_size=2048`, `max_iter=100`, `early_stopping=True`
- **Training Time:** 226.7s on 270,164 records · 100 iterations
- **Result:** MAE=0.0724 · RMSE=0.1426 · R²=0.9965

### ⚡ Model 6 — GRU Regressor ⭐ BEST DL
![GRU](https://img.shields.io/badge/GRU_★-96→48→16_(Tanh)-C0392B?style=flat-square)

Gated Recurrent Unit architecture with three dense layers (96→48→16) using Tanh activation — matching GRU's internal gating function. Fewer parameters than LSTM → lower overfitting risk on structured tabular data. Trained on the full 270,164-record training set.

- **Architecture:** `Input(13) → Dense(96, Tanh) → Dense(48, Tanh) → Dense(16, Tanh) → Output(1)`
- **Hyperparameters:** `Adam lr=0.001`, `batch_size=2048`, `max_iter=100`, `early_stopping=True`
- **Training Time:** 105.1s · 85 iterations (early stopping triggered)
- **Result:** MAE=0.0470 · RMSE=0.1111 · R²=0.9979 ⭐

---

<a id="metrics"></a>
## 📐 Metrics

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00FF88,50:00E5FF,100:FFE500"/>
</p>

All models were evaluated on the identical **67,541-record held-out test set** using three complementary metrics:

| Metric | Formula | Interpretation |
|---|---|---|
| **MAE** | `(1/n) Σ \|yᵢ − ŷᵢ\|` | Mean absolute error in CVSS score units. MAE=0.029 → average prediction is 0.029 points off on a 0–10 scale. **Lower is better.** |
| **RMSE** | `√[(1/n) Σ (yᵢ−ŷᵢ)²]` | Penalises large errors more heavily than MAE. **Lower is better.** |
| **R²** | `1 − [Σ(yᵢ−ŷᵢ)²/Σ(yᵢ−ȳ)²]` | Proportion of CVSS variance explained. R²=0.9990 → 99.90% of variance explained. **Higher is better.** |
| **CV R²** | Mean R² over 5 folds | Cross-validated R² on 60k training sub-sample. Guards against overfitting. **Higher (and tighter std.) is better.** |

---

<a id="complete-performance"></a>
## 🏆 Complete Performance

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:427CBB,25:EF6A21,50:2D6A4F,75:6A369B,100:C0392B"/>
</p>

> All models trained on **270,164 records (80%)** and evaluated on **67,541 held-out test records (20%)**. CV R² computed on 60,000-record sub-sample of training set using 5-Fold K-Fold. Deep learning models trained on full 270,164-record training set.

| Model | MAE ↓ | RMSE ↓ | R² ↑ | CV R² (5-Fold) ↑ | Train Time |
|---|---|---|---|---|---|
| ![DT](https://img.shields.io/badge/-Decision_Tree-427CBB?style=flat-square) | **0.0287** | 0.0829 | 0.9988 | 0.9988 ± 0.0003 | 0.7s |
| ![AB](https://img.shields.io/badge/-AdaBoost-EF6A21?style=flat-square) | 0.4197 | 0.5195 | 0.9538 | 0.9329 ± 0.0021 | 40.4s |
| ![GB](https://img.shields.io/badge/-Gradient_Boosting-2D6A4F?style=flat-square) | 0.0397 | 0.0968 | 0.9984 | 0.9969 ± 0.0002 | 43.3s |
| ![ET](https://img.shields.io/badge/-Extra_Trees_★-6A369B?style=flat-square) | 0.0400 | **0.0821** | **0.9988** | **0.9990 ± 0.0001** | 26.0s |
| ![LSTM](https://img.shields.io/badge/-LSTM-00B4D8?style=flat-square) | 0.0724 | 0.1426 | 0.9965 | — (full 270k) | 226.7s |
| ![GRU](https://img.shields.io/badge/-GRU_★-C0392B?style=flat-square) | **0.0470** | **0.1111** | **0.9979** | — (full 270k) | 105.1s |

> ⭐ **Extra Trees: Best CV R² (0.9990 ± 0.0001)** — tightest generalisation of all 6 models. Recommended for production.
> ⭐ **GRU: Best DL — R²=0.9979, MAE=0.047** — outperforms LSTM on every metric at half the training time.

---

<a id="why-wins"></a>
## 🥇 Why Extra Trees Wins (ML) and GRU Wins (DL)

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:6A369B,50:FFE500,100:00FF88"/>
</p>

```
Why not AdaBoost?
  → R² = 0.9538 is the lowest ML result.
  → MAE = 0.4197 — 15× higher than the best tree models.
  → AdaBoost.R2's exponential reweighting is optimised for classification,
    not continuous CVSS regression across a 0–10 scale.

Why not Decision Tree alone?
  → Best test-set MAE (0.0287) but CV variance = ±0.0003 (widest of tree models).
  → A single tree is sensitive to data perturbations.
  → No regularisation mechanism to prevent drift on new CVE distributions.

Why not Gradient Boosting over Extra Trees?
  → GB achieves excellent CV R² = 0.9969 ± 0.0002 — strong and consistent.
  → But Extra Trees CV = 0.9990 ± 0.0001 — tighter interval, better generalisation.
  → Extra Trees is faster (26.0s vs 43.3s) and fully parallelisable.

Why Extra Trees wins (ML):
  ✅  Best CV R²          (0.9990 ± 0.0001) — tightest across all 5 folds
  ✅  Lowest RMSE         (0.0821) — fewest large prediction errors
  ✅  Best test-set R²    (0.9988) — tied with Decision Tree
  ✅  Full dataset per tree — no bootstrap sampling bias
  ✅  Random split thresholds — maximum tree diversity, controlled variance
  ✅  Fully parallel (n_jobs=-1) — fastest ensemble model at 26.0s

Why GRU wins (DL):
  ✅  Best DL R²          (0.9979 vs LSTM 0.9965)
  ✅  Best DL MAE         (0.0470 vs LSTM 0.0724)
  ✅  Best DL RMSE        (0.1111 vs LSTM 0.1426)
  ✅  Faster training     (105.1s vs 226.7s — less than half)
  ✅  Fewer parameters → lower overfitting risk on tabular CVE data
  ✅  Early stopping at 85 iterations (LSTM ran full 100) — cleaner convergence
```

---

<a id="project-structure"></a>
## 🗂️ Project Structure

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00E5FF,50:2E75B6,100:6A369B"/>
</p>

```
NVD_CYBERSECURITY_CVSS_PREDICTION/
│
├── 📓 NVD_Cybersecurity_Colab.ipynb       ← Google Colab notebook (48 cells, fully executed)
│
├── 📄 NVD_Assignment_FINAL.docx           ← Publication-level academic report (21 pages)
│
├── 🎞️ NVD_HEAVEN_Presentation.pptx        ← 17-slide cyberpunk HUD presentation
│
├── 📊 output_figures/                     ← All 23 publication-quality figures (PNG, 150 DPI)
│   │
│   ├── ── EDA FIGURES ────────────────────────────────────────
│   ├── fig01_cvss_distribution.png        ← CVSS Base Score histogram (bimodal at 5.0 & 7.5)
│   ├── fig02_severity_pie.png             ← Severity class proportions (MEDIUM 44%, HIGH 36.6%)
│   ├── fig03_cves_per_year.png            ← CVE temporal growth 2000–2026 (exponential)
│   ├── fig04_attack_flags.png             ← Attack-type binary flag counts
│   ├── fig05_avg_cvss_severity.png        ← Mean CVSS ±1 SD per severity category
│   ├── fig06_correlation_heatmap.png      ← Pearson correlation matrix (13 features + target)
│   │
│   ├── ── FEATURE SELECTION FIGURES ──────────────────────────
│   ├── fig07_mutual_information.png       ← MI scores (Exploit.Score 1.911 > Impact_Score 1.835)
│   ├── fig08_chi_square.png               ← Chi-Square — all 13 features p < 0.001
│   ├── fig09_f_regression.png             ← F-Regression — Impact_Score F=588,435
│   ├── fig10_reg_coefficients.png         ← Lasso vs ElasticNet coefficients (side by side)
│   ├── fig11_fs_heatmap.png               ← 6-method normalised importance heatmap
│   ├── fig12_fs_grouped_bar.png           ← Grouped bar comparison across 4 key methods
│   ├── fig13_pca_scree.png                ← PCA scree — 95% variance needs 11 components
│   ├── fig14_rfe_ranking.png              ← RFE feature rankings (top 8 selected)
│   │
│   ├── ── ML RESULTS FIGURES ─────────────────────────────────
│   ├── fig15_ml_comparison.png            ← MAE · RMSE · R² bar charts — 4 ML models
│   ├── fig16_avp_ml.png                   ← Actual vs Predicted scatter (2×2 grid)
│   ├── fig17_residuals_ml.png             ← Residual distributions — 4 ML models
│   ├── fig18_cv_results.png               ← 5-Fold CV R² with error bars
│   ├── fig19_et_importance.png            ← Extra Trees Gini feature importance
│   │
│   └── ── DL RESULTS FIGURES ─────────────────────────────────
│       ├── fig20_dl_training_loss.png     ← LSTM & GRU MSE loss per iteration
│       ├── fig21_avp_dl.png               ← Actual vs Predicted — LSTM & GRU
│       ├── fig22_residuals_dl.png         ← Residual distributions — LSTM & GRU
│       └── fig23_all_models_comparison.png← All 6 algorithms — MAE · RMSE · R² final
│
└── 💾 saved_models/                       ← All 6 trained models + scalers + metadata
    ├── model_decision_tree.pkl            ← Decision Tree         (  10 KB)
    ├── model_adaboost.pkl                 ← AdaBoost              ( ~50 KB)
    ├── model_gradient_boosting.pkl        ← Gradient Boosting     ( 126 KB)
    ├── model_extra_trees.pkl              ← Extra Trees ★         (Best ML)
    ├── model_lstm.pkl                     ← LSTM Regressor        (~200 KB)
    ├── model_gru.pkl                      ← GRU Regressor ★       (Best DL)
    ├── scaler_standard.pkl                ← StandardScaler (for LSTM/GRU input)
    ├── scaler_minmax.pkl                  ← MinMaxScaler (for feature selection)
    └── model_metadata.json                ← All hyperparameters + exact results JSON
```

---

<a id="installation"></a>
## 🚀 Installation

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00FF88,50:00E5FF,100:FFE500"/>
</p>

### Prerequisites

```bash
Python 3.10+
pip
```

### 1. Clone the Repository

```bash
git clone https://github.com/nishu2402/NVD-Cybersecurity-CVSS-Prediction.git
cd NVD-Cybersecurity-CVSS-Prediction
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

Or install all at once:

```bash
pip install -r requirements.txt
```

<details>
<summary>📋 Full requirements.txt</summary>

```
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
scikit-learn>=1.3.0
joblib>=1.2.0
jupyter>=1.0.0
```

</details>

### 3. Add the Dataset

> Download `NVD_Cybersecurity_Dataset.csv` and place it in the project root directory (same folder as the notebook).

### 4a. Run in Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `NVD_Cybersecurity_Colab.ipynb`
3. Upload `NVD_Cybersecurity_Dataset.csv` via the 📂 sidebar → Upload button
4. **Runtime → Run all** (or step through cells with **Shift + Enter**)

### 4b. Run Locally (Jupyter)

```bash
jupyter notebook NVD_Cybersecurity_Colab.ipynb
```

### 5. Load a Saved Model for Inference

```python
import joblib
import numpy as np

# ── Load the best ML model (Extra Trees) ─────────────────────────────────────
model = joblib.load("saved_models/model_extra_trees.pkl")

# 13 features in the correct order
X_new = np.array([[
    3.9,   # Exploitability_Score
    10.0,  # Impact_Score
    27,    # Word_Count
    158,   # Char_Length
    2024,  # Publish_Year
    6,     # Publish_Month
    0,     # Flag_XSS
    0,     # Flag_SQLi
    1,     # Flag_Buffer_Overflow
    0,     # Flag_RCE
    0,     # Flag_Privilege_Escalation
    0,     # Flag_DoS
    0,     # Flag_Directory_Traversal
]])

predicted_cvss = model.predict(X_new)
print(f"Predicted CVSS Score: {predicted_cvss[0]:.2f}")
# → Predicted CVSS Score: 7.21

# ── Load GRU (Best DL) — requires scaling ────────────────────────────────────
scaler    = joblib.load("saved_models/scaler_standard.pkl")
gru_model = joblib.load("saved_models/model_gru.pkl")

X_scaled  = scaler.transform(X_new)   # scale using training-set fitted scaler
pred_gru  = gru_model.predict(X_scaled)
print(f"GRU Predicted CVSS:   {pred_gru[0]:.2f}")
```

---

<a id="future-roadmap"></a>
## 🔮 Future Roadmap

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:6A369B,33:FF1493,66:FFE500,100:00E5FF"/>
</p>

| Priority | Improvement | Expected Impact |
|---|---|---|
| 🔴 HIGH | **NLP / SecBERT Embeddings** — encode CVE description text using SecBERT (768-dim) | Significant accuracy boost; captures semantic meaning beyond binary flags |
| 🔴 HIGH | **SHAP Explainability** — per-prediction feature attributions | Enables deployment to security analysts who need to justify predictions |
| 🟠 MED | **Bidirectional LSTM (BiLSTM)** — process temporal CVE sequences in both directions | Richer temporal feature encoding; better handling of publication date signals |
| 🟠 MED | **CVSS v4.0 Support** — extend pipeline for Oct 2023 scoring standard | Adds Threat & Environmental metrics; future-proofs the pipeline |
| 🟠 MED | **FastAPI Deployment** — wrap Extra Trees / GRU in a REST API endpoint | Real-time CVSS prediction at vulnerability disclosure time |
| 🟡 LOW | **SMOTE Class Balancing** — over-sample CRITICAL (8.8%) and LOW (4.1%) | Improved prediction accuracy for rare but high-impact CVE categories |
| 🟡 LOW | **MLflow + Drift Monitoring** — experiment tracking and distribution-shift alerts | Production-grade MLOps for continuous retraining on new NVD data |
| 🟡 LOW | **CWE Category Integration** — map each CVE to its CWE root-cause weakness type | Finer-grained vulnerability type signal beyond binary attack-type flags |

---

<a id="disclaimer"></a>
## ⚠️ Disclaimer

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:FF1493,50:FFE500,100:FF1493"/>
</p>

> This project was developed as a **Master's Research Assignment** for the module **Applied Machine Learning (CMP7239)** at **Birmingham City University**, Academic Year 2025–26, under the supervision of **Dr Mohamed Ihmeida**.

- This repository is intended **solely for academic and educational purposes**.
- The CVSS predictions made by these models should **not** be used as a substitute for professional security assessments.
- All CVE data is sourced from the publicly available [National Vulnerability Database (NVD)](https://nvd.nist.gov/), maintained by the U.S. National Institute of Standards and Technology (NIST).
- The trained model files (`.pkl`) are provided for reproducibility purposes. Always verify model predictions against official NVD CVSS scores before making security decisions.
- The dataset file (`NVD_Cybersecurity_Dataset.csv`, ~340 MB) is **not included** in this repository. Contact via GitHub Issues if you need access.

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:05070F,20:0D1B2A,40:1F4E79,60:2E75B6,80:00E5FF,100:05070F&section=footer&text=Made%20with%20%F0%9F%94%90%20by%20Nisarg%20Chasmawala%20(HEAVEN)&fontSize=22&fontAlignY=65&fontColor=00E5FF&animation=twinkling"/>
</p>

<p align="center">
<strong>⭐ If this project helped you, please give it a star on GitHub!</strong>
</p>
