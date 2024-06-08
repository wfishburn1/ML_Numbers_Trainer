After comparing the results of using two hidden layers versus three or one, I have concluded that there is a consistent trend between these parameter changes; particularly in regard to training and validation accuracy rates. Increasing the amount of hidden layers initially causes a rise in both training and validation accuracy, due to the model learning complex patterns in the data; the downside is, if the added layers are too complex, the model may begin to "overfit" the training data, negatively impacting validation accuracy. Overfitting is essentially when the ML model aims to memorize its training without weighing in newly introduced or unseen data. For this reason, test accuracy may also decrease. On the other hand, reducing the number of hidden layers appers to cause a decrease in both training and validation, as well as test accuracy.
