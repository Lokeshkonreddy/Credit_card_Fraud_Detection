# 🔒 FraudShield: KNN-Based Credit Card Fraud Detection

## 📌 Project Overview
FraudShield is a **Credit Card Fraud Detection** system that applies the **K-Nearest Neighbors (KNN) algorithm** to identify fraudulent transactions. The model analyzes transaction patterns, detects anomalies, and helps prevent financial fraud by distinguishing between genuine and suspicious transactions.

## 🚀 Features
- **Data Preprocessing**: Cleans and structures transaction data for efficient analysis.
- **Fraud Detection Model**: Implements the KNN algorithm for anomaly detection.
- **Feature Engineering**: Extracts meaningful transaction attributes to enhance model accuracy.
- **Performance Evaluation**: Assesses model effectiveness using precision, recall, and F1-score.
- **Visualization**: Graphical insights into fraud trends and model performance.

## 📊 Technologies Used
- Python
- Pandas & NumPy
- Scikit-Learn (KNN Algorithm)
- Matplotlib & Seaborn
- Jupyter Notebook

## 🎯 Use Cases
- **Banking & Finance**: Detect fraudulent transactions and enhance security measures.
- **E-commerce**: Prevent online payment fraud and reduce chargeback losses.
- **Cybersecurity**: Strengthen fraud prevention systems in digital transactions.

## 🔧 Installation & Usage
### Prerequisites
Ensure you have Python installed. Install required dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
### Running the Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/HareenaChowdary/FraudShield_KNN-Based-Credit-Card-Fraud-Detection.git
   ```
2. Navigate to the project folder:
   ```bash
   cd FraudShield_KNN-Based-Credit-Card-Fraud-Detection
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the provided notebook to process data and train the KNN fraud detection model.

## 📈 Results & Insights
- Accurate fraud detection with high precision and recall.
- Fraud trends visualization for better risk assessment.
- Business-driven insights for enhancing fraud prevention strategies.

📂 Dataset

The dataset is from Kaggle:
[creditcard.csv](https://www.kaggle.com/code/maneesha96/fraud-detection-in-transaction-data-using-knn/input)

- **Source:** This dataset contains credit card transactions made by European customers over two days in September 2013.
  
- **Size:** 284,807 transactions; 30 features (V1-V28, Time, Amount).
  
- **Features:**
  
   **V1-V28:** Anonymized via PCA.
  
   **Time:** Seconds since the first transaction.
  
   **Amount:** Transaction value.
  
- **Target Variable:**
  
   **Class:** 1 (fraudulent) or 0 (non-fraudulent).

### 🌱 Contributing
Contributions are always welcome! If you have suggestions, fixes, or features to add, please fork the repository and create a pull request. You can also open an issue to report bugs or request new features.
