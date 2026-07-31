# ml-intrusion-detection
Machine learning-based intrusion detection system using CIC-IDS dataset, that classifies network traffic into benign or malicious categories such as DDoS, PortScan, Dos attacks, etc. The system uses supervised learning models to detect and classify network attacks.

## Features
- Data preprocessing and cleaning of large-scale network traffic data
- Handling class imbalance using weighted training
- Model training using:
    - Random Forest
    - XGBoost
- Performance evaluation using:
    - Confusion matrix
    - Classification Report
    - Macro F1 Score
- Model Comparison and best model selection
- Model serialization using Joblib

## Technologies used
- Python
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Google Colab

## Dataset
- CIC-IDS / Network Intrusion dataset from Kaggle
- Contains multiple types of network attacks and benign traffic

## Workflow
1. Data Collection from Kaggle
2. Data Cleaning (NaN, Infinite values, duplicates)
3. Feature Scaling using StandardScaler
4. Label Encoding
5. Train-Test Split (stratified)
6. Model Training
7. Evaluation and Comparison 
8. Model Saving

## Results
- Achieved strong performance on multi-class classification
- Macro F1-score used for fair evaluation across imbalanced classes
- XGBoost and Random Forest compared for optimal performance
