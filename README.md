# PDF Maliciousness Prediction Model

## Overview
This project develops a Machine Learning (ML) model to predict the maliciousness of PDF files, addressing the challenge of cybersecurity threats in commonly shared documents. The model is capable of distinguishing between benign and malicious PDF files with high precision and accuracy.

## Features
- **Machine Learning Models**: Uses XGBoost and RandomForest classifiers to analyze PDF files.
- **Feature Engineering**: Innovates with features such as `sus_domain_count` and `file_attachments_count` to enhance the model's predictive capabilities.
- **High Accuracy**: Achieves a 99% accuracy rate, with a 99% precision and F1-score, ensuring reliable identification with minimal false positives.

## Data
The dataset consists of 9,748 PDF files, labeled as benign or malicious, and covers 71 feature columns. Features include file characteristics, metadata, embedded URLs, and domain information extracted using open-source tools.

## Methodology
- **Feature Extraction**: Utilized open-source tools for rigorous feature extraction from PDFs.
- **Model Training and Testing**: Split the dataset into training (70%) and testing (30%) sets for model evaluation.
- **Cross-Validation**: Employed cross-validation methods to ensure robust model performance.

## Results
The model demonstrated exceptional performance:
- **Confusion Matrix Accuracy**: 1,493 True Positives (TP) and 1,422 True Negatives (TN).
- **Area Under Curve (AUC)**: Score of 1.00, indicating perfect classification capabilities.

## Visualizations
The repository includes visualizations such as feature importance graphs, confusion matrices, and ROC curves, offering insights into the model's decision-making process.

## Challenges
- Feature extraction complexity and reliance on accurate labeling of the training dataset.
- Limited testing to the provided dataset without the ability to validate on new, unseen files.

## Conclusion
The project emphasizes the importance of detailed data preprocessing, innovative feature engineering, and the use of powerful ML models to develop a reliable tool that enhances cybersecurity measures.

## Dependencies
- Python 3.8+
- NumPy
- Pandas
- scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Plotly

## Authors
- Amal Raj Singh
- Manasvi Logani
