# Intrusion-Detection-System-IDS-using-ML
A multi-class IDS that detects Normal, DoS, Probe, R2L, and U2R network attacks using KDD99/UNSW-NB15 datasets. Built with Python and Random Forest, it includes data preprocessing, feature scaling, model evaluation, and exports results for Power BI dashboards. Demonstrates practical cybersecurity monitoring and ML-based threat detection skills.

## Project Overview
The **Intrusion Detection System (IDS) using Machine Learning** detects suspicious network activities and cyber attacks.  
It classifies network traffic into multiple categories:

- **Normal**  
- **DoS (Denial of Service)**  
- **Probe**  
- **R2L (Remote-to-Local)**  
- **U2R (User-to-Root)**  

The project combines **cybersecurity monitoring** with **ML techniques** to identify threats and anomalies.  
Results are exported as a **Power BI-ready CSV** for interactive dashboards.

---

## Key Features
- Multi-class attack detection: Normal, DoS, Probe, R2L, U2R  
- Random Forest Classifier: High-accuracy ML model  
- Confusion matrix & classification report  
- Top 10 feature importance visualization  
- CSV export for Power BI dashboards  
- Trained model saved as `.pkl` for reuse or deployment  

---

## Tech Stack
- **Python** – Programming and data manipulation  
- **Pandas / NumPy** – Data preprocessing & feature engineering  
- **Scikit-learn** – ML model building & evaluation  
- **Matplotlib / Seaborn** – Data visualization  
- **Power BI** – Dashboard and reporting  

---

## Dataset
- **KDD99** – [Download Link](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)  
- **UNSW-NB15 (Optional)** – [Download Link](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)  

**Attack Categories:**  
- DoS (Denial of Service)  
- Probe  
- R2L (Remote-to-Local)  
- U2R (User-to-Root)  
- Normal  

---

## Installation
1. Clone the repository

git clone <repo_url>
cd IDS-ML-Cybersecurity

2. Install dependencies:

pip install -r requirements.txt

3. Open Google Colab and run IDS_Colab_Notebook.ipynb.

---

## Usage

1. **Load & preprocess dataset** – Encode categorical features, scale numeric features.  
2. **Train the model** – Random Forest classifier for multi-class detection.  
3. **Evaluate the model** – Accuracy, classification report, confusion matrix.  
4. **Visualize results** – Feature importance & attack distribution.  
5. **Export predictions** – CSV file for Power BI dashboards: `IDS_PowerBI_Results.csv`.  
6. **Save trained model** – `ids_multiclass_model.pkl`.  

---

## Power BI Dashboard

- Import `IDS_PowerBI_Results.csv`  
- Visualize:  
  - Attack type distribution  
  - Confusion matrix  
  - Top 10 feature importance  

---

## Model Performance

- **Accuracy:** High multi-class classification using Random Forest  
- **Evaluation Metrics:** Precision, Recall, F1-Score for each attack type  
- **Confusion Matrix:** Shows correctly and incorrectly classified attacks  
- **Feature Importance:** Top features contributing to attack detection  

---

## Skills Highlighted

- Cybersecurity monitoring & threat detection  
- ML-based anomaly detection  
- Data preprocessing & feature engineering  
- Model evaluation & visualization  
- Dashboard reporting (Power BI)  

---

## Why This Project Stands Out

This project demonstrates **real-world application of cybersecurity and ML**, providing actionable insights for network threat detection.  
Ideal for portfolios and **MNC cybersecurity roles**.  

---

## Folder Structure

IDS-ML-Cybersecurity/
│
├── IDS_Colab_Notebook.ipynb # Notebook with full code & markdown explanations
├── requirements.txt # Python dependencies
├── IDS_PowerBI_Results.csv # Predictions for Power BI
├── ids_multiclass_model.pkl # Trained Random Forest model
├── README.md # Project description
└── datasets/ # Optional: KDD99 or UNSW-NB15 datasets

---

## License
This project is licensed under the **MIT License**.

---

## Author
VIDHI MISTRY
vidhimistry292@gmail.com.
