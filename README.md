# 🔬 Glass Type Classification with Machine Learning

A machine learning project to classify different types of glass based on their **chemical composition and refractive index**.

## Project Overview

Glass identification is particularly important in **forensic science**, where glass fragments can provide valuable evidence.

This project uses the **UCI Glass Identification Dataset** to analyse glass properties and compare two supervised machine learning algorithms: **Gaussian Naive Bayes** and **Decision Tree Classifier**.

## Dataset

- **Source:** [UCI Machine Learning Repository – Glass Identification](https://archive.ics.uci.edu/dataset/42/glass+identification)
- **Samples:** 214
- **Features:** 9 numerical features
- **Target:** Glass Type (6 classes)
- **Missing Values:** None

## Project Workflow

1. Data Loading and Exploration
2. Exploratory Data Analysis (EDA)
3. Feature and Target Selection
4. Train-Test Split (80/20)
5. Model Training and Prediction
6. Model Evaluation
7. Results and Conclusion

## Machine Learning Models

- Gaussian Naive Bayes
- Decision Tree Classifier

## Model Performance

| Model | Accuracy |
|---|---:|
| Gaussian Naive Bayes | 55.81% |
| **Decision Tree Classifier** | **72.09%** |

The Decision Tree achieved a **weighted F1-score of approximately 0.70**, outperforming Gaussian Naive Bayes on the test set.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Open `glass_type_classification.ipynb` in Jupyter Notebook.
4. Run all cells in order.

Make sure the `glass.csv` dataset is located in the same folder as the notebook.

## Future Improvements

- Cross-validation
- Hyperparameter tuning
- Further analysis of class imbalance
- Comparison with additional classification algorithms

## Dataset Reference

German, B. (1987). *Glass Identification*. UCI Machine Learning Repository.

https://doi.org/10.24432/C5WW2P