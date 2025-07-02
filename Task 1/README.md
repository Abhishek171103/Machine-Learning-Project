# Task Assessment 1 (Basic ML Classification )

This project trains a simple two-layer neural network from scratch (no high-level wrappers) to classify the Iris dataset using PyTorch.

## 📊 Dataset

- Dataset: [Iris Dataset]
- Format: `iris.csv`
- Features: `sepal length`, `sepal width`, `petal length`, `petal width`
- Target: Flower species (`0 = setosa`, `1 = versicolor`, `2 = virginica`)

## 🛠 Requirements

Install the required Python libraries:
pip install torch pandas matplotlib scikit-learn etc.

## 📈 Output

Console shows accuracy for each epoch.
accuracy_plot.png shows how model accuracy evolved over 50 epochs.

## 📂 Files Included

iris.csv – the dataset
iris_classification.py – training and evaluation script
accuracy_plot.png – accuracy vs. epoch plot
README.md – instructions the assessment 

## 📌 Notes

No high-level libraries (e.g., sklearn.model_selection, Keras, etc.) were used for model creation.
Model uses SGD optimizer and CrossEntropyLoss.
