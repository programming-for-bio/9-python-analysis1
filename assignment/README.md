
### Assignment

1. Fork the `9-python-analysis1` repository and create a new jupyter-notebook 
in the assignment directory. 

2. In your notebook use Markdown text to create a title and explain the content
of your notebook to document your code. 

3. Use the `records` library to download a series of occurrence records for
a taxon of your choice over a period of time, or use *Bombus* as we have been
using in class. 

4. Try to apply a machine learning method from the `scikit-learn` library to 
the data in the dataframe of your `records.Epochs` object. This will involve
the following steps. 

	1. Select appropriate columns and format the data so that you have an 
	column of labels (y) and one or more columns of features (X). Then split
	it into a training and test data set. 

	2. Select a machine learning class from scikit-learn. For this you can 
	choose from many available options. Look to your reading for examples, or
	to the scikit learn documentation. The best way is to find examples of the
	model being applied and to substitute your data in for the example data. 

	3. Create an instance of that class. 

	4. Train your model on your training data set (call `.fit()` with your model).

	5. Get predictions by applying your model to the test data set (call 
	`.predict()` with your model). 

	6. Measure the accuracy of your model by comparing the predicted values to
	the actual labels in your test data. 

	7. Describe the model that you tried to apply and the question that you 
	tried to answer (e.g., I tried to use these features of the data to predict
	this). How well do you think the model worked?


5. Commit and push your notebook to the assignments directory and make a pull
request to the class repository. 

