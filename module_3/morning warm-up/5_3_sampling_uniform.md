### Import packages
`import pickle`

`import pandas as pd`

`import seaborn as sns`

##### 1.  We want to sample 3 variables from the uniform distribution between 0 and 1 (0, 1). 
##### The first variable should be picked 40% of the times, the second 30% of the times, and the third 30% of the times. (Think how you can use the cumulative sum to your assistance)

- Example: Imagine you are you are spinning a wheel with ten even sized wedges. Each wedge is also numbered 1-10.
  - If you got any number between 1 to 4 you would increment var. 1 
  - If you got any number between 5 to 7 you would increment var. 2 
  - If you got any number between 8 to 10 you would increment var. 3 

`use np.random.uniform`


##### 2. Run a simulation for 100000 steps. Sample at each step from uniform distribution to decide which variable was picked. Store the results into a dictionary - incrementing the selected variable by 1 at each step. 


##### [OPTIONAL] 3. save the dictionary in a pkl file 
- Read about pickle files!
`use open`

`use pickle.dump`

`use .close()`

##### 4. Open the saved file (check that what you have loaded is the same as your original dictionary)

##### 5. Push to github your notebook and the pkl file. 
