# Customer-Segmentation-and-Purchase-Prediction-Using-Machine-Learning-Techniques
This project analyzes customer behavior for an e-commerce company to:  Understand spending patterns. Predict whether a customer will make a purchase. Segment customers for targeted marketing campaigns.
# 🛍️ Customer Segmentation and Purchase Prediction Using Machine Learning

---

## 🧩 Problem Statement

1. Descriptive statistics and visualizations.
2. Feature preprocessing (encoding, normalization, scaling).
3. Predict customer satisfaction using classification.
4. Segment customers using clustering.

## Key Steps and Techniques

### 1️ Data Preprocessing

* Calculated **mean, median, and standard deviation** for:

  * Age, Total Spend, Items Purchased, Average Rating, Days Since Last Purchase.
* Applied:

  * **Label Encoding** → Gender, Membership Type, Satisfaction Level
  * **One-Hot Encoding** → City
* Scaled features using:

  * **Normalization** and **Standardization**
* Created **boxplots** and treated outliers in Total Spend.

### 2️ Classification

* Encoded Satisfaction Level:

  * Unsatisfied = 0, Neutral = 1, Satisfied = 2
* Built a **Logistic Regression model**.
* Evaluated using:

  * Accuracy Score
  * Confusion Matrix

### 3️ Clustering

* Applied **K-Means Clustering** on scaled numeric features.
* Determined optimal clusters using the **Elbow Method**.
* Visualized clusters using scatter plots.


##  Visualizations

* Boxplot of Total Spend
* Elbow Method Curve
* Cluster Scatter Plot

## Technologies Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn
* Jupyter Notebook
  
### Results Summary
* **Classification Accuracy:** ~85–90% (varies by dataset)
* Identified **3–4 key customer segments**
* Provided actionable insights for targeted marketingience & Machine Learning Enthusiast.
