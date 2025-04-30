# Bank Fraud Detection Using Machine Learning

## Overview
This project applies various machine learning algorithms to detect fraudulent transactions in banking data. Using a real-world dataset, the notebook demonstrates how data preprocessing, feature engineering, and classification models can be used to identify fraudulent behavior with improved accuracy and interpretability.

## Features
- Exploratory Data Analysis (EDA)
- Feature encoding and selection
- Data splitting and model training
- Evaluation using confusion matrix, ROC-AUC, precision, recall, and F1-score
- Comparison of multiple ML models (e.g., Logistic Regression, Random Forest, etc.)

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## How to Use
1. Clone the repository or download the notebook.
2. Install required packages (see below).
3. Open `ML_bankfraud.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells in sequence to reproduce results.

## Setup Instructions
Install the required Python libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dataset
This notebook utilizes the [PaySim Synthetic Financial Dataset for Fraud Detection](https://www.kaggle.com/datasets/ealaxi/paysim1), which simulates mobile money transactions to help in the study of fraudulent behavior. The dataset includes features such as transaction type, amount, and a label indicating whether a transaction is fraudulent.

## Results
The models are evaluated based on classification metrics, with visualizations of performance and decision boundaries where applicable. The project highlights which model performs best in identifying fraudulent activity while minimizing false positives.

## License
This project is open-source and available under the MIT License.
