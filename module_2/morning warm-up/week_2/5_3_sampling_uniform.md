### Import packages
`import pickle`

`import pandas as pd`

`import seaborn as sns`

### 1. create three variables coming from the uniform distribution x1 = 0.4, x2= 0.3, x3 = 0.3 (think of cumulative)

`uni_dict: {'x1': 0, 'x2': 0, 'x3':0}`

`use np.random.uniform`


### 2. run a simulation 100000 sampling at each step to decide which variable was picked. Store the results into a dictionary (uni_dict) 

- Read about pickle files!

### 3. save the dictionary in a pkl file 
`use open`

`use pickle.dump`

`use .close()`

### 4. open the saved file  (check that what you have loaded is the same as your original dictionary )

### 5. push to github your notebook and the pkl file 