K nearest neighbhor is a classification method to copy your neighbhors' behavior. It could be used as a simple baseline model to compare more advanced models with.

Let's create our own toy example. 

Creating the data:
(Notice that generally the scale matters when we have different units in our data)

1

Let's create a board and throw darts on it.

	- Throw 1000 darts in the rectangle [0, 20] X [0,25]
	-  Split the rectangle to 4 equal parts.
		- Use axvline and axhline 
	-  We are going to uniformaly hit each part. If we 		hit the top left, we label the point with 70% 		red, and with equal chances blue, green and 		balck. Choose the dominant color for the other 		parts.
	-  Save both the point (x, y) position and its 		label (color) to a list ('pt_li').
	- Plot the board
This should look like:

![](knn_ex.png)
	

2

Imagine you were to create a function to calculate distances by yourself. For each new point (test) you would need to calculate the distance to all points, sort them in ascending order, choose the first k, and assign a label accordingly. This is a very expensive computation. Luckily there are cool algorithms to make this process faster. 

(If interested explore for example https://www.cs.cmu.edu/~ckingsf/bioinfo-lectures/kdtrees.pdf) 

- we are just going to use ready made KNN functions.
- Split the data to validation folds.

Use:

```
from sklearn.neighbors import KNeighborsClassifier

KNeighborsClassifier

```

3

It's up to you to use cross validation to find the best K. Try only the options 1-5.


4

Throw 15 new darts uniformaly on the board and label them. Plot it! Does it work? 


5

What is your accuracy?

6

Can you draw a confusion matrix? 
     