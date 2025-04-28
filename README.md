# Thesis: Automated Investigation of Cyber Attacks Through Network Traffic Analysis (PCAPs)

This repository contains the implementation for the Master's thesis project focused on the automated detection of cyber attacks, particularly Distributed Denial of Service (DDoS) attacks, by analyzing network traffic captured in PCAP files.

The project applies machine learning techniques to identify anomalies and classify network traffic as benign or malicious, using supervised and unsupervised learning methods.

---

## 📂 Repository Structure

- **CLASSIFICATION/**  
  Contains Jupyter Notebooks for supervised classification models such as:
  - Random Forest
  - Support Vector Machine (SVM)
  - Gradient Boosting
  - Evaluation using metrics like Accuracy, Precision, Recall, and F1-Score.

- **ANOMALY DETECTION/**  
  Contains Jupyter Notebooks for unsupervised anomaly detection models such as:
  - Isolation Forest
  - One-Class SVM
  - Random Forest adapted for anomaly detection.

- **PRACTICE/**  
  Contains experimental and practice notebooks used for initial testing and validation of machine learning pipelines.

---

## ⚙️ Technologies and Libraries Used

- **Python 3.x**
- **Jupyter Notebook**
- **NumPy** - Numerical operations
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine Learning models
- **Matplotlib** and **Seaborn** - Data visualization

---

## 📚 Dataset

The experiments are based on the **CICIDS2017** dataset, specifically the 
`Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv` subset, simulating real-world DDoS attack scenarios during business hours.

---

## 🚀 Key Features

- Preprocessing network traffic data (handling missing values, normalization, feature selection)
- Training and evaluating classification models for DDoS detection
- Training anomaly detection models to identify malicious traffic without labeled data
- Comparing model performance based on Accuracy, Precision, Recall, and F1-Score
- Clear code organization for reproducibility and further research extension

---

## 📈 Results Summary

- **Random Forest** achieved the highest performance with near-perfect detection rates.
- **Gradient Boosting** and **SVM** also demonstrated excellent classification capabilities.
- Anomaly detection models (Isolation Forest, One-Class SVM) provided acceptable performance but lower recall compared to supervised approaches.

---

## 📜 Citation

If you use this work or part of it in your research, please cite the thesis and this repository.

