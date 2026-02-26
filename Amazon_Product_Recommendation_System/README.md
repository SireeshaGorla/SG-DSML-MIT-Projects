# Amazon Product Recommendation System

## 📌 Project Overview
In this project, I developed a recommendation engine to suggest electronic products to Amazon customers. By analyzing a dataset of user ratings, I implemented various algorithmic techniques to solve the "information overload" problem, helping users find relevant products in a sea of millions of choices.

## 🎯 Objectives
- **Personalized Suggestions:** Moving beyond generic "top-selling" lists to user-specific recommendations.
- **Algorithm Comparison:** Evaluating the strengths and weaknesses of different filtering methods.
- **Model Optimization:** Using hyperparameter tuning to improve the accuracy of predicted ratings.

## 🛠️ Tech Stack
- **Language:** Python
- **Core Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Recommendation Engine:** Scikit-Surprise (SVD, KNN)
- **Evaluation Metrics:** RMSE, Precision@k, Recall@k, and F1-Score

## 📊 Models Implemented
I built and compared four distinct recommendation strategies:
1. **Rank-Based Recommendation:** Using global popularity to recommend items to new users (Cold Start problem).
2. **User-User Collaborative Filtering:** Finding similar users based on their rating patterns.
3. **Item-Item Collaborative Filtering:** Suggesting products similar to those a user has liked before.
4. **Model-Based (Matrix Factorization):** Using **SVD (Singular Value Decomposition)** to uncover latent features in the user-item interaction matrix.



## 🚀 Key Insights
- The **SVD model** outperformed basic similarity-based models after hyperparameter tuning via GridSearchCV.
- Collaborative filtering effectively handled the sparsity of the Amazon dataset, providing more nuanced recommendations than simple popularity rankings.
- The project demonstrates a full pipeline from data cleaning to advanced model evaluation.

## 📁 How to Run
1. Navigate to the `Amazon_Product_Recommendation_System` folder.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `Recommendation_Systems_Learner_Notebook_Full_Code_Sireesha_Gorla.ipynb`
