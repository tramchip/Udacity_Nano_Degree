Disaster Response pipeline repo for Udacity Data Science 

NLP pipeline has 3 stages : Model, Train , Predict 

Feature union is a class in scikit-learn’s Pipeline module that allows us to perform steps in parallel and take the union of their results for the next step. A pipeline performs a list of steps in a linear sequence, while a feature union performs a list of steps in parallel and then combines their results.

feature unions are built using a list of (key, value) pairs, where the key is the string that you want to name a step, and the value is the estimator object.
