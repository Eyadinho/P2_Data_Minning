📊 FIFA Player Performance Prediction using Data Mining
🚀 Overview

This project explores how machine learning can be used to predict soccer player performance and uncover the key factors that influence player ratings.

Instead of relying on a single dataset, this project uses three different FIFA datasets to ensure that results are robust, reliable, and generalizable.

The project combines:

Data preprocessing
Feature engineering
Multiple machine learning models
Clustering for player segmentation
Cross-dataset evaluation
🎯 Objectives
Predict player overall rating using machine learning
Compare performance of multiple models
Engineer meaningful features that improve prediction
Validate results across multiple datasets
Extract insights that can be applied to real-world sports analytics
📂 Datasets Used

This project uses three Kaggle datasets:

fifa_players.csv
Detailed player attributes (technical + physical stats)
FIFA-Players-Dataset.csv
Large-scale dataset with extended metadata
FIFA Player Season Stats Dataset
Performance-based and season-related statistics

Raw Data
   ↓
Data Cleaning & Preprocessing
   ↓
Feature Engineering
   ↓
Model Training
   ↓
Evaluation & Comparison
   ↓
Clustering & Insights



🧹 Data Preprocessing
Standardized column names across datasets
Converted relevant columns to numeric
Handled missing values
Selected consistent feature sets for modeling


🧠 Feature Engineering

Custom features were created to improve model performance:

Technical Score
→ Average of dribbling, vision, composure
Value-to-Wage Ratio
→ Measures financial efficiency
Age Potential Gap
→ Difference between potential and current rating

These features helped capture player quality, efficiency, and growth potential.

🤖 Machine Learning Models

The following models were implemented:

Linear Regression (baseline)
Ridge Regression
K-Nearest Neighbors (KNN)
Random Forest (best performer)
📈 Results
Random Forest consistently outperformed all other models
Achieved:
Highest R² score
Lowest RMSE and MAE
Performance remained strong across all three datasets

👉 This demonstrates that the model is both accurate and reliable

🧩 Clustering (Unsupervised Learning)

K-Means clustering was used to group players into meaningful segments:

Playmakers
Attackers
Defenders
Developing players

This adds interpretability beyond prediction by revealing hidden patterns in player types.

📊 Key Insights
Technical attributes strongly influence player ratings
Feature engineering significantly improves model performance
Random Forest handles complex relationships better than linear models
Results are consistent across multiple datasets
🌍 Real-World Impact

This project demonstrates how machine learning can be applied to:

Player scouting and recruitment
Identifying undervalued talent
Supporting transfer decisions
Enhancing sports analytics with data-driven insights
⚠️ Limitations
FIFA ratings include subjective elements
No real match performance data (goals, assists, etc.)
Datasets vary in structure and completeness
🔮 Future Work
Incorporate real match statistics
Build position-specific models
Explore deep learning approaches
Develop a real-time analytics dashboard
🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib
Jupyter Notebook




