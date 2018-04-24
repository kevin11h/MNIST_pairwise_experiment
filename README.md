# MNIST Pairwise Experiment, Confusion Range and MNIST "de-confusing" attempt. 

In this experiment, I am going to take a look at how a very simple one layer NN performs when trained on separate digit pairs on MNIST dataset. 

Next, I am going to identify signs of "confusion" when same simple NN trained on all 10 digits and gets the digit wrong. 
We will see that in such cases top two weight in the final layer are very close in value, compared to when NN classifies digit correctly.

Finally, I am going to build a simple heuristic model where we will allow NN take a "second" guess in cases when we can tell it is being confused and normally would misclassify a digit. 
