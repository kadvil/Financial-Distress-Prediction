# Financial-Distress-Prediction
An end-to-end ML portfolio and analysis using multiple models on a Kaggle competition dataset (Give me some credit) exploring delinquency based credit default. Several algorithms were combined in a voting classifier to achieve an AUC-ROC score of 0.86825 (within 0.13% of highest Kaggle leadership board score).

Data Obtained from : https://www.kaggle.com/c/GiveMeSomeCredit


## What are we predicting in this project? Why are we predicting it?
<br/>

<font size=3>
    
With the given dataset, we will be predicting for the likelihood of the borrower to fall into financial distress and default on a loan based on their past credit behavior and other variables. Predicting an individual's financial distress is important for several reasons:

- **Risk Management**: Banks and other financial institutions need to manage the risk of default by their borrowers. Predicting an individual's financial distress can help banks identify customers who are at a higher risk of defaulting on their loans. This allows them to take proactive measures to mitigate potential losses, such as adjusting interest rates or reducing credit limits.

- **Credit Decisions**: Banks use credit scores and other indicators of financial health to make lending decisions. Predicting an individual's financial distress can provide additional information to help banks make more informed credit decisions. Banks can use this information to determine whether to approve a loan, set interest rates, or adjust other terms of the loan.

- **Portfolio Management**: Banks need to manage their loan portfolios effectively to maintain their financial health. Predicting an individual's financial distress can help banks identify potential risks in their loan portfolios and take steps to reduce their exposure to these risks. This can help banks avoid losses and maintain their financial stability.

- **Compliance**: Banks are subject to regulatory requirements that require them to manage their risks effectively. Predicting an individual's financial distress can help banks comply with these regulations and avoid penalties or other regulatory action.

- **Customer Service**: Banks have a responsibility to provide good customer service to their customers. Predicting an individual's financial distress can help banks identify customers who may be struggling financially and provide them with the support they need to manage their finances effectively. This can help build trust and loyalty with customers and improve the overall customer experience.

    With this dataset, predicting an individual's financial distress can help banks identify customers who are at a higher risk of defaulting on their loans. This allows them to take proactive measures to manage their risks and avoid potential losses, while also providing support to customers who may be struggling financially. The **AUC (Area Under the Curve)** is a commonly used metric to evaluate the performance of binary classification models, such as those used to predict financial distress. The AUC represents the probability that the model will correctly rank a randomly chosen positive example (i.e., a case of financial distress) higher than a randomly chosen negative example (i.e., a case without financial distress). This is explained more in next section.
