---
annotations_creators:
- expert-generated
language_creators:
- expert-generated
language:
- en
license:
- mit
multilinguality:
- monolingual
size_categories:
- n<1K
source_datasets:
- original
task_categories:
- tabular-regression
- tabular-classification
task_ids:
- tabular-regression
- tabular-classification
pretty_name: Bio-Slurry Methane Emission Dataset
tags:
- methane-emission
- agriculture
- environment
- machine-learning
- ensemble-learning
- stacking-regressor
- climate-change
dataset_info:
  features:
  - name: feature_1
    dtype: float32
  - name: feature_2
    dtype: float32
  - name: feature_3
    dtype: float32
  - name: feature_4
    dtype: float32
  - name: emission_level
    dtype:
      class_label:
        names:
          '0': Low
          '1': Medium
          '2': High
---

# Bio-Slurry Methane Emission Dataset

## 📄 Description

This dataset is the official data source for the research paper **"Predictive and Economic Assessment of Methane Emissions from Bio-Slurry Amended Systems using Ensemble Machine Learning"**, accepted at **STI 2025** (*Awaiting Publication*).

It contains experimental data designed to predict methane emissions from bio-slurry amended agricultural systems. The dataset supports both **regression** (predicting exact emission values) and **classification** (categorizing emissions into Low, Medium, and High levels) tasks. It serves as a valuable resource for researchers working on environmental sustainability and climate change mitigation through machine learning.

## 🚀 Quick Start

You can easily load this dataset using the Hugging Face `datasets` library:

```python
from datasets import load_dataset

# Load the dataset
dataset = load_dataset("musfiqurtuhin/bioslurry-methane-emission")

# View the first example
print(dataset['train'][0])
```

## 🔗 Associated Resources

*   **GitHub Repository:** [BioSlurry-Methane-Emission-Prediction](https://github.com/MusfiqurTuhin/BioSlurry-Methane-Emission-Prediction)
*   **Kaggle Dataset:** [Bio-Slurry Methane Emission Dataset](https://www.kaggle.com/datasets/musfiqurtuhin/bio-slurry-methane-emission-dataset)

## 📊 Dataset Statistics

*   **Total Samples:** 350
*   **Preprocessing:** Outliers removed using IQR method.
*   **Tasks:** Regression, Classification (3 classes)

## 🤝 Citation

If you use this dataset, please cite it as follows:

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
