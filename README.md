# 🛡️ Intrusion Detection in Networks using Machine Learning  

## 📖 Overview  
This project focuses on detecting malicious network activity using **machine learning algorithms**.  
It analyzes network traffic data to classify behavior as **normal** or **suspicious**, helping enhance cybersecurity and prevent unauthorized intrusions in computer networks.

---

## 🎯 Objectives  
- Build an **Intrusion Detection System (IDS)** using machine learning.  
- Train models to classify network traffic into normal or attack categories.  
- Compare multiple algorithms to find the most accurate one.  

---

## 🧠 Machine Learning Models Used  
- Gradient Boosting  
- LightGBM  
- Random Forest
- Support Vector Machine (SVM)

---

## 🧩 Dataset  
The project can use publicly available network intrusion datasets such as:  
- **NSL-KDD Dataset**  

Each record in these datasets includes features like duration, protocol type, service, flag, source bytes, destination bytes, and others that represent network traffic behavior.

---

## ⚙️ Workflow  
1. **Data Preprocessing** – Data cleaning, encoding categorical values, and normalization.  
2. **Feature Selection** – Identifying the most significant features impacting prediction.  
3. **Model Training** – Training and tuning multiple ML models for classification.  
4. **Model Evaluation** – Using accuracy, precision, recall, F1-score, and confusion matrix.  
5. **Visualization** – Feature importance, ROC curves, and confusion matrices for analysis.  

---

## 📊 Results  
- Models such as **Gradient Boosting** and **LightGBM** achieved the best performance.  
- The system effectively detects attacks like **DoS**, **Probe**, **R2L**, and **U2R**.  

---

## 💻 Technologies Used  
- **Language:** Python  
- **Libraries:** scikit-learn, pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook / VS Code  

---

## 🚀 How to Run  
1. **Clone this repository:**  
   ```bash
   git clone https://github.com/skjbcads/Intrusion-Detection-in-Networks-Using-Machine-Learning-.git

