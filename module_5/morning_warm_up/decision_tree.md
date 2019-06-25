Where did decision trees come from? well, can you perform k-nearest neighbors on observations with different dimensionality? with trees you can!

Let's try to understand how to use a decision tree.

Imagine we are doctors and we need to decide if a person is in the risk group for having 'chompapia' or not. 

We have a dataset with each row containing charactristics of a person. (Age, blood presuare etc)

1. Read the ```chompapia.csv``` dataset
2. If the person has minimum systolic blood pressure > 120 tag that person has having chompapia else continue
3. If the person's age > 62? put the person in
tag has no chompapia. Else continue. 
4. If the person has heart rate > 135 or < 35 tag has 
chompapia. Else tag as no chompapia.

We just created a decision tree! 

5. Load the ``` tree_true_label.csv```
6. Check your accuarcy/Flase positive rate/False negative rate
7. Draw the tree and its splits on a paper (not python).

Few of the questions that come into mind:

- we have chosen a certain set of rules to make the splits. Did we choose the right splits? (e.g. maybe the age should be 57?) Did we choose the right order? what would be the a good criterion to make these splits? explore the idea of entropy if interested! 

- If we continue to grow the tree more and more we could find ourselves with one observation per node. This would mean overfit! How would we account for that? 

- How would you get the probabilities of the tree?  
  