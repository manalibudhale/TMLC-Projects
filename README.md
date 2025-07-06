# Project: Road Traffic Severity Classification (Python-JupyterNotebook)

The primary objective of this project was to build a predictive model to classify the severity of road traffic accidents, supporting authorities in taking proactive measures to enhance public safety and allocate emergency resources effectively. The analysis began with Exploratory Data Analysis (EDA) to understand the dataset’s structure and uncover patterns that contribute to accident severity. Visualizations such as histograms and heatmaps were created to explore the distribution of variables, identify correlations, and detect missing or inconsistent entries. These issues were resolved through careful data preprocessing to improve data integrity.

Categorical variables describing accident attributes (e.g., weather conditions, vehicle types, driver demographics) were encoded into numeric form using LabelEncoder, ensuring compatibility with machine learning algorithms. The dataset was then divided into training and testing sets, enabling a robust evaluation of model performance on unseen data.

To address the classification task comprehensively, a suite of machine learning models was trained, ranging from simpler methods like Logistic Regression and Decision Tree classifiers to advanced ensemble techniques including Random Forest, AdaBoost, Gradient Boosting, and XGBoost. Performance was measured using key metrics such as accuracy, confusion matrices, and F1 scores, which are critical for assessing how well the models balance the detection of high-severity and low-severity accidents.

Among all algorithms, the XGBoost classifier delivered the highest predictive performance. To further improve its accuracy, hyperparameter tuning was performed using grid search techniques, optimizing parameters such as learning rate and tree depth. This process resulted in a refined model capable of reliably predicting accident severity.

By transforming raw accident data into actionable insights, this solution equips transportation authorities with a powerful tool to identify high-risk scenarios in advance, prioritize interventions, and ultimately reduce the impact of severe accidents on communities.
