# credit_risk_classification

    Various techniques were used to train and evaluate a model based on loan risk. Such model is very important to identify the creditworthiness of the borrowers. 
    The accuracy, precision and recall scores of the model are as follows:
        - Accuracy: 99% 
        - Precision:
            Healty Loans: 100% (100% of the loans that were predicted healthy were in fact healty loans)
            High-risk Loans: 85% (15% of the loans that were predicted high-risk were actually heatly loans)
        - Recall:
            Healty Loans: 99% (1% of loans were not captured as healthy loans when they should have been)
            High-risk Loans: 91% (9% of the loans were not caputred as high-risk when they should have been)
    In summary, this model can be used for predictin healthy loans. However, a different model might have to be used to predict high-risk loans.Without additional knowledge on the particulars of the loans, a clear decision cannot be made if it is acceptable that 15% of the predicted high risk loans were not high-risk and that 9% of the high-risk loans were not categorized as such.