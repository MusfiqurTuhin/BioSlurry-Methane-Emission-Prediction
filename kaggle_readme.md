# Bio-Slurry Methane Emission Dataset

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-%23EB4034.svg?style=for-the-badge&logo=xgboost&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

## 📄 Context

Methane emissions from agricultural systems, particularly bio-slurry amended soils, are a significant contributor to greenhouse gases. This dataset was collected as part of the research paper **"Predictive and Economic Assessment of Methane Emissions from Bio-Slurry Amended Systems using Ensemble Machine Learning"**, accepted at **STI 2025** (*Awaiting Publication*).

The goal of this dataset is to enable the development of robust machine learning models that can accurately predict methane emission levels based on various physicochemical parameters of the bio-slurry systems. This can aid in developing strategies to mitigate emissions and improve environmental sustainability.

## 🔗 Associated Resources

*   **GitHub Repository:** [BioSlurry-Methane-Emission-Prediction](https://github.com/MusfiqurTuhin/BioSlurry-Methane-Emission-Prediction)
*   **Hugging Face Dataset:** [bioslurry-methane-emission](https://huggingface.co/datasets/musfiqurtuhin/bioslurry-methane-emission)
*   **Paper:** *Awaiting Publication (STI 2025)*

## 💾 Dataset Specifications

The dataset comprises experimental data collected from bio-slurry amended systems.

*   **Total Samples:** 350 (after preprocessing and outlier removal)
*   **Features:** Physicochemical parameters of the soil and slurry mixture.
*   **Target Variables:**
    *   **Regression:** Quantitative methane emission levels.
    *   **Classification:** Emission levels categorized into **Low**, **Medium**, and **High**.
*   **Format:** CSV

## 🧠 Benchmarks

We evaluated several machine learning models on this dataset using 5-Fold Cross-Validation. The **Stacking Regressor** demonstrated superior performance.

| Model | R² Score |
| :--- | :--- |
| **Stacking Regressor** | **0.6663** |
| Random Forest | 0.6546 |
| Linear Regression | 0.6485 |
| CatBoost | 0.6415 |
| LightGBM | 0.6029 |
| XGBoost | 0.5106 |

## 🤝 Citation

If you use this dataset in your research or projects, please cite the following:

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

For questions or feedback, please contact: **Md. Musfiqur Rahman**
