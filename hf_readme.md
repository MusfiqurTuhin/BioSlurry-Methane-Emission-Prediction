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

This dataset is part of the research **"Predictive and Economic Assessment of Methane Emissions from Bio-Slurry Amended Systems using Ensemble Machine Learning"** (STI 2025). It contains data for predicting methane emissions from bio-slurry systems, supporting both regression and classification tasks.

## 🚀 Quick Start

```python
from datasets import load_dataset
dataset = load_dataset("musfiqurtuhin/bioslurry-methane-emission")
print(dataset['train'][0])
```

## 🔗 Associated Resources

*   **GitHub Repository:** [BioSlurry-Methane-Emission-Prediction](https://github.com/MusfiqurTuhin/BioSlurry-Methane-Emission-Prediction)
*   **Kaggle Dataset:** [Bio-Slurry Methane Emission Dataset](https://www.kaggle.com/datasets/musfiqurtuhin/bio-slurry-methane-emission-dataset)

## 🤝 Citation

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
