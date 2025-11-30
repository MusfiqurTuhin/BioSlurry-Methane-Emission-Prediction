# Predictive and Economic Assessment of Methane Emissions from Bio-Slurry Amended Systems using Ensemble Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-%23EB4034.svg?style=for-the-badge&logo=xgboost&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

## 📄 Abstract

This repository contains the official implementation and dataset for the paper **"Predictive and Economic Assessment of Methane Emissions from Bio-Slurry Amended Systems using Ensemble Machine Learning"**, accepted at **STI 2025** (*Awaiting Publication*).

The study focuses on predicting methane emissions from bio-slurry amended systems using advanced ensemble machine learning techniques. By leveraging a dataset of 350 samples, we employed various regression and classification models, including Linear Regression, Random Forest, XGBoost, LightGBM, and CatBoost, along with a Stacking Regressor to achieve robust prediction performance.

## 🔗 Quick Links

*   **Paper:** *Awaiting Publication (STI 2025)*
*   **Kaggle Dataset:** [Bio-Slurry Methane Emission Dataset](https://www.kaggle.com/datasets/musfiqurtuhin/bio-slurry-methane-emission-dataset)
*   **Hugging Face Dataset:** [bioslurry-methane-emission](https://huggingface.co/datasets/musfiqurtuhin/bioslurry-methane-emission)

## 💾 Dataset Description

The dataset consists of **350 samples** (after preprocessing) collected to analyze methane emissions. It includes various physicochemical parameters of the bio-slurry systems.

*   **Total Samples:** 350
*   **Target Variable:** Methane Emission Levels (Regression & Classification)
*   **Format:** CSV

## 🧠 Methodology

We implemented a multi-stage machine learning pipeline:

1.  **Data Preprocessing:** Outlier removal (IQR method), feature scaling.
2.  **Model Selection:**
    *   **Regression:** Linear Regression, Random Forest, XGBoost, LightGBM, CatBoost.
    *   **Ensemble:** Stacking Regressor (combining base models for improved accuracy).
3.  **Classification:** Categorizing emission levels into Low, Medium, and High.

## 📊 Result Analysis

### Regression Performance (5-Fold CV)

| Model | R² Score |
| :--- | :--- |
| **Stacking Regressor** | **0.6663** |
| Random Forest | 0.6546 |
| Linear Regression | 0.6485 |
| CatBoost | 0.6415 |
| LightGBM | 0.6029 |
| XGBoost | 0.5106 |

### Classification Performance

*   **Accuracy:** 68%
*   **Precision/Recall:** Balanced across Low, Medium, and High classes.

## 📝 Citation

If you use this dataset or code, please cite the following:

```bibtex
@misc{md__musfiqur_rahman_2025,
	title={Bio-Slurry Methane Emission Dataset},
	url={https://www.kaggle.com/dsv/13932927},
	DOI={10.34740/KAGGLE/DSV/13932927},
	publisher={Kaggle},
	author={Md. Musfiqur Rahman},
	year={2025}
}
```

## 📬 Contact

For any queries, please contact: **Md. Musfiqur Rahman**
