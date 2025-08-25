# Classification Report

Project Title : Air Fryer - Product Review Classification using Neural Networks and NLP.
Objective: To Analyze and Classify Product Reviews using NLP Techniques and Neural Networks.

# Evaluation Metrics Used

- Accuracy: Overall correctness of the model  
- Precision: How many predicted positive reviews were actually positive.
- Recall: How many positive reviews were predicted correctly.
- F1 Score: Harmonic mean of precision and recall  
- Confusion Matrix: Matrix to visualize true vs predicted classifications

# Model 1: Basic Neural Network Model with 4 Hidden Layers

-Accuracy:  0.9111842105263158
-Precision: 0.9038461538461539
-Recall:    0.9215686274509803
-F1 Score:  0.9126213592233009

-Confusion Matrix:
 [[136,  15],
  [12, 141]]


# Model 2: Artificial Neural Network Model

-Accuracy: 0.9177631578947368
-Precision: 0.9177776828434724
-Recall: 0.9177631578947368
-F1 Score: 0.9177604880696552

-Confusion Matrix:
 [[138  13]
  [ 12 141]]


# Model 3: Long Short-Term Memory Model

-Accuracy: 0.9177631578947368
-Precision: 0.9179366028708135
-Recall: 0.9177631578947368
-F1 Score: 0.9177604883007714

-Confusion Matrix:
 [[140  11]
  [ 14 139]]

# Conclusion

Among the models tested:
- ANN and LSTM models has good accuracy of 91.78%(Approx).
- Choosing the model among them depends on the goal of the project.
- Since our goal is to correctly classify the reviews,LSTM model can be considered because it is better at handling sequential text data.
- Even though accuracy is same, ANN just works on fixed vectors, so it doesn’t fully use sequential info. 