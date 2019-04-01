# GridSearchCV

Basically what i did was test logistic regression model on the dataset having non linear separation.

It gave a good result .

But when the same model was done on SVM we got a pretty bad result ?

This is beacuse of not choosing the best set of hyperparamters.

GridSearchCV does that for us.
This takes input of all the testing values you want to test your model and gives us the best possible set of parameters which will give us the best result on the model.

Using GridSearhCv we got an accuracy of 97%.
