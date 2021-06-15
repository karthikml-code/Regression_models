It is a type of ensemble learning. It is like taking multiple algorithm or single algorithm multiple times to enhance or boost the predictability.

Basically, pick a k data point and build decision trees associated with that k data point. Choose the number of trees and repeat the above steps. 
For a new data point, make all the trees to predict the y value. Then take the average of all the predicted values to the new data point. This increases the accuracy.

Powerful and accurate, good performance on many problems, including non linear
No interpretability, overfitting can easily occur, need to choose the number of trees
