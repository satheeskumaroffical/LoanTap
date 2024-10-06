# LoanTap
Logistic Regression model for LoanTap.
final model metrics score (threshold : 0.6)

precision : 0.9105728924080112

F1_score: 0.8303542986585496

accuracy_score: 0.9393129819319059

recall_score: 0.7631253659488647

This report presents the analysis of a Logistic Regression model developed for LoanTap, aimed at predicting loan statuses as either "fully paid" or "charged off." Given the financial implications of these classifications, accurate predictions are crucial for effective risk management and decision-making.

The primary objective of this analysis is to evaluate the model's performance based on various metrics and thresholds, ensuring it meets LoanTap's business requirements for precision , FL score and accuracy in loan status prediction.

Dataset: LoanTap loan data, including various features such as loan amount, annual income, account type, etc.

Target Variable: Loan status (1 = fully paid, 0 = charged off).

Model Development Logistic Regression Model Algorithm: Logistic Regression

Model Evaluation Metrics

Confusion Matrix: Provides counts of true positives (TP), false positives (FP), true negatives (TN), and false negatives (FN).

Precision: Measures the accuracy of positive predictions.

F1 Score: The harmonic mean of precision and recall.

Accuracy: The overall correctness of the model's predictions.

Insights-

High Precision: The model achieved a precision of 91.06%, indicating a strong ability to correctly identify fully paid loans.

Robust Accuracy: An accuracy of 93.93% highlights the model's overall effectiveness in predicting loan statuses.

Conclusion-

The Logistic Regression model for LoanTap demonstrates significant predictive power with a precision of 91.06% and an accuracy of 93.93%. The adjustments made to the threshold successfully enhanced precision, reducing the likelihood of false positives. These results suggest that the model is well-suited for LoanTap's operational needs in assessing loan risk and informing decision-making.
