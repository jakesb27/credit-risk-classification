# Credit Risk Classification
UCI Data Analytics Bootcamp | Module 20 Challenge

## Summary
The purpose of this challenge is to predict high-risk vs. healthy loans using the <a href="https://scikit-learn.org/stable/index.html">sckit-learn</a> library. I used a Logistic Regression model that with original data that was split into training and testing datasets. In addition to a balanced accuracy score of 95.20%, the model's precison was a 1.00 for healthy loans and 0.85 for high-risk loans. Below is the complete classification report.

</br>

### <u>Classifiction Report Summary</u>

</br>

### Healthy Loan
* Precision - 1.00
* Recall - 0.99

### High-risk Loan
* Precision - 0.85
* Recall - 0.91

</br>

```
                precision    recall  f1-score   support
  Healthy Loan       1.00      0.99      1.00     18765
High-risk Loan       0.85      0.91      0.88       619

      accuracy                           0.99     19384
     macro avg       0.92      0.95      0.94     19384
  weighted avg       0.99      0.99      0.99     19384
```

</br>

## Future Use Summary
It is my recommendation that the model be used to determine healthy vs high-risk loans as a basis for further evaluation. Any loan that falls into the high-risk category should be flagged for further evaluation on a case-by-case to review other outside factors not included in the dataset sush as the need for the loan, i.e. pay off debt, home improvement, personal business. Any loan considered healthy should be automatically flagged for approval with no additional review needed.