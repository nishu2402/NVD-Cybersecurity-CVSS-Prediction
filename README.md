# 🔐 NVD CYBERSECURITY - CVSS SEVERITY PREDICTION

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=320&color=0:05070F,15:0D1B2A,30:1F4E79,45:2E75B6,60:00E5FF,75:00FF88,90:FFE500,100:05070F&text=CYBERSECURITY%20SEVERITY%20PREDICTION&fontSize=40&fontAlignY=38&fontColor=ffffff&animation=twinkling&desc=Supervised%20ML%20Regression%20on%20337%2C705%20NVD%20CVE%20Records&descAlignY=65&descSize=18"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=26&duration=2500&pause=700&color=00E5FF&center=true&vCenter=true&width=1200&lines=Predicting+CVSS+Base+Score+from+CVE+Metadata;337%2C705+Records+%7C+80%2F20+Train%2FTest+Split;6+Feature+Selection+Methods+Applied;Gradient+Boosting+%E2%86%92+R%C2%B2+%3D+0.9989+%7C+MAE+%3D+0.033;Near-Perfect+Vulnerability+Severity+Prediction"/>
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=6&color=0:00E5FF,25:2E75B6,50:00FF88,75:FFE500,100:FF1493"/>
</p>

---

<div align="center">

  <p>
    <img src="https://img.shields.io/badge/Python-3.9+-00E5FF?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
    <img src="https://img.shields.io/badge/Best_Model-Gradient_Boosting-6A369B?style=for-the-badge&logo=apachespark&logoColor=white" alt="Gradient Boosting"/>
    <img src="https://img.shields.io/badge/R²_Score-0.9989-00FF88?style=for-the-badge&logo=databricks&logoColor=black" alt="R2 Score"/>
    <img src="https://img.shields.io/badge/Dataset-NVD_337K-FFE500?style=for-the-badge&logo=databricks&logoColor=black" alt="Dataset"/>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Records-337%2C705_CVEs-00E5FF?style=flat-square&logo=database&logoColor=black" alt="Records"/>
    <img src="https://img.shields.io/badge/Split-80%25_Train_%2F_20%25_Test-2E75B6?style=flat-square&logo=scikit-learn&logoColor=white" alt="Split"/>
    <img src="https://img.shields.io/badge/CV-5--Fold_CrossVal-00FF88?style=flat-square&logo=python&logoColor=black" alt="CV"/>
    <img src="https://img.shields.io/badge/MAE-0.033_on_0--10_scale-FFE500?style=flat-square&logo=apachespark&logoColor=black" alt="MAE"/>
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

### Nisarg Chasmawala (Shroff)

<div align="center">

