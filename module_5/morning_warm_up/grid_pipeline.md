### Let's practice creating a pipeline where we gridsearch through hyperparameters on a transformer AND a model

1. Read your csv file into a dataframe (wine_full_train.csv)
2. Import necessary libraries

```
from sklearn.decomposition import PCA 
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.neighbors import KNeighborsClassifier
from sklearn.preprocessing import StandardScaler
from sklearn.pipeline import Pipeline
```

3. Train/test split data
4. Build pipeline steps including StandardScaler, PCA, and KNeighbors
5. Set gridsearch params for PCA (try 5, 6, 7) AND KNN (try 7, 11, 15, 19, 23)
6. Check which parameters work best!