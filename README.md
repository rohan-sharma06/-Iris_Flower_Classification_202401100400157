# -Iris_Flower_Classification_202401100400157

## Overview
This project implements the **Iris Flower Classification** using a **Random Forest Classifier**. The model predicts the species of an iris flower based on sepal and petal dimensions.

## Dataset
The Iris dataset consists of 150 samples with four features:
- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

### Target Classes:
1. **Setosa**
2. **Versicolor**
3. **Virginica**

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Installation and Execution
1. Clone the repository or download the script.
2. Run the script using:
   ```bash
   python iris_classification.py
   ```

## Steps in the Code
1. **Load the dataset** using `sklearn.datasets`.
2. **Preprocess the data** (normalize features, map target labels).
3. **Split the dataset** into training and testing sets.
4. **Train the model** using `RandomForestClassifier`.
5. **Evaluate the model** using accuracy, confusion matrix, and classification report.
6. **Visualize the results** using a confusion matrix heatmap.

## Model Evaluation
The model is evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**



## Visualization
A confusion matrix heatmap is generated to show classification performance.

## Future Improvements
- Implement different classifiers (SVM, Neural Networks, KNN, etc.).
- Deploy the model as a web application.
- Perform hyperparameter tuning to optimize performance.

## Author
**Rohan Sharma**

## License
This project is licensed under the MIT License.
