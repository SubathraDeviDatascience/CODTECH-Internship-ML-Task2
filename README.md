# Overview of the project

## Project Title: Credit Card Fraud Detection

### Objective
To develop a fraud detection model that identifies fraudulent credit card transactions using supervised learning techniques. Given the challenge of dealing with imbalanced data, the model is designed to effectively distinguish between genuine and fraudulent transactions.

### Dataset
The synthetic dataset used for this project includes the following columns:
  - **Feature1** : Numeric feature representing transaction details.
  - **Feature2** : Numeric feature representing transaction details.
  - **Feature3** : Numeric feature representing transaction details.
  - **Feature4** : Numeric feature representing transaction details.
  - **Class**    : Target variable indicating whether a transaction is fraudulent (1) or not (0).

### Key Activities
1. **Data Preparation**
     - Load and preprocess the dataset.
     - Handle imbalanced data using techniques like Random Under-Sampling.

2. **Feature Selection**
     -  Select relevant features for training the model.

3. **Model Training**
     -  Use RandomForestClassifier from scikit-learn to train the model on the dataset.

4. **Prediction**
     -  Make predictions on the test data and evaluate the model's performance.

5. **Visualization**
     -  Visualize the results using confusion matrix and ROC curve.
  
### Output
![image](https://github.com/user-attachments/assets/539d29f4-0608-4c5f-b674-a03997601c77)


### Conclusion
This project demonstrates the use of supervised learning techniques to detect fraudulent credit card transactions. By addressing the challenge of imbalanced data, the model provides a reliable way to identify potential fraud and enhance the security of financial transactions.
