# ExtraaLearn: Predicting Lead Conversion in EdTech

## 📌 Project Overview
This project focuses on identifying potential customers (leads) for **ExtraaLearn**, an EdTech startup. Using historical lead data, I built and tuned machine learning models to predict which leads are most likely to convert into paid customers, allowing the company to allocate its marketing resources more efficiently.

## 🎯 Objectives
- **Predict Conversion:** Build a classification model to identify high-probability leads.
- **Identify Key Drivers:** Determine the factors (e.g., website time, occupation) that most influence a lead's decision to subscribe.
- **Lead Profiling:** Create a profile of a "likely-to-convert" customer.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Models Used:** Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, and Bagging Classifier.

## 📊 Key Findings from EDA
- **Conversion Rate:** The dataset showed a baseline conversion rate of approximately 30%.
- **High-Impact Features:** - **Website Interaction:** Leads who first contact through the website have a higher conversion rate than mobile app users.
  - **Profile Completion:** Leads with "High" profile completion are significantly more likely to convert.
  - **Demographics:** Working professionals and individuals over age 35 show higher interest in paid programs.

## 🚀 Model Performance
The final models were optimized using **GridSearchCV**.
- **Random Forest** and **Decision Trees** provided the best balance of precision and recall.
- Key factors influencing the model were the **time spent on the website** and the **first interaction source**.

## 📁 How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/Sireesha_Gorla_Full_ClassificationProject.ipynb` in Jupyter or Google Colab.
