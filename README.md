# A Robust Unsupervised Ensemble Pipeline with Explainable AI for Stellar Anomaly Detection in GAIA DR3

## Project Overview

This project focuses on anomaly detection in stellar data using a hybrid ensemble machine learning approach. The dataset is preprocessed, cleaned, and enhanced through feature engineering before applying multiple unsupervised learning algorithms to identify unusual stellar observations. The project also compares clustering performance using different evaluation metrics and provides an interactive interface for prediction.

## Objectives

- Clean and preprocess Gaia stellar dataset
- Perform feature engineering
- Analyze stellar data using visualizations
- Reduce dimensionality using PCA
- Detect anomalies using ensemble machine learning models
- Compare clustering performance using multiple evaluation metrics
- Deploy a simple prediction interface using Gradio

## Dataset

The project uses the **Gaia Stellar Dataset** containing astronomical features such as:

- Right Ascension (RA)
- Declination (DEC)
- Parallax
- Proper Motion (PMRA, PMDEC)
- Radial Velocity
- G Magnitude
- BP Magnitude
- RP Magnitude

## Feature Engineering

The following new features were created:

- Color Index (BP − RP)
- Total Proper Motion
- Distance (Parsecs)
- Total Velocity

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Gradio

## Machine Learning Techniques

The project implements:

- Principal Component Analysis (PCA)
- K-Means Clustering
- Gaussian Mixture Model (GMM)
- Isolation Forest
- Local Outlier Factor (LOF)
- Ensemble-based Anomaly Detection

## Evaluation Metrics

The models are evaluated using:

- Silhouette Score
- Davies–Bouldin Index
- Calinski–Harabasz Score

## Project Structure

```
Stellar-Analysis/
│── FINAL_Stellar_Analysis.ipynb
│── README.md
│── requirements.txt
│── dataset.csv
```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/anikals375/Stellar-Analysis.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all notebook cells sequentially.

## Future Enhancements

- Improve ensemble learning techniques
- Integrate deep learning models for anomaly detection
- Deploy as a cloud-based web application
- Add real-time astronomical data support

## Author

**Anika L Shiriya**

Computer Science Engineering Student
