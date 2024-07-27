# Credit card fraud detection

Data set obtained from Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

<p align = jsutify>I have used Random Forest Classifier from sklearn library for data training. I have used 20% of the credit card data for training and rest 80% for testing RF model. </p>

![image](https://github.com/user-attachments/assets/42024fd0-8d32-48ac-aeb2-3a097132b5cf)


## Random forest
<p align = justify> The Random Forest Classifier is a robust and versatile ensemble learning method used for classification tasks. It works by constructing multiple decision trees during the training process, with each tree being trained on a random subset of the data.</p>

![image](https://github.com/user-attachments/assets/2547bc58-f068-4180-8268-f7b08230df3e)

<p align = justify>This is achieved through a technique known as bootstrap aggregation or bagging, where each subset is created by sampling the data with replacement. Additionally, when making splits in each tree, only a random subset of features is considered, introducing further diversity among the trees and helping to reduce overfitting. During prediction, each tree in the forest votes on the class, and the final classification is determined by the majority vote. This approach enhances the model's accuracy and reduces the risk of overfitting compared to a single decision tree.  
 However, while Random Forest is effective and can handle a variety of data types, it is more computationally intensive and less interpretable than individual decision trees.</p>
 
## Confusion matrix
<p align = justify>A confusion matrix is a valuable tool for evaluating the performance of a classification model. It provides a detailed summary of how well the model distinguishes between fraudulent and non-fraudulent transactions. 

- True Positives (TP): The number of fraudulent transactions that the model correctly identifies as fraudulent. This indicates how well the model detects actual fraud cases.
- True Negatives (TN): The number of legitimate transactions that the model correctly identifies as non-fraudulent. This reflects the model's accuracy in identifying genuine transactions.
- False Positives (FP): The number of legitimate transactions that the model incorrectly classifies as fraudulent. This is also known as a Type I error, and it represents the false alarms or “false positives” where legitimate transactions are wrongly flagged as fraud.
- False Negatives (FN): The number of fraudulent transactions that the model incorrectly classifies as non-fraudulent. This is also known as a Type II error, and it indicates missed fraud cases where actual fraud goes undetected.

Confusion matrix also helps in determing accuracy, precision, recall/sensitivity and F1 scores.
</p>

 
