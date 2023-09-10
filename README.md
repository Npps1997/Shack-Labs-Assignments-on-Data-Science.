# Shack Labs Internship Assignment.
1. House Price Prediction.
2. Product Matching using Title Similarity model (Used Universal Sentence Encoder)

Libraries and Frameworks used:

* Pandas
* Numpy
* Scikit-learn
* Matplotlib
* Seaborn
* Math
* Tensorflow
* Tensorflow hub
* PyTorch

## Assignment 1. Machine Learning model performances- Used r2 score as performance metrics:(House Price Prediction)

1. Linear Regression: This model assumes linear relationships between the features, hence it gives a straight line during fitting.

    * Mean: 4549.916183822997
    * Standard Deviation/Error: 829.863743230809
    * Accuracy/r2 score = 93%
    
2. Decision Tree Regressor: This model is prone to overfitting but supports non-linearity. Hence it gives better results than Linear Regression.

    * Mean: 3644.4593913710487
    * Standard Deviation/Error: 604.0465859327052
    * Accuracy/r2 score = 97%
    
3. Random forest Regressor: This model is a combination of multiple decision trees hence it gives the average result of all the decision trees present inside it. It also handles the overfitting problem due to its randomness nature, thats why it gives better results than a single decision tree.

    * Mean: 2396.6078387186235
    * Standard Deviation 493.3366982557698
    * Accuracy/r2 score = 98.7%

## Assignment 2. Product Matching using Title Similarity model.

### Problem Statement
Match similar products from the Flipkart dataset with the Amazon dataset.


### Overview
Here we have a data-set containig titles and descriptions of the products of flipkart and amazon. Some records may do not have any description.


### Goal
Our goal is to come up with a way to find similar products to any new unlabled product based on its title an description.

### Approach

1. EDA
2. Conversion of text into vectors.
3. Calculation of similarity
4. Extraction of similar products.
5. Comparison of products.
    
I have choosen the technique of title similarity model by using Universal Sentence Encoder for finding the Embeddings and used numpy for finding the title similarity.

### Universal Sentence Encoder
* It is one of the most well performing sentence embedding techniques proposed by Google. It is a pre-trained model used for finding embeddings.
* For this we need to install tensorflow and tensorflow hub.
* The model is available to us via tensorflow hub.

### Similarity using numpy
https://numpy.org/doc/stable/reference/generated/numpy.dot.html

reference: https://forbytes.com/blog/product-matching-in-ecommerce/
