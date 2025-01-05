1. Loaded the data file where data source is Kaggle
2. Cleaned dataset and dropped unrequired columns to keep the clean memory
3. Analyzed the dataset and identified a few columns came with null values
4. Used the imputation method to replace null values with median and mode as per requirement
5. Feature Engineering : Performed One Hot Encoding to convert required features from categorical to numerical in order to avoid errors while modeling
6. Built and tested the Logistic Regression model
7. Hypertuned the model in order to improve accuracy
8. Both the results were same, since Hypertune model was hypertuned with various parameters I further proceeded with results of Hypertuned model
9. Used the results of Classification Report to compute survival percentage
10. Results : 40% of passengers survived as per the given historical dataset
11. Plotted countplot to demonstrate survival rate visually
