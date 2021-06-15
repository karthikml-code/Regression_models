Multiple Linear Regression has the same code as Linear, but the features are more here. 

We use 5 different methods in Multiple linear regression
1)	All in – uses all the variable. Can be used only if you have prior knowledge on the model
2)	Backward elimination – select the significance level to stay in the model. Usually sl=0.05. fit the model with all predictors. Consider the predictor with highest p value. If p>sl, remove the predictor and start with the others. Or else finish the model
3)	Forward elimination – as same as the backward elimination, start with sl=0.05. Fit all the simple regressor and take the one with the lowest p value. Then fit all possible models and add one predictor. Consider the predictor with the lowest p value. if p<sl then start adding another predictor else finish the model
4)	Bidirectional elimination – need to have two significance value as slstay and slenter with 0.005 for both. Both forward and backward happens simultaneously. Forward selection, new variable with p<slenter has to enter and backward selection, old variable with p<slstay has to stay.
5)	Score comparision – build all possible models and do a score comparison. It is a tedious process. for 4 feature data we need to 2**n -1 which 15 models for 4 feature data.

2,3,4 are the stepwise methods

y= b0 + b1*x1 + b2*x2 + … +bn*xn

Here x1, x2 .. xn are the independent variable here. 
b1 , b2 .. bn are the co-efficient values
b0 is the constant value.
