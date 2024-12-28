# Project Descriptions

This repository contains machine learning and data preprocessing projects created for different purposes, including internships and hackathons. Below is a detailed overview of each project:

## 1. Breast Cancer Prediction
**Purpose**: 
Developed for an internship at [ADVERK Technologies](https://adverk.net/), this notebook focuses on predicting the presence of breast cancer using Naive Bayes Classifier.

### Key Features:
- **Libraries Used**: 
  - `numpy`, `pandas`, `seaborn`, `matplotlib.pyplot`
  - `sklearn` modules: `preprocessing`, `model_selection`, `metrics`, `naive_bayes`
- **Workflow**:
  1. Load breast cancer data using `datasets`.
  2. Preprocess numerical features.
  3. Split the dataset into training and testing subsets.
  4. Apply `RobustScaler` for scaling.
  5. Train and evaluate a Gaussian Naive Bayes classifier.

---

## 2. Product Confirmer ML
**Purpose**: 
Developed for the Indian Government's "Dark Patterns Buster Hackathon," this notebook predicts the usability or validation of a product based on various attributes.

### Key Features:
- **Libraries Used**: 
  - `pandas`, `category_encoders`, `joblib`, `graphviz`, `pickle`
  - `sklearn` modules: `ensemble`, `metrics`, `model_selection`, `tree`
- **Workflow**:
  1. Load and preprocess product data, filling missing values with appropriate defaults.
  2. Encode categorical features using `OneHotEncoder`.
  3. Train a Random Forest Classifier.
  4. Test the model and evaluate its accuracy.
  5. Save the trained model using `pickle` and `joblib` for reuse.

---

## 3. Stroke Prediction
**Purpose**: 
Developed for an internship at [ADVERK Technologies](https://adverk.net/), this project aims to predict the likelihood of a stroke based on patient data using Decision Tree.

### Key Features:
- **Libraries Used**:
  - `pandas`, `numpy`, `category_encoders`, `graphviz`
  - `sklearn` modules: `model_selection`, `metrics`, `tree`
- **Workflow**:
  1. Load healthcare dataset.
  2. Handle missing values and preprocess categorical data using `OrdinalEncoder`.
  3. Train a Decision Tree Classifier with Gini Impurity.
  4. Evaluate the model and visualize decision trees using `graphviz`.

---

## Repository Structure
- **`Breast cancer.ipynb`**: Notebook for breast cancer prediction.
- **`ProductconfirmerML.ipynb`**: Notebook for product confirmation model.
- **`Strokefinding.ipynb`**: Notebook for stroke prediction.

---

## Requirements
Install the necessary libraries using the following command:
For Windows Command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn category_encoders graphviz joblib
```
For Jupyter Notebook:
```bash
!pip install numpy pandas matplotlib seaborn scikit-learn category_encoders graphviz joblib
```
---

## How to Use
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the desired notebook using Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook <notebook-name>.ipynb
   ```
3. Follow the workflow described within each notebook.

---

## Acknowledgments
- **ADVERK Technologies**: For providing the opportunity to work on real-world machine learning problems.
- **Indian Government**: For organizing the "Dark Patterns Buster Hackathon," inspiring innovative solutions like Product Confirmer ML.

---

Feel free to explore and modify the projects as needed. Contributions are welcome!
