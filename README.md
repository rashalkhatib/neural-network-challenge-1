# neural-network-challenge-1
This project implements a neural network model using TensorFlow and Keras to predict outcomes related to student loan repayment. The model is trained on student loan data and saved for future use. It is also saved in both .keras and .h5 formats.

## Part 1 | Prepare the data:
- Two datasets were created: a target (y) dataset, which includes the "credit_ranking" column, and a features (X) dataset, which includes the other columns.
- The features and target sets have been split into training and testing datasets.
- Scikit-learn's StandardScaler was used to scale the features data.
## Part 2 | Compile and Evaluate a Model:
- A deep neural network was created with appropriate parameters.
- The model was compiled and fit using the accuracy loss function, the adam optimizer, the accuracy evaluation metric, and a small number of epochs (50).
- The model was evaluated using the test data to determine its loss and accuracy.
- The model was saved and exported to a keras file named student_loans.keras.
# Part 3 | Predict loan repayment success:
- The saved model was reloaded.
- The reloaded model was used to make binary predictions on the testing data.
- A classification report is generated for the predictions and the testing data.
# Summary:
This neural network model can predict the likelihood that a student applicant will repay their student loans. By doing so, we would have a more accurate interest rate for the borrowers.
