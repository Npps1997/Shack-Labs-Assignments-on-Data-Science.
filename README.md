Shack Labs Internship Assignment.
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

Assignment 1. Machine Learning model performances- Used r2 score as performance metrics:(House Price Prediction)

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

Assignment 2. Product Matching using Title Similarity model.
    
I have choosen the technique of title similarity model by using Universal Sentence Encoder for finding the Embeddings and used numpy for finding the title similarity.
