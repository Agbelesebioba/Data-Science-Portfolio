**Exploratory and Predictive Data Analysis of PCOS**

**Overview**

This project analyzes and predicts Polycystic Ovary Syndrome (PCOS) using a structured dataset and various machine learning techniques. It focuses on identifying key risk factors and building a predictive model for early diagnosis.

**Dataset**

•	Source: Kaggle - PCOS Dataset

•	Includes clinical, hormonal, metabolic, and lifestyle attributes

**Data Import & Exploration:**

•	Load the PCOS dataset using pandas

•	Use df.info(), df.describe(), and df.head() to understand data structure

•	Visualize class distribution (PCOS vs Non-PCOS)

**Data Cleaning & Preprocessing:**

•	Handle missing values

•	Encode categorical variables

•	Normalize features for distance-based models

**Exploratory Data Analysis (EDA):**

•	Visualizations with matplotlib and seaborn to explore distributions

•	Correlation heatmaps to identify relationships between features

•	Boxplots and histograms for key hormones (FSH, LH, AMH), BMI, and lifestyle traits

**Modeling:**

•	Implemented ML models: Logistic Regression, Random Forest, SVM, XGBoost

•	Used techniques like Recursive Feature Elimination (RFE) and Principal Component Analysis (PCA) for feature selection

**Evaluation:**

•	Accuracy, precision, recall, F1-score, and ROC-AUC used to evaluate models

•	Best performance: Random Forest and XGBoost with ~99% accuracy

**Insights & Output:**

•	Top features: Follicle counts (Left & Right), AMH levels, BMI, and lifestyle indicators (e.g., fast food consumption)

•	Visualization of top feature importance from the models

**Visualizations**

•	Class distribution (PCOS vs Non-PCOS)

•	Hormonal and metabolic feature comparisons using boxplots

•	Correlation matrix heatmap

•	Feature importance bar charts from ML models

**Key Findings**

•	Random Forest and XGBoost provided the highest predictive accuracy (~99%).

•	PCOS is strongly associated with elevated AMH, follicle counts, BMI, and lifestyle behaviors.

•	A combination of hormonal and lifestyle data provides the most effective diagnosis model.


