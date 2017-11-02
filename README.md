# MLPython
A basic program to recognize Iris flowers. 

# Step 1 = Collect Data 

Using a well known dataset that contains 150 samples of Iris Flowers. 
This specific data set comes pre loaded in scikit learner. 

Each Sample has a label - Iris Setosa , Iris Veriscolor, and Iris Virginica. 
Each Sample has it's own set of features - Petal length/Width and Sepal Length/Width. 

Type of Learning - [Supervised Learning]
If we didn't have labels it would be called Unsupervised Learning but since it has labels it would be catagorized as Supervised learning. 

# Step 2 = Pick the Model 

Given the numerous amount of Machine learning algorithms, How do you know which one to utilize? 
Our goal is to catagorize a flower , whether it be an Iris flower or NOT an Iris flower.

This would fall under a classification model therefore we need to use a classifer! 
But..what type? 

It depends on the size of your data! Currently , If you have a lot of data , deep neural networks outperform many generic ML algorithms.
In our case , we only have 150 samples so we'll use a Linear Classifier. 

We'll set the clas parameter to 3 and move on to training the model!

# Step 3 = Train the model 

Since we're using a classifer , We just need to call the FIT method on our object to trian our model.
FIT is a training algorithm that allows us to input our training data into a model , finding patterns in the data. 

Now when we input a new flower , it will be able to determine whether or not it's an Iris flower! 



