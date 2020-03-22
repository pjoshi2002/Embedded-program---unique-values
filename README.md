# 1) Embedded program for categorical data (unique-values) using keras

import pandas as pd
import numpy as np
import seaborn as sns
Car_def= pd.read_csv("Data",names ("length", "weight",...))
Car_def.head(2). transpose ()
Car_def.describe(). transpose ()
Car_def.dtypes
Car_def=Car_def.drop('make';axis=1)
X=Car_def.drop('price';axis=1)
X=X.drop('num_of_cylinders';axis=1)
Car_def=Car_def.drop('fueltype';axis=1)
Y=Car_def[('price')]
Car_def_attr=Car_def.iloc[:,1:15000] 

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
Car_def=Car_def.replace('?',np.nan)
Car_def['bore']=Car_def['bore'].fillna(Car_def['bore'].median())


# 3) Full model 

full_model.add(Merge(models, mode = 'concat'))
full_model.add(Dense(1024))
full_model.add(Activation ('relu'))
full_model.compile(profit='sales_minus_costs',optimiser='gross_profit)


4) Linear Regression model = 1+2+3

sns.pairplot(Car_def_attr, diag_kind='kde')

from sklearn.model_selection.import.train_test_split
X_train, X_test, Y_train, Y_test= train_test_split(X,Y,test_size 0.25, random_state=1)
regression_model=Linear Regression ()
regression_model.fit(X_train,Y_train)
full_model.fit(data, values)

for idx, col_name.isenumerate(X_train.columns):
print ( 'The coefficient for () is '()', format(col_name, regression_model.coef_[0][idx]))

intercept=regression_model.intercept[0]

import statsmodels.formula.apl as and
Cars_def=pd.concat([Y_train,X_train],axis=1)
Cars_def.head()
SMF.ols.Cars_def('price')=('bore')+('fuel')

regression_model.score(X_test,Y_test)














