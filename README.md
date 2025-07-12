# Cars24-Price-Prediction-Project-repository-structure-
# 🚗 Cars24 Price Prediction Model

### 📋 Project Overview
This project builds a predictive model to estimate the selling price of cars based on historical data scraped from Cars24.  
It covers the full data pipeline — from web scraping & data cleaning to exploratory analysis, feature engineering, model training, and evaluation.

---

## 🎯 Objectives
✅ Scrape real-world car listings from Cars24.  
✅ Clean and preprocess the data for analysis.  
✅ Perform EDA (exploratory data analysis) to uncover insights.  
✅ Train a regression model to predict car prices.  
✅ Evaluate model performance and interpret results.

---

## 🔧 Tools & Technologies
- 🐍 Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- 📊 Jupyter Notebook
- 💾 Pickle (for saving the trained model)

---

## 📂 Repository Structure
Cars24-Price-Prediction/
├── Data/ # Raw & cleaned datasets
├── Notebook/ # Jupyter notebook with code
├── Models/ # Trained model file
├── Screenshots/ # Sample visualizations & results
├── README.md # Project documentation


---

## 📊 Workflow
1️⃣ Data Collection:  
Web scraping Cars24 using Selenium & BeautifulSoup.  
2️⃣ Data Cleaning:  
Handling missing values, outliers, and converting strings to numeric.  
3️⃣ EDA:  
Visualizing key variables — age, kms driven, fuel type, etc.  
4️⃣ Modeling:  
Trained a regression model (Linear Regression, Random Forest, etc.) to predict car price.  
Achieved **R² ≈ 0.89** on test data.  
5️⃣ Deployment-ready:  
Saved model as `.pkl` for future use.

---

## 🌟 Key Insights
- Car price decreases with age and mileage.
- Petrol cars tend to have higher resale value compared to diesel in some segments.
- Brand & model significantly influence price.

---

## 📷 Screenshots
![Dashboard Insights](<img width="1327" height="739" alt="Screenshot 2025-07-06 215027" src="https://github.com/user-attachments/assets/75a289fd-91e9-4f74-ba3b-19a4bbc438d0" />
)  
![Model Performance](<img width="1428" height="419" alt="Screenshot 2025-07-12 141439" src="https://github.com/user-attachments/assets/d909fce7-024c-451d-9416-53c3c7d48a1c" />
)  


---

## 🚀 How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/yourusername/Cars24-Price-Prediction.git
   cd Cars24-Price-Prediction

📬 Contact
📧 jaiswalank1999@gmail.com
🔗 LinkedIn www.linkedin.com/in/ankush-kumar-jaiswal-196937200



