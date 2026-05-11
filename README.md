# Analyzing Antenatal Care Utilization and Socioeconomic Disparities among Pregnant Women in Nepal Based on DHS 2022 Data

## Project Overview

This project analyzes antenatal care (ANC) utilization and socioeconomic disparities among pregnant women in Nepal using the Nepal Demographic and Health Survey (NDHS) 2022 dataset.

The study focuses on identifying inequalities in maternal healthcare access based on education level, wealth index, ethnicity, district, and other socioeconomic factors. Statistical analysis, clustering techniques, and machine learning models were used to identify patterns and predict maternal healthcare utilization.

---

## Objectives

* Identify groups of pregnant women accessing antenatal healthcare services.
* Analyze socioeconomic disparities affecting ANC utilization.
* Perform clustering analysis to classify maternal healthcare groups.
* Apply machine learning models for predictive analysis.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* SciPy
* OpenPyXL

---

## Methods Used

### Data Preprocessing

* Data cleaning
* Variable selection
* Binary recoding
* Feature categorization

### Clustering Techniques

* Hierarchical Clustering
* Ward’s Method
* Elbow Method
* Silhouette Analysis

### Statistical Analysis

* Cross-tabulation
* Chi-Square Test

### Machine Learning

* Decision Tree
* XGBoost Classification
* Cross Validation
* Permutation Feature Importance

---
---

## Main Python Files

| File Name                | Description                             |
| ------------------------ | --------------------------------------- |
| `data_clean.py`          | Cleans and preprocesses dataset         |
| `ratio_calculations.py`  | Performs ratio calculations             |
| `clustering.py`          | Main clustering implementation          |
| `elbow_method.py`        | Finds optimal cluster number            |
| `silhouette_method.py`   | Evaluates clustering quality            |
| `wards_method.py`        | Performs hierarchical clustering        |
| `chi_square_analysis.py` | Performs chi-square testing             |
| `crosstab_analysis.py`   | Performs cross-tabulation analysis      |
| `decision_tree.py`       | Decision tree classification            |
| `xgboost_category.py`    | XGBoost classification model            |
| `cross_validation.py`    | Model evaluation using cross-validation |
| `permutation_test.py`    | Permutation feature importance          |

---

## Dataset

The project uses NDHS 2022 data focused on women aged 15–49 years who had a live birth within the last five years.

---

## Key Findings

* Two major maternal care groups were identified:

  * Good Maternal Care Group
  * Low Maternal Care Group

* Education level, wealth index, district, ethnicity, and husband occupation significantly influenced ANC utilization.

* XGBoost achieved approximately 88% classification accuracy.

---

## How to Run

Install required libraries:

```bash
pip install -r requirements.txt
```

Run Python scripts:

```bash
python scripts/clustering/clustering.py
```

---

## Future Improvements

* Add dashboard visualization
* Improve predictive modeling
* Include postnatal and delivery care analysis
* Deploy web-based analytics system

---
