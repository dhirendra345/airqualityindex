# airqualityindex
# 🌍 AI-Based Air Quality Index (AQI) Prediction & Hazard Detection System  
A Machine Learning project designed to predict AQI categories and identify hazardous pollution levels using feature engineering, real-time monitoring concepts, and multiple ML models.  
This project was developed as part of the INT395 POC submission.

---

## 📌 Project Overview
Air pollution continues to be one of the leading environmental challenges worldwide.  
This project uses machine learning techniques to classify AQI levels into three categories:

- **Good**  
- **Moderate**  
- **Hazardous**

The system integrates advanced feature engineering and an innovative **Weighted Toxicity Index** to enhance prediction accuracy and early hazard detection.

---

## 🚀 Key Features
- **>90% Accuracy** across three ML models (Random Forest, SVM, Logistic Regression)
- **Feature Engineering:** PM Ratio, Total Pollution Load, Toxicity Index
- **Innovative Component:** Weighted Toxicity Index (0.3 × NO₂ + 0.3 × SO₂ + 0.4 × CO)
- **EDA Visualizations:** Distribution plots, correlation heatmaps, boxplots
- **SMOTE** applied for handling class imbalance
- **Scalable pipeline** for future IoT integration
- **ROC-AUC analysis** for model reliability

---

## 📂 Folder Structure

├──  dataset
│ └── AQI_DS.csv
│
├──  notebooks
│ ├── RandomForest_AQI.ipynb
│ ├── SVM_AQI.ipynb
│ └── LogisticRegression_AQI.ipynb
│
├──  ppt
│ └── AQI_Project_Presentation.pptx
│
├──  documentation
│ └── Patent_Document.docx
│ └── POC_Report.docx
│
├── README.md
