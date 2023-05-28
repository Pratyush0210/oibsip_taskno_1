# oibsip_taskno_1
The Iris dataset is a popular dataset for machine learning tasks. It consists of measurements of four features (sepal length, sepal width, petal length, and petal width) of three different species of Iris flowers (setosa, versicolor, and virginica).

A machine learning model to predict the species of Iris flower based on its measurements using the Python libraries pandas, numpy, seaborn, scikit-learn, and matplotlib.
Make sure to replace 'iris_dataset.csv' with the actual path to your Iris dataset file. The code performs the following steps:

- Load the Iris dataset using pd.read_csv().
- Explore the dataset by displaying the first few rows using head() and visualize the data using pairplot() from seaborn and show() from matplotlib.
- Split the dataset into features (X) and target (y).
- Encode the target variable using LabelEncoder() from scikit-learn.
- Split the data into training and testing sets using train_test_split() from scikit-learn.
- Create a K-Nearest Neighbors classifier with KNeighborsClassifier().
- Train the classifier using fit().
- Make predictions on the test set using predict().
- Evaluate the model by calculating the accuracy score using accuracy_score() from scikit-learn and generating a classification report using classification_report() from scikit-learn.
- This code uses the K-Nearest Neighbors algorithm for classification, but you can try other algorithms provided by scikit-learn as well. Remember to adjust the hyperparameters and explore different techniques to improve the model's performance.
