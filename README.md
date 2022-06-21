# Setting up confusion matrix demo with sklearn
I recently helped create a demo for a customer that required a confusion matrix. I could not access the customer's data. However, accessing the customer data is not necessary to complete the demo. It is more important to maintain data security. I just needed to understand the underlying features and structure of the data. 

Here is how I was able to quickly help the customer set up a confusion matrix demo using sklearn:

1. **Get Sample Data:** You have the choice to use existing data or make some data.  I created data using two methods.  In method 1, I create data using the random library.  This method enables me to make as much data as I want.  For this demo, I set the data to 23,000 random values of either 0 or 1. in method 2, I created a list of labels for ground truth and predicted values.  I shuffled the labels to mix them up.  If you commit to method 2, you should have a data frame with shuffled labels. You can provide your custom label names in the code blocks.

2. **Create Array:**. You now have a Pandas data frame with fake data.  Next, convert the True and Predicted values to NumPy arrays.

3. **Invoke sklearn methods for confusion matrix:** This is straightforward.  Use sklearn methods for confusion matrix and model performance metrics.  I include visualization examples using matplotlib and seaborn.

**Bonus:** 
1. I have included a notebook showing how to use the built-in iris dataset. If you don't want to create data, you can use the included iris data set with sklearn. I have included a notebook to show how to quickly extract the iris sample dataset to a Pandas data frame.

2. I included two notebooks showing the use of a confusion matrix with the iris dataset.  These examples are from the sklearn documentation.
