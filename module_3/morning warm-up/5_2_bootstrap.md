### Import packages
`import numpy as np`

`from __future__ import division`

### 1. bootstrapping !!
##### Let's say we have a pandas dictionary (our sink) and inside we have one urn (with red and white balls). The urn has 40 red balls 60 white 

##### What's the probability to pick a red ball with replacement 3 times in a row ? 

- Can you answer this question theoretically? 


##### lets create a simulation running 1000/10000/100000 iterations and count how many times we got three reds in a row.

`sink : {'urn': {'red': 40, 'white':60}}`

`use np.random.rand`


### 2. push to github (are you close to the theortical distribution ??? If not check again!)


### [optional] 3. How will you create the same simulation without replacement ? 
