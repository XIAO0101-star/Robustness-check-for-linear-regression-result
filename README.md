The research aims to utilise machine learning techniques to examine the relationship between EUR/USD currency pair and other economic indicators and make predictions of its valuation based on these indicators.
To check the robustness of the linear regression model, I used neural network to build up another model to predict the test dataset. If the Student's t-test result is not statitically significant, the linear regression model is robust.
Student’s t-test result for Neural Network & Linear Regression
	Student’s t-test result (p value)
Linear regression vs. Actual value	0.15282
Neural network vs. Actual value	0.458933
Linear regression vs. Neural network	0.216757
The Student’s t-test value is not statistically significant. 
Robustness_test.ipynb: the main program - including data processing, model training and testing
training.csv: train dataset
test.csv: test dataset
Neural Network result.csv: prediction result output
