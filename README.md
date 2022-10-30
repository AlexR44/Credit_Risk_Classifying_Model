# Credit Risk Classifying Model

![](https://www.paymentsjournal.com/wp-content/uploads/2020/06/16364-scaled.jpg)

Credit risk presents a classification problem that is inherently imbalanced, given that healthy loans easily outnumber risky ones. 

In this analysis notebook, a logistical regression model is first built and trained with 75% of an imbalanced dataset of historical lending activity from a peer-to-peer lending services company to help identify the creditworthiness of borrowers. The remaning 25% of the historical data is used for testing of the model. 

As a second phase in the analysis, the training data is balanced by random oversampling, a new logistical regression model is built and trained with this new dataset, and new predictions are made on the remaning 25% of the historical data.

The accuracies of both models are ensuingly compared to assess their performance.