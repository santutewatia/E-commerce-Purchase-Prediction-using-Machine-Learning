# E-commerce-Purchase-Prediction-using-Machine-Learning
#### Decision Tree Classifier | Imbalanced Data | Business Analytics

#### 📌 Project Overview

This project focuses on predicting whether a website visitor will complete a purchase based on their browsing behavior.

An e-commerce company (ShopSmart) wants to improve its marketing strategy by identifying high-intent users and reducing lost revenue opportunities.

#### 🎯 Problem Statement

Thousands of users visit the platform daily, but the company struggles to identify which users are likely to convert.

👉 Challenges:
❌ Inefficient targeting of potential buyers
❌ Missed revenue opportunities
❌ Lack of behavioral insights

👉 Objective:
Build a Machine Learning classification model to predict whether a visitor will:

✅ Make a purchase (Revenue = 1)
❌ Not purchase (Revenue = 0)

#### 📊 Dataset Description
12,330 user sessions
Mix of numerical + categorical features
Each session represents a unique visitor

📌 Dataset is imbalanced, making evaluation more critical.

#### 🔑 Key Features

| Feature                 | Description                       |
| ----------------------- | --------------------------------- |
| Administrative          | Pages related to account activity |
| Administrative_Duration | Time spent on admin pages         |
| Informational           | Informational pages visited       |
| Informational_Duration  | Time spent on info pages          |
| ProductRelated          | Product pages visited             |
| ProductRelated_Duration | Time spent on product pages       |
| BounceRates             | % users leaving after one page    |
| ExitRates               | % exits from page                 |
| PageValues              | Value before transaction          |
| SpecialDay              | Closeness to special events       |
| Month                   | Month of visit                    |
| OperatingSystems        | OS used                           |
| Browser                 | Browser used                      |
| Region                  | User region                       |
| TrafficType             | Traffic source                    |
| VisitorType             | New / Returning                   |
| Weekend                 | Weekend visit                     |

#### 🧹 Data Preprocessing

✔ Handled missing values
✔ Encoded categorical variables
✔ Feature transformation
✔ Checked class imbalance
✔ Prepared dataset for modeling

#### ⚙️ Model Building
🔹 Algorithm Used:
Decision Tree Classifier
🔹 Improvements:
Applied pruning techniques (max_depth, min_samples_split, etc.)
Reduced overfitting
Improved generalization

#### 📈 Model Evaluation

Since the dataset is imbalanced, performance is evaluated using:

F1 Score (Primary Metric) ⭐
Accuracy (secondary)
Confusion Matrix
Precision & Recall

📌 Benchmark:
👉 Target F1 Score ≥ 0.55

#### 🔍 Key Insights

📊 Product-related activity strongly influences purchase decisions
⏱ Higher time spent on product pages increases conversion probability
📉 High bounce & exit rates reduce chances of purchase
📅 Special days and seasonal trends impact buying behavior
🔁 Returning visitors are more likely to convert

#### 🛠 Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

#### 🏁 Conclusion

This project demonstrates how Machine Learning can help businesses predict customer purchase behavior, enabling better targeting, improved marketing strategies, and increased revenue.
