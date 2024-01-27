Homework 1:
• We mentioned that perceptron converges if the data is linearly separable. Try sklearn per-
ceptron model for versicolor and virginica, with sepal length and petal length. What do you
observe?
• We created My Perceptron class for only 2 inputs. Extend this code for 3 inputs. Investigate
the iris data set and choose 3 features to classify setosa and versicolor using your code. Notice
that you cannot easily plot the decision boundary now since the data is 3-dimensional, but you
can still compare the actual and the predicted labels to see how your algorithm is performing.
• Try to generalize My Perceptron code so it could be used for any number of inputs. (Hint:
Recall, that for a list w we can use w[-1] and w[:-1] to access the last value in the list and
all the values expect the very last value. Also, use np.dot, NumPy dot product, to compute
the pre-activation value of z.)
