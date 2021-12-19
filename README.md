# About the Model
This is the Face dataset classification project with Jupyter notebook, Python. For this project, we will use the Olivetti faces dataset. The 'sklearn.datasets.fetch_olivetti_facesfunction' is the data fetching, caching function that downloads the data archive from AT&T. There are ten different images of each of 40 distinct subjects.

So, you should download Jupyter notebook, Python and sklearn for this project

Jupyter notebook : https://jupyter.org/install
Python : https://www.python.org/downloads/
sklearn : https://scikit-learn.org/stable/install.html

# About the Hyperparameter
In sklearn library, there are some kinds of way to learn that contain many parameters. And I will use LogisticRegression for learning. 

If you want to know about Hyperparameter of LogisticRegression, see this link

https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html


# About my codes

By reducing the tol value and C value, the accuracy was further improved by reducing the value of tolerance.
By setting fit_intercept to False, the constant was removed from the decision function.
The weight was automatically adjusted by setting class_weight to 'balanced'.
In addition, by increasing the max_iter value, the maximum number of iterations it takes for the solver to converge is increased.
And the multi_class is changed to 'ovr' to maximize accuracy.
