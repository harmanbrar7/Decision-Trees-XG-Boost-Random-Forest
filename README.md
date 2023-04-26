# Decision-Trees-XG-Boost-Random-Forest
information gain, one-hot encoding, entropy and decision tree analysis with multiple examples 

*All ipynb files have explanations and mathematical models included for ease of access*

*you may need to adjust your file path from the utils.py file, in most cases just remove "images/" from the code
if you are running it on Jupyter otherwise leave it in for any other IDE.

9 images are provided to show the animal features as explained below

3 jpegs are provided to show the output of the decision trees and the training examples

In a decision tree, we decide if a node will be split or not by looking at the information gain that split would give us.
The entropy shows the degree of predictability of an event
We use a dataset involving the facial features of animals and training a model
We can use one-hot encoding to encode the categorical features



The 2nd file is a tree ensemble that takes in data of heart patients and predicts their likelyhood of getting cardiovascular disease.
Use the heart.csv file
In this:
Use Pandas to perform one-hot encoding of a dataset
Use scikit-learn to implement a Decision Tree, Random Forest and XGBoost models
