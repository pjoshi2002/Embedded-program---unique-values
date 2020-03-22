# 1) Embedded program for categorical data (unique-values) using keras

import pandas as pd
import numpy as np
Car_def= pd.read_csv("Data",names ("length", "weight",...))
Car_def.head(2). transpose ()
Car_def.dtypes
Car_def.iloc[:,1:15000]

Car_def.describe().unique()
for categorical_var in categorical_vars:
model = Sequential ()
no_of_unique_cat = df_train[categorical_var].nunique()
embedding_size=int(min(np.ceil((no_of_unique_cat)/2,50)))
vocab=no_of_unique_cat + 1
model.add(embedding (vocab, embedding_size, input_length=1))
model.add(Reshape.(target_shape=(embedding_size)))
models.append(model)

# 2. 
model_rest=sequential ()
model_rest.add(Dense(15001,input_dim=1))
model.append(model_rest)
full_model.add(Merge(models, mode = 'concat'))

















