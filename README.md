 Breast Cancer Prediction using Naive Bayes

This project is a beginner-level machine learning implementation to classify breast cancer tumors as **benign** or **malignant** using the **Naive Bayes algorithm**.

The dataset is loaded from **Google Drive** and processed in **Google Colab** using Python and scikit-learn.



 Project Overview

*Dataset**: Breast Cancer data (CSV format)
  **Platform**: Google Colab
  **Model**: Gaussian Naive Bayes (from `sklearn`)
**Goal**: Predict whether a tumor is benign (non-cancerous) or malignant (cancerous)

 Files

| File | Description |
|------|-------------|
| `Breast_cancer_dataset.csv` | Dataset used for training/testing |
| `naive_bayes_breast_cancer.ipynb` | Colab notebook with full pipeline |
| `README.md` | Project documentation |


 Libraries Used

- `pandas` – Data manipulation
- `scikit-learn` – ML algorithms, preprocessing, evaluation
- `google.colab` – Google Drive integration



 Steps Performed

1. **Mounted Google Drive** to access the dataset.
2. **Loaded** and **cleaned** the dataset (handled missing values, encoded categorical features).
3. **Split** the dataset into training and testing sets.
4. **Trained** a Gaussian Naive Bayes classifier.
5. **Evaluated** the model using accuracy score, confusion matrix, and classification report.



 Model Performance

-  Good accuracy on the test set
-  Confusion matrix and classification report included for detailed evaluation


 Key Learnings

- How to load data from Google Drive in Colab
- Preprocessing for ML: handling missing values and encoding
- Training and testing a Naive Bayes classifier
- Evaluating classification models using scikit-learn



## 📊 Sample Output

