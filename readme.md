**Analyzing Rotten Tomatoes Reviews with Naive Bayes Algorithm**

This Python code uses the Multinomial Naive Bayes algorithm to classify movie reviews as either "fresh" or "rotten" based on their sentiment.

**Libraries Used**
The following libraries are used in this code:

NumPy
TensorFlow
Keras
Pandas
Seaborn
PyLab
Matplotlib
Scikit-learn
NLTK
WordCloud
BeautifulSoup

**Code Execution**
To execute the code, simply run it in a Python environment with the required libraries installed.

The code imports a CSV file with movie reviews, applies some preprocessing to the data, and splits the data into training, validation, and test sets. The Multinomial Naive Bayes algorithm is then used to train a model on the training set, which is evaluated using the validation set. Finally, the performance of the model is evaluated on the test set, and a confusion matrix is generated to visualize the results.

The code also includes a bar graph that compares the accuracy of the model when using different values of alpha for the Laplace smoothing.
