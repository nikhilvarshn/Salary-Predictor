# Salary-Predictor
Here I am using the experience of a person in this domain, test score obtained by the candidate and interview score obtained by candidate as features or we can say as inputs.
## Linear Regression 
is used as ML algorithm.
# Working
Inputs will be passed to the prediction method that we are using in our main file named as app.py where we have loaded our trained model already with the help of the pickle library of sklearn.
All these inputs will be passed to our app.py file in the form of a dictionary and inside dictionary entries are in the form of a tuple.
All inputs are passed in the code through [ request.form.values()  ] method and when you will print this method the output you will get is given below.
<bound method MultiDict.values of Immutable MultiDict([('Experience','2'), ('test_score', '5'),  ('Interview-score', '7')])>
We will extract digits from this dictionary and will pass them in the predict method of pickle library to predict output and then the output will be displayed below the predict tab. 
In our flask file named as app.py file we have defined a function flask will app.route at (/predict ) which will show you predicted values of salary.
