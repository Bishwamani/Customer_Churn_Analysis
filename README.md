# Customer Churn Analysis - Telecommunications

##  Project Overview
This project analyses customer churn in a telecommunications company using data preprocessing, clustering, and predictive modeling techniques.

---

##  Dataset
- Raw dataset: Dataset_ATS_v2.csv
- Processed dataset: churn_cleaned.csv

---

##  Data Preparation
- Missing values handled using median and mode
- Categorical variables encoded using Label Encoding
- Dataset split into:
  - 80% training
  - 20% testing
- Feature scaling applied using StandardScaler

---

##  Clustering Analysis
- K-Means clustering used to segment customers
- Elbow method used to determine optimal clusters
- PCA used for visualization

Outputs:
- elbow_plot.png
- cluster_visualization.png

---

##  Predictive Modeling
- ANN model developed for churn prediction
- Model trained and evaluated using test data

Outputs:
- ann_model.h5
- ann_predictions.csv

---

##  Key Findings
- High monthly charges increase churn risk
- Short tenure customers are more likely to churn
- Different customer segments show different behaviours

---

##  Recommendations
- Improve customer retention strategies
- Provide personalised offers
- Enhance customer service experience

---

##  Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- TensorFlow / Keras

##  Model File
The trained ANN model is saved as `models/ann_model.h5`.  
This file contains the saved neural network architecture and learned weights for churn prediction.
