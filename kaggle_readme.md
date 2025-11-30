# Bio-Slurry Methane Emission Dataset

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

## 📄 Context

This dataset was collected for the research paper **"Predictive and Economic Assessment of Methane Emissions from Bio-Slurry Amended Systems using Ensemble Machine Learning"**, accepted at **STI 2025**. It aims to facilitate the development of machine learning models for predicting methane emissions from agricultural bio-slurry systems, which is crucial for environmental impact assessment and management.

## 🔗 Associated Resources

*   **GitHub Repository:** [BioSlurry-Methane-Emission-Prediction](https://github.com/MusfiqurTuhin/BioSlurry-Methane-Emission-Prediction)
*   **Hugging Face Dataset:** [bioslurry-methane-emission](https://huggingface.co/datasets/musfiqurtuhin/bioslurry-methane-emission)
*   **Paper:** *Awaiting Publication (STI 2025)*

## 💾 Dataset Specifications

The dataset contains experimental data on methane emissions.

*   **Rows:** 350 (Cleaned)
*   **Task:** Regression (Emission amount) & Classification (Emission level: Low, Medium, High)
*   **Format:** CSV

## 🧠 Benchmarks

The dataset has been benchmarked using various machine learning models. The **Stacking Regressor** achieved the best performance with an **R² score of 0.6663**.

| Model | R² Score |
| :--- | :--- |
| **Stacking Regressor** | **0.6663** |
| Random Forest | 0.6546 |
| Linear Regression | 0.6485 |
| CatBoost | 0.6415 |

## 🤝 Citation

If you use this dataset in your research, please cite:

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
