# MNIST Pairwise Experiment, Confusion Range and MNIST "de-confusion" attempt. 

In this experiment, I am going to take a look at how a very simple one layer NN performs when trained on separate digit pairs in MNIST dataset. 

Next, I am going to identify signs of "confusion" when the same simple NN is trained on all 10 digits and gets the digit wrong. 
We will see that in such cases top two weight in the final output layer are very close in value, compared to when NN classifies a digit correctly.

Finally, I am going to build a simple heuristic model where we will allow our NN take a "second guess" in "confusion range" cases when we can tell it is being not sure about a result and normally would misclassify a digit. 
