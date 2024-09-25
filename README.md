# Fraud Detection System for E-Commerce Transactions

## Project Overview and Use Case:

### Objective:

The objective of this project is to develop a machine learning-based fraud detection system that can identify and prevent fraudulent transactions in real-time, thereby reducing financial losses and improving the overall security of e-commerce transactions.

### Background:

E-commerce has become an integral part of modern retail, with millions of transactions taking place every day. However, this growth has also led to an increase in fraudulent activities, resulting in significant financial losses for businesses and individuals alike. Traditional rule-based systems are no longer effective in detecting fraud, as fraudsters have become more sophisticated in their methods.

### Problem Statement:

The e-commerce company, "OnlineMart," is facing a significant challenge in detecting and preventing fraudulent transactions. The company's current system relies on manual reviews and rule-based checks, which are time-consuming and prone to errors. As a result, OnlineMart is experiencing a high rate of false positives, leading to unnecessary transaction cancellations and revenue losses.

### Dataset
The dataset used in this project is downloaded from DataCamp's Fraud Detection in Python course. It is a dataset containing credit card transactions data. Fraud occurrences are fortunately an extreme minority in these transactions. However, Machine Learning algorithms usually work best when the different classes contained in the dataset are more or less equally present. If there are few cases of fraud, then there's little data to learn how to identify them. This is known as class imbalance, and it's one of the main challenges of fraud detection. Let's explore this dataset, and observe this class imbalance problem.

## Project Evaluation
### Final Model Accuracy:

98% for predicting fraud detection
### Final Model Recall:

86% of the time the model will correctly predict fraudulent transactions.

## Discussion
In this project, we employed a dual approach to detect fraud cases, leveraging both supervised and unsupervised machine learning techniques. When dealing with labeled fraud cases, we utilized supervised learning to train our models. By combining the strengths of multiple classifiers, we aimed to create a robust and accurate fraud detection system. Our analysis revealed that Random Forest excelled in precision but struggled with false negatives, while Logistic Regression demonstrated high recall but was plagued by false positives. Decision Tree performed moderately, striking a balance between precision and recall.

By combining these models, we achieved a significant improvement in performance. Our hybrid approach enabled us to increase the detection of actual fraud cases from 75% to 78%, reduce false negatives by 3%, and limit the increase in false positives to only 4. This presents a favorable trade-off for organizations prioritizing the detection of as many fraud cases as possible while maintaining a low false positive rate. By combining the strengths of multiple models, we created a robust and accurate fraud detection system that minimizes the risk of false negatives and optimizes performance.

Ultimately, our approach highlights the importance of carefully evaluating and selecting models based on their strengths and weaknesses, as well as understanding the trade-offs between precision, recall, and false positives. By adopting a both approach to fraud detection, organizations can create a more effective and efficient system for identifying and preventing fraudulent activity.

![image](https://github.com/user-attachments/assets/93480efd-8d29-4c49-b69c-507c0df60ac7)

In the absence of labeled fraud cases, unsupervised machine learning techniques can be employed to distinguish normal from abnormal behavior, potentially indicating fraudulent activity. This approach requires a deep understanding of the data and its characteristics, as well as a clear definition of what constitutes "normal" behavior. However, validating the results of unsupervised machine learning models can be challenging, as traditional performance metrics such as accuracy, precision, and recall are not applicable due to the lack of actual fraud labels or ground truth. To overcome this limitation, alternative validation methods can be used, such as consulting with fraud analysts to verify the suspiciousness of flagged cases, conducting in-depth investigations of flagged cases, and testing the model on historical known fraud cases to assess its ability to detect them accurately. By leveraging these approaches, unsupervised machine learning can provide valuable insights into potentially fraudulent behavior, even in the absence of labeled data.

![image](https://github.com/user-attachments/assets/4bb0b459-0e4f-46c6-bc57-0291f6b3c0c3)


