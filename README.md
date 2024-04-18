NETWORK INTRUSION DETECTION

1. Data Loading and Exploration:
•	Loaded training and testing datasets containing network intrusion data.
•	Checked the structure and basic statistics of the datasets.
2. Data Preprocessing:
•	Removed the 'num_outbound_cmds' column as it contained redundant information.
•	Explored the distribution of the 'class' column, indicating the type of network activity (normal or anomaly).
•	Checked for missing values (none found) and duplicates (none present).
3. Exploratory Data Analysis (EDA):
•	Visualized categorical features using pie charts.
•	Examined the distribution of numerical features with histograms.
•	Created a heatmap to visualize the correlation matrix of numerical features.
•	Investigated class distribution across categorical features using count plots.
•	Detected outliers using box plots.
4. Feature Scaling:
•	Scaled numerical attributes to have zero mean and unit variance using StandardScaler.
5. Encoding Categorical Attributes:
•	Applied label encoding to convert categorical attributes into numerical format.
6. Feature Selection:
•	Utilized Random Forest Classifier to identify important features.
•	Conducted Recursive Feature Elimination (RFE) to select a subset of 15 relevant features.
7. Dataset Partitioning:
•	Split the dataset into training and testing sets.
8. Model Implementation and Evaluation:
•	Applied three machine learning models: Naive Bayes Classifier, Logistic Regression, and K-Nearest Neighbors (KNN) Classifier.
•	Trained each model on the training set and evaluated performance on the test set.
•	Assessed accuracy, generated classification reports, and visualized confusion matrices for each model.
•	Achieved high accuracy across all models: Naive Bayes (89%), Logistic Regression (96%), and KNN Classifier (99%).
9. Model Comparison:
•	Compared the accuracy of the three models using a bar chart.
10. Conclusion:
•	Successfully implemented and evaluated machine learning models for network intrusion detection.
•	Achieved high accuracy, demonstrating the effectiveness of the models in distinguishing normal and anomalous network activities.
This project involved comprehensive data exploration, preprocessing, model training, and evaluation, showcasing your proficiency in machine learning and network intrusion detection techniques.
