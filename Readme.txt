# Advanced ANN for Breast Cancer Classification

This project implements an **Advanced Artificial Neural Network (ANN)** to classify breast cancer using the **Breast Cancer dataset from scikit-learn**.  

## Features
- Dataset exploration and preprocessing
- Multi-layer ANN with ReLU activation
- Regularization (Dropout and L2)
- Model evaluation using Accuracy, Precision, Recall, and Confusion Matrix
- Training & validation curves
- Streamlit web app for interactive prediction

## Files
- `ANN_BreastCancer.ipynb` : Jupyter Notebook with full workflow
- `app.py` : Streamlit app for predictions
- `requirements.txt` : Python dependencies
- `.gitignore` : Git ignore file to avoid unnecessary uploads
- `ann_model.h5` : Trained ANN model
- `scaler.save` : Saved scaler for preprocessing

## How to Run
### Locally (Notebook)
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/breast_cancer_ann.git
   cd breast_cancer_ann
