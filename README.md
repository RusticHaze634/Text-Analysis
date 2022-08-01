<h3 align="center">Text Analytics</h3> 
<h3 align="center">( Sentiment Classification  )</h3> 
:thought_balloon:

### ABSTRACT :
----------------
_This is a text classification task - sentiment classification.  
Every document (a line in the data file) is a sentence extracted from social media (blogs).   
The goal is to classify the sentiment of each sentence into "positive" or "negative"._  
**_Accuracy of this model: 97.91%_**

### DATASET:
----------------
- The training data contains 7086 sentences, already labeled with 1 (positive sentiment) or 0 (negative sentiment).
- The test data contains 33052 sentences that are unlabeled.
- The submission should be a .txt file with 33052 lines.
- In each line, there should be exactly one integer, 0 or 1, according to the classification results.


### SOLUTION APPROACH:
----------------
```
 Text Analytics
     NLP + ML (Naive Bayes Theoerm)  
     Ensemble Learning
```
### STEPS:
----------------
**1. EDA and Pre-processing**
  - Bag-of-Words method
  - Feature Extraction
  - Removing the low frequency words
  - Count the features
  - Remove Stop Words
  - Stemming
  
**2. Balancing the unbalanced data classes**
**3. Naive Bayes Model for sentiment Classification**
  - Dataset segmentation 
  - Model building
  - Prediction test
  - Classification report
  

### DATA VISUALIZATION:
----------------

- Sample Data:

![attachment:sample%20data.png](https://github.com/RusticHaze634/Text-Analysis/blob/main/Images/sample%20data.png)


- Positive and Negative Class-wise Data Distribution Bar Plot :

![attachment:01.png](https://github.com/RusticHaze634/Text-Analysis/blob/main/Images/01.png)

- The Occurances of Features (Column-wise) :

![attachment:f%20of%20words.png](https://github.com/RusticHaze634/Text-Analysis/blob/main/Images/f%20of%20words.png)

- Positive and Negative Class-wise Data Distribution After Balancing Data-Classes:

![attachment:01%20filtered.png](https://github.com/RusticHaze634/Text-Analysis/blob/main/Images/01%20filtered.png)

### RESULTS:
----------------

- The Table with Results:

![attachment:Result%20table.png](https://github.com/RusticHaze634/Text-Analysis/blob/main/Images/Result%20table.png)

- Confusion Matrix

![attachment:confusion%20matrix.png](https://github.com/RusticHaze634/Text-Analysis/blob/main/Images/confusion%20matrix.png)

- The Prediction Accuracy Score for Training Data : **99.37%**
- The Prediction Accuracy Score for Testing Data : **97.91%**
