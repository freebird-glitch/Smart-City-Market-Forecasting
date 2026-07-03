# Smart City Infrastructure & Commercial Market Forecasting

# Internship Domain: Data Science & Machine Learning
*Organization:* The IoT Academy / UpSkill Campus  
*Intern Name:* Riya Gaikwad  

## 📌 Project Background & Problem Statement
In modern urban planning, tracking the intersection of commercial density and shifting market demands is crucial for managing city resources. This project explores geospatial retail footprints (using global store distributions) alongside consumer demand metrics over time to forecast regional traffic spikes and structural shifts.

## 🛠️ Design & Data Cleaning
- *Datasets Used:* `directory.csv` (Starbucks commercial hubs) and `vgsales.csv` (Global consumer trends).
- *Data Preparation:* Used Python (`Pandas`) to drop incomplete feature parameters, align structural data categories, and convert text variables into clean numerical markers using One-Hot Encoding (`pd.get_dummies()`).

## 📊 Implementation & Results
I trained and evaluated two distinct machine learning frameworks to predict global demand trajectories:

1. *Linear Regression (Baseline):* - **MAE:** 0.0026
   - **RMSE:** 0.0049
2. *Random Forest Regressor (Advanced):* - **MAE:** 0.0101
   - **RMSE:** 0.0858

### Key Performance Observation:
The baseline Linear Regression model significantly outperformed the complex Random Forest framework on the validation set. The Random Forest model exhibited distinct *overfitting*, capturing training quirks perfectly but generating a higher error rate when forecasting unseen chronological sequences.

## 💡 Key Learnings
- Mastered structural data cleaning operations, discovering that data preparation occupies the vast majority of a data scientist's pipeline.
- Implemented chronological chronological train-test splits crucial for managing sequential historical trends without breaking chronological order.
- Learned how to diagnose and document model overfitting issues by contrasting baseline versus non-linear algorithmic metrics.
