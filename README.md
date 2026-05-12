# python_pbl
Phase 1: Data Collection and Preprocessing
Selected an air quality dataset containing pollutant and meteorological features.
Handled missing values and removed null records.
Converted date column into date-time format.
Extracted useful features such as:
Year
Month
Day
Day of Week
Applied one-hot encoding for city names.
Encoded AQI category labels using Label Encoding.
Standardized features using StandardScaler.
Tools & Libraries
Pandas
NumPy
Scikit-learn
Phase 2: Exploratory Data Analysis and Feature Engineering
Performed data visualization and analysis using:
Correlation Heatmap
AQI Category Distribution
Analyzed relationships between pollutant features and AQI levels.
Prepared final cleaned dataset for model training.
Visualization Libraries
Matplotlib
Seaborn
Phase 3: Model Training and Evaluation
Trained multiple Machine Learning classification models:
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Evaluated model performance using:
Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
ROC Curve
The models were compared to identify the best-performing classifier for AQI prediction.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Conclusion
This project demonstrates a complete Machine Learning pipeline for predicting air quality categories using environmental and meteorological data. The system successfully preprocesses raw data, trains multiple classification models, and evaluates their performance for accurate AQI prediction.
