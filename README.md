🏨 Reducing Hotel Booking Cancellation Rate (City Hotel & Resort)

📋 Project Overview

This project aims to analyze and reduce hotel booking cancellations for a City Hotel and a Resort Hotel using data-driven insights. By exploring booking trends, customer behavior, and influential factors, the project identifies actionable strategies to minimize cancellations and improve hotel revenue management.

🎯 Objectives

Identify key factors contributing to high booking cancellation rates.

Compare cancellation patterns between City Hotel and Resort Hotel.

Build predictive models to forecast cancellations before they occur.

Suggest data-backed recommendations to reduce future cancellations.

📊 Dataset

Source: Hotel Booking Demand Dataset (Kaggle)

Records: ~119,000 bookings

Features: 32 attributes including booking date, lead time, room type, deposit type, and customer demographics.



---

⚙ Tools & Technologies

Category	Tools/Technologies

Data Processing	Python (Pandas, NumPy)
Data Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-learn
Notebook Environment	Jupyter Notebook
Version Control	Git & GitHub



---

🧠 Approach

1. Data Cleaning: Handle missing values, duplicates, and outliers.


2. Exploratory Data Analysis (EDA): Understand patterns and correlations.


3. Feature Engineering: Encode categorical features and scale numerical ones.


4. Model Building: Train classification models (Logistic Regression, Random Forest, XGBoost) to predict cancellations.


5. Evaluation: Compare models using accuracy, precision, recall, and ROC-AUC score.


6. Recommendations: Provide actionable insights to reduce cancellations.




---

📈 Key Insights

Longer lead times and no-deposit bookings have higher cancellation rates.

City Hotels face more cancellations than Resort Hotels.

Bookings made through Online Travel Agents (OTAs) tend to cancel more.

Implementing non-refundable deposits and better communication strategies can reduce cancellations.



---

🧩 Results

Model	Accuracy	ROC-AUC

Logistic Regression	79%	0.81
Random Forest	85%	0.89
XGBoost	87%	0.91



---

💡 Recommendations

Introduce incentives for early confirmations.

Monitor high-risk bookings using predictive models.

Use personalized reminders and flexible policies for loyal customers.

Optimize deposit policies to balance flexibility and security.