| | Detail |
|---|---|
| 🎓 **University** | Birmingham City University |
| 📚 **Module** | Applied Machine Learning — CMP7239 |
| 🏅 **Level** | Level 7 (Postgraduate) |
| 🆔 **Student ID** | 25155511 |
| 📅 **Academic Year** | 2025 – 2026 |
| 👨‍🏫 **Module Leader** | Dr Mohamed Ihmeida |
| 📍 **Location** | Birmingham, England, UK |
| 🔗 **LinkedIn** | [linkedin.com/in/nisarg-chasmawala](https://www.linkedin.com/in/nisarg-chasmawala) |
| 🐙 **GitHub** | [github.com/nishu2402](https://github.com/nishu2402) |

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
- [🥇 Why Gradient Boosting Wins](#why-wins)
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

This project applies a **full supervised machine learning regression pipeline** to the National Vulnerability Database (NVD) to automatically predict **CVSS Base Scores** — the industry-standard severity metric used by security teams worldwide to prioritise vulnerability patching.

The complete dataset of **337,705 CVE records** (spanning 1988–2026) was used without sampling, split into **80% training (270,164 records)** and **20% testing (67,541 records)**. Six feature selection strategies and four regression algorithms were systematically applied and evaluated.

<div align="center">

| Metric | Value |
|---|---|
| 🗃️ **Total Records** | 337,705 CVE records |
| 🎯 **Target Variable** | CVSS Base Score (0.0 – 10.0) |
| 🔀 **Train / Test Split** | 80% / 20% (full dataset) |
| 🔁 **Cross-Validation** | 5-Fold K-Fold |
| 🏆 **Best R²** | 0.9989 (Gradient Boosting) |
| 📉 **Best MAE** | 0.0287 (Decision Tree) |
| 🗓️ **Coverage** | 1988 – 2026 (38 years) |
| ✅ **Missing Values** | Zero — dataset 100% complete |

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

**Our solution:** Train a machine learning regression model on 337,705 historical CVE records to predict the CVSS Base Score from structured metadata — achieving **R² = 0.9989** with **MAE = 0.033** (on a 0–10 scale) using Gradient Boosting. This means on average, the model predicts CVSS score to within **0.033 of the true value**.

```
CVE Metadata (13 features) ──▶ ML Regression Model ──▶ Predicted CVSS Score
     Impact_Score                  Gradient Boosting          e.g. 7.42
     Exploitability_Score              (n=150)               ±0.033 MAE
     Attack Type Flags              R² = 0.9989
     Text Length Features
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

<img width="8192" height="1716" alt="pipeline" src="https://github.com/user-attachments/assets/6e06ca6b-2d51-44a2-9f05-8a2df115348b" />


---

<a id="feature-selection"></a>
## 🔍 Dimensionality Reduction & Feature Selection Strategies

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:FFE500,50:6A369B,100:00E5FF"/>
</p>

Six complementary feature selection methods were applied. Using multiple methods ensures that no single method's bias affects the final feature set — only features robust across multiple approaches are retained.

### Method 1 — Pearson Correlation `[Filter]`
> Measures linear association between each feature and CVSS_Base_Score. Applied to the full 337,705-record dataset.

| Top Features | r | Observation |
|---|---|---|
| Impact_Score | 0.797 | ⭐ Dominant linear predictor |
| Exploitability_Score | 0.276 | Strong secondary predictor |
| Flag_RCE | 0.220 | Strongest attack-type flag |
| Flag_Buffer_Overflow | 0.159 | High-severity attack signal |
| Flag_XSS | 0.129 | Negative correlation (lower CVSS) |

### Method 2 — Mutual Information Regression `[Filter]`
> Captures both linear and non-linear dependencies. Runs on 100k-record sample.

**Key insight:** `Exploitability_Score` (MI=1.907) ranks *above* `Impact_Score` (MI=1.834) — reversing the Pearson ranking — revealing strong non-linear dependencies invisible to Pearson.

### Method 3 — Chi-Square Test `[Filter]`
> Tests statistical independence between each feature and CVSS score. All 13 features achieved **p < 0.001** — statistically significant associations confirmed.

### Method 4 — F-Regression / ANOVA `[Filter]`
> ANOVA F-test for linear coefficients. `Impact_Score` achieved **F-Score = 588,435** — over 21× larger than any other feature, confirming exceptional linear dominance.

### Method 5 — Recursive Feature Elimination `[Wrapper]`
> Iteratively eliminates weakest features using Linear Regression. Top 8 selected:
> `Exploitability_Score`, `Impact_Score`, `Word_Count`, `Char_Length`, `Publish_Year`, `Flag_XSS`, `Flag_SQLi`, `Flag_Directory_Traversal`

### Method 6 — Random Forest Gini Importance `[Embedded]`
> Tree-based embedded method. `Impact_Score` = **87.77%** of all Gini importance. `Exploitability_Score` = **12.21%**. Together they account for **~99.98%** of predictive importance.

### ✅ Final Selected Feature Set (13 Features)

```python
FEATURES = [
    "Exploitability_Score",       # CVSS sub-score — dominant predictor
    "Impact_Score",               # CVSS sub-score — primary predictor ⭐
    "Word_Count",                 # word count of CVE description
    "Char_Length",                # character length of description
    "Publish_Year",               # year of CVE publication
    "Publish_Month",              # month of CVE publication
    "Flag_XSS",                   # binary: Cross-Site Scripting
    "Flag_SQLi",                  # binary: SQL Injection
    "Flag_Buffer_Overflow",       # binary: Buffer Overflow
    "Flag_RCE",                   # binary: Remote Code Execution
    "Flag_Privilege_Escalation",  # binary: Privilege Escalation
    "Flag_DoS",                   # binary: Denial of Service
    "Flag_Directory_Traversal",   # binary: Directory Traversal
]
```

---

<a id="models-explained"></a>
## 🤖 Models Explained

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:427CBB,33:EF6A21,66:43795C,100:6A369B"/>
</p>

### 📏 Model 1 — Linear Regression
![Linear Regression](https://img.shields.io/badge/Linear_Regression-Baseline-427CBB?style=flat-square)

The canonical OLS baseline. Fits a weighted straight line through all 13 features. Provides the essential benchmark — any non-linear model must significantly outperform this to justify its complexity.

- **Objective:** Minimise `‖y − Xβ‖²` (Ordinary Least Squares)
- **Solution:** `β = (XᵀX)⁻¹Xᵀy` (closed-form — no hyperparameters)
- **Training Time:** ~9.6s on 270,164 records
- **Limitation:** Cannot capture the non-linear thresholds in the CVSS scoring formula

### 🌿 Model 2 — Decision Tree Regressor
![Decision Tree](https://img.shields.io/badge/Decision_Tree-depth%3D8-EF6A21?style=flat-square)

Recursively partitions the feature space using binary splits that minimise MSE. Captures non-linear thresholds naturally — e.g., `Impact_Score > 6.5 → HIGH severity`. Depth capped at 8 to balance expressiveness with generalisation.

- **Algorithm:** CART (Classification and Regression Trees)
- **Hyperparameters:** `max_depth=8`, `criterion='squared_error'`
- **Max Leaf Nodes:** 2⁸ = 256 (≈ 0.039 CVSS units per bucket)
- **Training Time:** ~1.7s

### 🌳 Model 3 — Random Forest Regressor
![Random Forest](https://img.shields.io/badge/Random_Forest-n%3D150-43795C?style=flat-square)

Builds 150 independent Decision Trees on bootstrap samples with random feature subsets at each split. Final prediction = arithmetic mean across all trees. Dramatically reduces variance versus any single tree.

- **Method:** Bagging + Random Subspace (max_features="sqrt" ≈ 4 features/split)
- **Hyperparameters:** `n_estimators=150`, `max_features='sqrt'`, `min_samples_leaf=2`, `n_jobs=-1`
- **Training Time:** ~1m 17s (parallel, all CPU cores)
- **Model Size on Disk:** 81,661 KB

### 🚀 Model 4 — Gradient Boosting Regressor ⭐ BEST
![Gradient Boosting](https://img.shields.io/badge/Gradient_Boosting-BEST-6A369B?style=flat-square)

Builds 150 shallow trees sequentially. Each tree corrects the residuals of the current ensemble via gradient descent in function space. Shrinkage (`lr=0.10`) and stochastic subsampling (`subsample=0.8`) provide implicit regularisation.

- **Update Rule:** `Fₘ(x) = Fₘ₋₁(x) + η · hₘ(x)` where `hₘ` fits the negative MSE gradient
- **Hyperparameters:** `n_estimators=150`, `learning_rate=0.10`, `max_depth=4`, `subsample=0.8`
- **Training Time:** ~1m 30s (sequential — cannot parallelise across trees)
- **Model Size on Disk:** 126 KB

---

<a id="metrics"></a>
## 📐 Metrics

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00FF88,50:00E5FF,100:FFE500"/>
</p>

All models were evaluated on the identical **67,541-record held-out test set** using three complementary metrics:

| Metric | Formula | Interpretation |
|---|---|---|
| **MAE** | `(1/n) Σ \|yᵢ − ŷᵢ\|` | Mean absolute error in CVSS score units. MAE=0.033 → average prediction is 0.033 points off on a 0–10 scale. **Lower is better.** |
| **RMSE** | `√[(1/n) Σ (yᵢ−ŷᵢ)²]` | Penalises large errors more heavily than MAE. **Lower is better.** |
| **R²** | `1 − [Σ(yᵢ−ŷᵢ)²/Σ(yᵢ−ȳ)²]` | Proportion of CVSS variance explained. R²=0.9989 → 99.89% of variance explained. **Higher is better.** |
| **CV R²** | Mean R² over 5 folds | Cross-validated R² on 80k training sub-sample. Guards against overfitting. **Higher (and tighter std.) is better.** |

---

<a id="complete-performance"></a>
## 🏆 Complete Performance

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:427CBB,33:EF6A21,66:43795C,100:6A369B"/>
</p>

> All models trained on **270,164 records (80%)** and evaluated on **67,541 held-out test records (20%)**. CV R² computed on 80,000-record sub-sample of training set using 5-Fold K-Fold.

| Model | MAE ↓ | RMSE ↓ | R² ↑ | CV R² (5-Fold) ↑ | Train Time |
|---|---|---|---|---|---|
| ![LR](https://img.shields.io/badge/-Linear_Regression-427CBB?style=flat-square) | 0.9332 | 1.1755 | 0.7634 | 0.7640 ± 0.0031 | 9.6s |
| ![DT](https://img.shields.io/badge/-Decision_Tree-EF6A21?style=flat-square) | **0.0287** | 0.0829 | 0.9988 | 0.9989 ± 0.0002 | 1.7s |
| ![RF](https://img.shields.io/badge/-Random_Forest-43795C?style=flat-square) | 0.0505 | 0.1115 | 0.9979 | 0.9949 ± 0.0002 | 1m 17s |
| ![GB](https://img.shields.io/badge/-Gradient_Boosting_★-6A369B?style=flat-square) | 0.0331 | **0.0789** | **0.9989** | **0.9989 ± 0.0002** | 1m 30s |

> ⭐ **Gradient Boosting achieves the best overall score:** highest R² (0.9989), lowest RMSE (0.0789), and tightest CV variance (±0.0002) — confirming both accuracy and robustness.

---

<a id="why-wins"></a>
## 🥇 Why Gradient Boosting Wins

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:6A369B,50:FFE500,100:00FF88"/>
</p>

```
Why not Linear Regression?
  → R² = 0.763 confirms CVSS scoring is non-linear.
  → MAE = 0.933 means ~1 full CVSS point error on average.
  → Unacceptable for HIGH/CRITICAL boundary decisions (thresholds at 7.0 and 9.0).

Why not Decision Tree alone?
  → Best MAE (0.0287) but high variance — a single tree is sensitive to data perturbations.
  → No regularisation mechanism to prevent overfitting on new CVE distributions.

Why not Random Forest?
  → Excellent (R²=0.9979) but slightly lower accuracy than Gradient Boosting.
  → Memory-intensive: 81,661 KB vs. Gradient Boosting's 126 KB on disk.
  → CV R² of 0.9949 vs. 0.9989 — weaker generalisation on unseen data.

Why Gradient Boosting wins:
  ✅  Highest test-set R²   (0.9989) — explains 99.89% of CVSS variance
  ✅  Lowest RMSE           (0.0789) — fewest large prediction errors
  ✅  Tightest CV variance  (±0.0002) — most consistent across 5 folds
  ✅  Smallest model file   (126 KB)  — lightweight for deployment
  ✅  Shrinkage (lr=0.10)  — implicit regularisation via learning rate
  ✅  Stochastic subsampling (80%) — reduces overfitting risk further
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
├── 📓 NVD_Cybersecurity.ipynb             ← Google Colab notebook (14 cells, fully documented)
├── 🐍 nvd_cybersecurity.py                ← Complete standalone Python pipeline script
│
├── 📊 output_figures/                     ← All 16 generated charts (PNG, 160 DPI)
│   ├── fig01_cvss_distribution.png        ← Target variable distribution
│   ├── fig02_severity_pie.png             ← Severity class proportions
│   ├── fig03_cves_per_year.png            ← CVE temporal trend 2000–2026
│   ├── fig04_attack_flags.png             ← Attack type flag counts
│   ├── fig05_avg_cvss_severity.png        ← Mean CVSS by severity (±1 SD)
│   ├── fig06_correlation_heatmap.png      ← Pearson correlation matrix
│   ├── fig07_mutual_information.png       ← Mutual Information scores
│   ├── fig08_chi_square.png               ← Chi-Square significance chart
│   ├── fig09_rfe_ranking.png              ← RFE feature rankings
│   ├── fig10_rf_importance.png            ← Random Forest Gini importance
│   ├── fig11_fs_heatmap.png               ← Multi-method FS heatmap
│   ├── fig12_fs_grouped_bar.png           ← Multi-method FS bar comparison
│   ├── fig13_model_comparison.png         ← MAE/RMSE/R² comparison bars
│   ├── fig14_actual_vs_predicted.png      ← Actual vs. predicted scatter (4 models)
│   ├── fig15_residuals.png                ← Residual distributions (4 models)
│   └── fig16_cv_boxplot.png               ← 5-Fold CV R² boxplot
│
└── 💾 saved_models/                       ← Trained model files (joblib)
    ├── model_linear_regression.pkl        ← Linear Regression     (  1 KB)
    ├── model_decision_tree.pkl            ← Decision Tree         ( 10 KB)
    ├── model_gradient_boosting.pkl        ← Gradient Boosting ★  (126 KB)
    └── model_metadata.json                ← Training config + metrics
```

---

<a id="installation"></a>
## 🚀 Installation

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:00FF88,50:00E5FF,100:FFE500"/>
</p>

### Prerequisites

```bash
Python 3.9+
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
scikit-learn>=1.1.0
joblib>=1.2.0
```

</details>

### 3. Add the Dataset

> Download `NVD_Cybersecurity_Dataset.csv` and place it in the project root directory (same folder as the `.py` script).

### 4a. Run the Full Pipeline (Script)

```bash
python nvd_cybersecurity.py
```

**Expected output:**
```
══════════════════════════════════════════════════════════════════════
  NVD CYBERSECURITY — CVSS BASE SCORE PREDICTION
  Master's Research Assignment
══════════════════════════════════════════════════════════════════════
  Dataset : NVD_Cybersecurity_Dataset.csv
  Shape   : 337,705 rows × 19 columns
  Memory  : 339.8 MB
  ...
  PIPELINE COMPLETE — MASTER'S ASSIGNMENT
══════════════════════════════════════════════════════════════════════
```

### 4b. Run in Google Colab (Notebook)

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `NVD_Cybersecurity_Colab.ipynb`
3. Upload `NVD_Cybersecurity_Dataset.csv` via the folder icon → upload button
4. Run all cells top to bottom with **Shift + Enter**

### 5. Load a Saved Model for Inference

```python
import joblib
import pandas as pd

# Load the best-performing model
model = joblib.load("saved_models/model_gradient_boosting.pkl")

# Define the 13 features (in correct order)
features = [
    "Exploitability_Score", "Impact_Score", "Word_Count", "Char_Length",
    "Publish_Year", "Publish_Month", "Flag_XSS", "Flag_SQLi",
    "Flag_Buffer_Overflow", "Flag_RCE", "Flag_Privilege_Escalation",
    "Flag_DoS", "Flag_Directory_Traversal"
]

# Predict on new CVE data
X_new = pd.DataFrame([{
    "Exploitability_Score": 3.9,
    "Impact_Score": 10.0,
    "Word_Count": 27,
    "Char_Length": 158,
    "Publish_Year": 2024,
    "Publish_Month": 6,
    "Flag_XSS": 0,
    "Flag_SQLi": 0,
    "Flag_Buffer_Overflow": 1,
    "Flag_RCE": 0,
    "Flag_Privilege_Escalation": 0,
    "Flag_DoS": 0,
    "Flag_Directory_Traversal": 0
}])

predicted_cvss = model.predict(X_new[features])
print(f"Predicted CVSS Score: {predicted_cvss[0]:.2f}")
# → Predicted CVSS Score: 7.21
```

---

<a id="future-roadmap"></a>
## 🔮 Future Roadmap

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:6A369B,33:FF1493,66:FFE500,100:00E5FF"/>
</p>

| Priority | Improvement | Expected Impact |
|---|---|---|
| 🔴 HIGH | **NLP / BERT Embeddings** — encode full CVE description text using SecBERT | Significant accuracy boost; captures semantic meaning beyond binary flags |
| 🔴 HIGH | **SHAP Explainability** — per-prediction feature attributions | Enables deployment to security analysts who need to explain predictions |
| 🟠 MED | **XGBoost / LightGBM** — optimised gradient boosting frameworks | 10× faster training, better regularisation, lower memory footprint |
| 🟠 MED | **CVSS v4.0 Support** — extend pipeline for Oct 2023 scoring standard | Adds Threat & Environmental metrics; future-proofs the pipeline |
| 🟠 MED | **REST API Deployment** — wrap Gradient Boosting in FastAPI endpoint | Real-time CVSS prediction at vulnerability disclosure time |
| 🟡 LOW | **SMOTE Class Balancing** — over-sample CRITICAL (8.8%) and LOW (4.1%) | Improved prediction accuracy for rare but high-impact CVE categories |
| 🟡 LOW | **MLflow + Drift Monitoring** — experiment tracking and distribution-shift alerts | Production-grade MLOps for continuous retraining |
| 🟡 LOW | **CWE Integration** — map each CVE to its CWE category as a feature | Finer-grained vulnerability type signal than binary flags |

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
- **The `model_random_forest.pkl` file (~82 MB). I can able to upload if you want contact me I'll share you**

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:05070F,20:0D1B2A,40:1F4E79,60:2E75B6,80:00E5FF,100:05070F&section=footer&text=Made%20with%20%F0%9F%94%90%20by%20Nisarg%20Chasmawala&fontSize=22&fontAlignY=65&fontColor=00E5FF&animation=twinkling"/>
</p>

<p align="center">
<strong>⭐ If this project helped you, please give it a star on GitHub!</strong>
</p>
