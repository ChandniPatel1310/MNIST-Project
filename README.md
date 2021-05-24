# MNIST-Project
. Theory:-
 The MNIST database contains 60,000 training images and 10,000 testing images.
For this model, we use data set from the sklearn datasets. 

Logistic Regression:-
In statistics, the logistic model (or logit model) is used to model the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead or healthy/sick. 
This can be extended to model several classes of events such as determining whether an image contains a cat, dog, lion, etc.
 Each object being detected in the image would be assigned a probability between 0 and 1, with a sum of one.
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist.
 In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (a form of binary regression). Mathematically,
A binary logistic model has a dependent variable with two possible values, such as pass/fail which is represented by an indicator variable, where the two values are labeled "0" and "1". 


Steps for the Model:-

Step1: Fetching the Data:
Fetch dataset from openml by name or dataset id.
Datasets are uniquely identified by either an integer ID or by a combination of name and version (i.e. there might be multiple versions of the ‘iris’ dataset).
Please give either name or data_id (not both). In case a name is given, a version can also be provided.

Step 2: Visualization:-
For plotting, just use %matplotlib inline. 
Select any data from the dataset and visualize it. 
Before visualize, reshape the data.

Step 3: Training and Testing:-
There are 70000 data in the dataset.
In both x,y variable, put 60000 for training and 10000 for testing.
Do random shuffling. NUM py is use for random shuffling.
NUM py:
NumPy is a python library used for working with arrays.
It also has functions for working in domain of linear algebra, Fourier transform, and matrices.
NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely.
NumPy stands for Numerical Python.

Step 4: Classification:-
Classifying the data in the binary.

Step 5: Predict Data:-
Predict the data using logistic regression.

Step 6: Accuracy:-
Check accuracy for our model.

