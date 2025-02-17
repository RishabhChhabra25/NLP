Python code that uses machine learning and natural language processing to identify hate speech and categorise tweets.

**Dataset and Flow**

To accomplish this, we use a publicly accessible dataset that CrowdFlower has made available and employ NLP algorithms. We outline the steps in our method, which begin with dataset analysis and go to text pre-processing to produce a cleaner dataset for feature engineering, our next step. In order to classify the data set into hate speech, offensive language, and neither, we lastly perform a thorough analysis using the NLP LSTM model.

class label

0 - hate speech 
1 - offensive language 
2 - neither


**Conclusion**

We have found that the LSTM model can accurately predict hate speech with 89% accuracy. The next steps would be to optimise the hyperparameters for increased accuracy, A careful analysis of the features and errors could lead to efficient feature extraction methods and assist in fixing the present problems in this field.

