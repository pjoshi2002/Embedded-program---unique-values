# 1) Embedded program for categorical data (unique-values) using keras

import pandas as pd
import numpy as np
Car_def= pd.read_csv("Data",names ("length", "weight",...))
Car_def.head(2). transpose ()
Car_def.dtypes
Car_def=Car_def.drop('make';axis=1)
Car_def=Car_def.drop('fueltype';axis=1)
Car_def.iloc[:,1:15000] cz

Car_def.describe().unique()
for categorical_var in categorical_vars:
model = Sequential ()
no_of_unique_cat = df_train[categorical_var].nunique()
embedding_size=int(min(np.ceil((no_of_unique_cat)/2,50)))
vocab=no_of_unique_cat + 1
model.add(embedding (vocab, embedding_size, input_length=1))
model.add(Reshape.(target_shape=(embedding_size)))
models.append(model)

# 2) Embedded program for other data (unique data other than categorical data )


model_rest=sequential ()
model_rest.add(Dense(15001,input_dim=1))
model.append(model_rest)
Car_def['cylinder']=Car_def['num_of_cylinders'].replace({'one':1,'two':2,'three':3,....'fifteen thousand': 15000})
Car_def['horsepower']=Car_def['horsepower'].astype('float64')

full_model.add(Merge(models, mode = 'concat'))
full_model.add(Dense(1024))
full_model.add(Activation ('relu'))
full_model.compile(profit='sales_minus_costs',optimiser='gross_profit)
full_model.fit(data, values)















