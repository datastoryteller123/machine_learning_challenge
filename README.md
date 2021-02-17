## Machine Learning Challenge

# Machine Learning Code
  # Logistic Regression
  exoplanet.csv - dataset
  Log_Reg_model_1: Max iterations used 100, which the Training/Testing score with an approximate score of .51
  Log_Reg_model_2: Max iterations used 1,000, which the Training/Testing score with an approximate score of .58
  Log_Reg_model_3: Max iterations used 10,000, which the Training/Testing score with an approximate score of .85
  model_1: The Jupyter Notebook used to run the code.
  
  The Logistic Regression would not be the optimal choice for Machine Learning, based on the 3 Training/Testing sets, as even though the third set scored a .85, the testing and      training took too long, due to the size of the max iterations.

  # SVM
  exoplanet.csv - dataset
  model_2: The Jupyter Notebook used to run the code.
  SVM_model_1: This would be the best model compared to the Logistic Regression approach, as the test/training score with an approximate score of .85 and the best param and score     with {'C': 10, 'gamma': 0.0001} scoring .87. This model was much faster than model_3 of the Logistic Regression, as it didn't have a max iterations of 10,000.
