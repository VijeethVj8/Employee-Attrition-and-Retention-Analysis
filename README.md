# Employee-Attrition-and-Retention-Analysis
# Capstone 1 - Part 1: Employee Attrition Analysis

## 📂 Dataset
Download the dataset from [here](#).

## 📌 Context & Problem Statement
Employee attrition is a critical issue for organizations due to the high cost of hiring, training, and workflow disruptions when employees leave. Understanding attrition patterns helps HR departments reduce turnover and improve employee retention.

This project utilizes a **fictional HR Attrition dataset** with **30 features** (numerical and categorical) to:
- Identify key factors influencing attrition.
- Develop predictive models to forecast employee turnover.
- Provide actionable insights to reduce attrition and enhance employee performance.

## 🏢 Business Use Case
1. **Overview of attrition within an organization**.
2. **Identify key factors contributing to employee attrition**.
3. **Analyze contributors to performance ratings** and their correlation with attrition.

---
## 🎯 Goals & Metrics
- **Identify top reasons for attrition** and propose actionable solutions.
- **Determine key drivers of employee performance**.
- **Develop and optimize predictive models** for attrition forecasting.

---
## 🚀 Project Implementation

### **📌 1. Data Retrieval (1 pt)**
✅ Extracted the dataset from the source (CSV file).  
✅ Explored dataset structure, features, and the target variable (`Attrition`).  
✅ Understood the significance of each feature related to attrition.  

### **🛠 2. Data Preprocessing (2 pts)**
✅ Cleaned dataset: handled missing values, duplicates, and outliers.  
✅ Encoded categorical variables (one-hot encoding) and transformed data types.  

### **📊 3. Feature Engineering & Exploratory Data Analysis (3 pts)**
✅ Created new features (e.g., tenure categories, seniority levels).  
✅ Analyzed key factors affecting attrition (e.g., age, salary, job role).  
✅ Visualized attrition rates across demographic & employment-related variables.  
✅ Identified patterns and correlations using heatmaps and scatter plots.  

### **🤖 4. Model Training & Evaluation**
✅ Implemented multiple models: **Random Forest, CatBoost**.  
✅ Addressed class imbalance with **class weighting & threshold tuning**.  
✅ Improved recall from **19% to 55%** while maintaining an accuracy of **84%**.  
✅ Final classification report:

```plaintext
              precision    recall  f1-score   support
           0       0.91      0.90      0.91       247
           1       0.51      0.55      0.53        47
    accuracy                           0.84       294
   macro avg       0.71      0.73      0.72       294
weighted avg       0.85      0.84      0.85       294
```

### **📢 5. Effective Communication (2 pts)**
✅ Markdown cells used to explain each step.  
✅ Clear visualization with labeled plots.  
✅ Well-commented and structured code for readability.  

---
## 🛠️ Tools & Technologies Used
- **Programming:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, CatBoost
- **Machine Learning:** Classification models, Threshold tuning, Feature Engineering
- **Data Visualization:** Heatmaps, Bar charts, Scatter plots
- **Version Control:** GitHub

---
## 📌 Challenges & Solutions
| **Challenge** | **Solution** |
|--------------|-------------|
| **Class Imbalance** (few attrition cases compared to non-attrition) | Used **class weighting** and **threshold tuning** to improve recall. |
| **Selecting the Right Model** | Tested multiple models, optimized **CatBoost** as the best-performing model. |
| **`predict_proba()` errors in CatBoost** | Fixed by setting `loss_function='Logloss'`. |
| **Improving Recall without Losing Accuracy** | Optimized threshold tuning to balance **precision and recall**. |

---
## 📌 Submission Guidelines
- **Ensure all code runs correctly** before submission.
- **Cite references** for external resources used (Stack Overflow, ChatGPT, etc.).
- **Minimum score required:** **7/10**.
- **Upload project to GitHub** and submit the link via LMS.

---
## 🏆 Final Thoughts
- Successfully **identified key attrition factors**.
- Developed a **high-performing predictive model** with **optimized recall**.
- The project is well-documented and structured for easy understanding.

✅ **Ready for GitHub submission!** 🚀

