🌸 Iris Flower Classification (Beginner ML Project)

This is my first machine learning project, where I built a simple model to classify iris flowers
into three species based on their measurements. The goal of this project was to
understand the complete ML workflow — from loading data to making predictions.

The three species in the dataset are:
*Setosa
*Versicolor
*Virginica

💡 What I Did in This Project
*Loaded the Iris dataset from scikit-learn
*Explored the features (sepal length/width, petal length/width)
*Split the dataset into training and testing sets
*Trained a Random Forest Classifier
*Achieved 100% accuracy on the test data
*Made predictions on new flower measurements
*This project helped me understand how ML models learn patterns and how to structure a notebook properly.

🚀 Example Prediction
prediction = model.predict([[6.3, 3.0, 4.5, 1.5]])
print("Predicted Species:", iris.target_names[prediction][0])

Output:
Predicted Species: versicolor

🔧 Tools & Libraries Used
Python
Pandas
NumPy
scikit-learn
Kaggle Notebook

📁 Files in This Repository
Iris Flower Classification.ipynb — the notebook with the full code
README.md — this file
