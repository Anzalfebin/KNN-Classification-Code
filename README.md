# K-Nearest Neighbors (KNN) Classification

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for classification using Python and Scikit-learn.

## Objective
To understand and implement the KNN algorithm and evaluate its performance using accuracy and confusion matrix.

## Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Dataset
Iris dataset (built-in from Scikit-learn)

## Steps Performed
1. Loaded the Iris dataset
2. Split data into training and testing sets
3. Normalized features using StandardScaler
4. Trained KNN model with different K values
5. Selected best K based on accuracy
6. Evaluated model using:
   - Accuracy score
   - Confusion matrix
7. Visualized accuracy vs K graph

## Results
- Achieved high classification accuracy using optimal K value.
- Model performed well on multi-class classification.

## Key Learnings
- KNN is an instance-based learning algorithm
- Normalization improves performance
- Choosing correct K is important for accuracy
- Works well for small datasets

## How to Run
1. Install required libraries:
   pip install numpy pandas matplotlib scikit-learn

2. Run the Python file:
   python knn_classification.py
