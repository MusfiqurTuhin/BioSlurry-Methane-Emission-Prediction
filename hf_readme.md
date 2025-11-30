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
- tabular-single-column-regression
- tabular-multi-class-classification
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

## � Dataset Structure

### Data Instances

A typical data point consists of physicochemical parameters of the bio-slurry system and the corresponding methane emission level.

```json
{
  "feature_1": 0.5,
  "feature_2": 1.2,
  "feature_3": 0.8,
  "feature_4": 0.3,
  "emission_level": 1
}
```

### Data Fields

| Field Name | Type | Description |
| :--- | :--- | :--- |
| `feature_1` | `float32` | Physicochemical parameter 1 (e.g., pH, Temperature) |
| `feature_2` | `float32` | Physicochemical parameter 2 |
| `feature_3` | `float32` | Physicochemical parameter 3 |
| `feature_4` | `float32` | Physicochemical parameter 4 |
| `emission_level` | `class_label` | Categorized emission level: `0` (Low), `1` (Medium), `2` (High) |

## 📊 Dataset Statistics

*   **Total Samples:** 350
*   **Preprocessing:** Outliers removed using IQR method.
*   **Tasks:** Regression, Classification (3 classes)

## �🔗 Associated Resources

*   **GitHub Repository:** [BioSlurry-Methane-Emission-Prediction](https://github.com/MusfiqurTuhin/BioSlurry-Methane-Emission-Prediction)
*   **Kaggle Dataset:** [Bio-Slurry Methane Emission Dataset](https://www.kaggle.com/datasets/musfiqurtuhin/bio-slurry-methane-emission-dataset)

## ⚠️ Considerations for Using the Data

### Social Impact of Dataset

This dataset contributes to the understanding of greenhouse gas emissions from agricultural practices. Better prediction models can lead to more effective mitigation strategies, positively impacting climate change efforts.

### Discussion of Biases

The data is collected from specific experimental setups and may not fully represent all global bio-slurry systems. Users should consider the geographical and experimental context when generalizing findings.

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

## 📬 Contact

For questions or feedback, please contact: **Md. Musfiqur Rahman**
