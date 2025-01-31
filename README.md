# Decision-Tree
📌 Decision Tree Regression on Admission Prediction Data
📝 Overview
This project demonstrates Decision Tree Regression using Python and Scikit-Learn. The model predicts the Chance of Admission based on GRE Score from an admission dataset.

🚀 Steps Performed

1️⃣ Importing Required Libraries
NumPy, Pandas for data handling
Matplotlib for visualization
Scikit-Learn for model training

2️⃣ Loading and Exploring the Dataset
Reading the dataset using pandas.read_csv()
Checking shape and first few rows using .shape and .head()

3️⃣ Data Preprocessing
Dropping irrelevant columns
Extracting GRE Score as X and Chance of Admit as Y
Reshaping data for model training

4️⃣ Data Visualization
Scatter plot to visualize the relationship between GRE Score and Chance of Admit

5️⃣ Splitting the Dataset
Using train_test_split() to create training (80%) and testing (20%) sets

6️⃣ Building and Training the Decision Tree Model
Using DecisionTreeRegressor() from Scikit-Learn
Training the model with dt.fit(x_train, y_train)

7️⃣ Making Predictions
Predicting values for x_test using dt.predict(x_test)

8️⃣ Visualizing the Decision Tree
Using plot_tree() from sklearn.tree

📊 Results
The trained Decision Tree Regression Model predicts Chance of Admission based on GRE Score. The tree structure can be visualized for better understanding.
