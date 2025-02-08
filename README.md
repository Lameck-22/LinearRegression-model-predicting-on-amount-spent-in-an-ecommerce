# Linear Regression model predicting the amount spent in an Ecommerce
This project's aim was to predict the yearly amount spent in an Ecommerce, Linear regression model was used trying to achieve this.
First I installed scikit-learn using
'''
%pip install scikit-learn
'''
- From sklearn I imported various packages like: 
  -linear_model
  -metrics
  -model_selection

- linear_model was used to perform linear regression and find the best fit line
- model_selection was used to train_test_split the data
- metrics was used to test the accuracy of the model, in this case we used r2_score which rates the model between 0-1; when the value is higher then the model is good

- The dependent variable was the yearly amount spent while the dependent variables were; Avg. Session Length, Time on App,Time on Website,Length of Membership.
- This was a multilinearregression moddel
