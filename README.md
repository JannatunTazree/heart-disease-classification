# Heart Disease Classification

Machine learning project for classifying heart disease using the `heart_2020_cleaned.csv` dataset.

# Data Source

Kaggle Indicators of Heart Disease Dataset: (https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)

## Repository structure

```text
heart-disease-classification/
├── data/
│   └── heart_2020_cleaned.csv
├── notebooks/
│   └── heart_disease_classification_JT_15202606.ipynb
├── outputs/
├── .gitignore
├── requirements.txt
└── README.md
```

## Project overview

This notebook performs exploratory data analysis and compares multiple classification models for heart disease prediction. The workflow includes:

- Loading and inspecting the dataset
- Checking target variable balance
- Exploring numerical and categorical features
- Encoding categorical variables and scaling numerical variables
- Splitting the dataset into train and test sets
- Training and evaluating machine learning classifiers
- Saving model comparison outputs

## Models included

The notebook includes experiments with:

- Support Vector Classifier approach using `SGDClassifier` and `RBFSampler`
- K-Nearest Neighbors
- Gaussian Naive Bayes

## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/JannatunTazree/heart-disease-classification.git
cd heart-disease-classification
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook notebooks/heart_disease_classification_JT_15202606.ipynb
```

## Dataset

The dataset file is included at:

```text
data/heart_2020_cleaned.csv
```

The notebook uses this relative path, so it should run correctly after cloning the repository.

## Notes

Generated files such as model comparison CSV/JSON outputs are saved in the `outputs/` folder. The folder is kept in the repository with a `.gitkeep` file, while generated contents are ignored by Git.
