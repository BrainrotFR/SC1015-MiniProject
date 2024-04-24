# Welcome to our SC1015 repository 
SC1015 (Introduction to Data Science & Artificial Intelligence) Mini Project  
# About
This project uses the laptop price dataset from Kaggle to predict laptop prices based on their specificatons. For detailed walkthrough, please view the source code in the following order:

1. Data Extraction & Cleaning
3. Data Visualisation
4. Linear Regression 
5. Neural Network
6. Random Forest Regression
7. K-Nearest Neighbour Regression

# Contributors
- @BrainrotFR - Neural Network
- @JmeMei - Random Forest Regression
- @uwubrain - K-Nearest Neighbour
- @everyone - Data Extraction & Cleaning, Data Visualisation, Linear Regression

# Problem Definition
  * What attributes affect the laptop's prices the most?
  * Can we predict the price of a laptop given those attributes?

# Models Used
 1. Linear Regression
 2. Neural Network
 3. Random Forest Regression
 4. KNN Regression

# Conclusion:
Apple is not the most expensive brand. Its Razer. 

The top 4 attributes that contributes to the increase of price.
 - Ram: 0.74
 - GPU: 0.44
 - Screen resolution: 0.39
 - Operating system: 0.29

Linear regression: Better with only 4 attributes
Keras: Better with only 4 attributes
Random Forest Regression: Better with all attributes
Keras: Better with only 4 attributes
K Nearest Neighbour (KNN) Regression: Better with only 4 attributes

Reasons why Random Forest Regression, Kera, and K Nearest Neighbour (KNN) is better than linear regression.

- Found out that KNN would be a better linear regression for this dataset and would recommend these to the companies as it can help them with pricing strategies to maintain its competitive prices.
- Recommend companies to use the top 4 variables to accurately predict the price prediction.

- A lower MSE does not necessarily lead to better predictions.For example, by using log function, even though the MSE got lower, it also magnify the  differences between small values which may amplify the impact of outliers, leading to a worse prediction.

# What did we learn from this project?
* Lower MSE does not necessarily lead to better predictions
* Neural Network using Keras and Tensorflow
* Random forest Regression
* KNN regression
* Using Github to share and collaborate on code
* Concepts and techniques to achieve better MSE
  * etc. Bagging, normalising data using Log function

# Reference
* https://www.geeksforgeeks.org/random-forest-regression-in-python/
* https://www.tensorflow.org/tutorials/keras/regression
* https://machinelearningmastery.com/regression-tutorial-keras-deep-learning-library-python/
