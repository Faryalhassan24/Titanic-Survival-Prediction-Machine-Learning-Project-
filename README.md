## About the project
This project applies Machine Learning algorithms (Decision Tree & K-Nearest Neighbors) on the Titanic dataset to predict passenger survival. It involves data preprocessing, feature encoding, model training, evaluation, and visualization.

### Technologies 
•	Python
•	Pandas, NumPy (Data Handling)
•	Matplotlib, Seaborn (Visualization)
•	Scikit-learn (Machine Learning Models)

### Project Workflow
1.	Data Preprocessing

•	Handled missing values using Simple Imputer and mean filling.

•	Converted categorical variables (Sex, Embarked, Cabin, Ticket) into numeric using Label Encoding.

•	Dropped irrelevant columns. 

2.	Exploratory Data Analysis (EDA)

Scatterplots between features, such as Age vs. Fare, Age vs. SibSp, and Fare vs. Parch, to understand survival patterns.
Visualized survival distribution across categories.

### Machine Learning Models
##### 1. Decision Tree Classifier 

•	Applied with max_depth=4.

•	Visualized the decision tree.

•	Evaluated using Accuracy, Confusion Matrix, and Classification Report.

##### 2. K-Nearest Neighbors (KNN) 

•	Implemented with n_neighbors=1.

•	Compared predictions with actual survival labels.

•	Evaluated using Accuracy, Confusion Matrix, and Classification Report.

•	Heatmap of confusion matrix created using Seaborn.

### Results
1. Decision Tree Classifier
o	Accuracy: 78.73%
o	Insights: The Decision Tree shows key rules like women and higher-class passengers had better chances of survival.
2. KNN Classifier
o	Accuracy: 69.95%
o	Insights: Works well with selected features; performance depends on k value

