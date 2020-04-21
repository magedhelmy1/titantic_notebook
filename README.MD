This notebook is based on the Titanic dataset.

This notebook contains a Data pre-processing cells which includes

-> dropping column names

-> grouping names in the Name column

-> Hot encoding the embarked column

-> Hot encoding the Cabin column

-> Filling out the missing values of age, fare and embarked

-> Hot encoding the Sex column

-> Scaling the train and test dataset


It turns out that dropping age, name and fare has little to do with increasing accuracy of the data.
So you can comment out blocks and experiment with different blocks

I have training a general Random Forest and a Shallow Neural Network using Keras to experiment with accuracy

I have created a "Test File" which contains the actual survival rate. So you can experiment locally, without
always having to submit to Kaggle. You can submit to Kaggle ones your happy with your algorithm results.
