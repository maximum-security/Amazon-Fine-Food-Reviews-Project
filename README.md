# Amazon-Fine-Food-Reviews-Project
Examining the "Amazon Fine Foods Reviews" dataset from Kaggle to predict customer sentiment.

### Dataset
[Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

### Overview
The "Amazon Fine Food Reviews" dataset contains reviews for Amazon food products. Information regarding each review (time of review, helpfulness, summary, etc.) is also in the dataset. This project attempts to predict customer sentiment using both metadata and the substantive review text data. Results are then compared to determine the most reliable source of data for classification.

### Models Used
- Logistic Regression
- Naive Bayes
- Linear SVM

### Results
Results show that Logistic Regression is the best performing model when trying to capture `neutral` reviews, while Linear SVM is the best overall performing model after class balancing. This project highlights the importance of capturing negative and neutral reviews, as well as the significance of text data in machine learning.


