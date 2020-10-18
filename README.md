# CREDIT CARD FRAUD DETECTION

## What is Fraud?

Fraud is an act of deception used to illegaly deprive another person or entity of money, property or legal rights.

## Rule-based approach for fraud detection

In Rule-based approach,

* Algorithms are written by fraud analyst.
* Based on strict rules.
* Changes for detecting a new fraud are done manually.
* Increase in customers and data, increases human efforts.
* Time Consuming and costly.
* Cannot recognize the hidden patterns.
* Cannot predict the fraud by going beyond the rules.
* Connot responds to new situations, not trained on or explicitly programmed.

## Data Science approach for fraud detection

To leverage the vast amounts of data collected from online transactions and model it in a way that allows us to flag or predict fraud in future transactions.  
So we use different Machine Learning and Deep Learning techniques to detect fraud.

Here we have used Machine Learning Techniques.  
**Machine Learning (ML)** - ML encompasses a large collection of algorithms and techniques used in classifications, regression, clustering and anomaly detection.  

## Some of the Challenges of fraud detection model

* Unbalanced Data
* Operational Efficiency
* Incorrect flagging 

### Dealing with Unbalanced Data

* Classifier tends to favour majority class (=Legitimate)
* Large classification error over the fraud cases
* Classifiers learn better from a balanced distribution

**Sampling Methods to solve this Unbalanced Data problem**

**Random Over-SAmpling (ROS)** -

In this technique we over sample the minority class which is our fraud cases, so we copy the cases that are already present in are fradulent cases, so me copy the same cases multiple times till we reach the threshold value that we want in our dataset. The problem with this technique is that it is done by creating the duplicating lots fraud cases that are already present in our dataset that means we will be training our model with lots of duplicate values which won't explain the varriance in the dataset.

**Random Under-Sampling (RUS)** -

In this technique we under sample the majority class which is our legitimate cases, so we remove some of the cases from our dataset which are from legitimate transactions so we remove some of the cases till we have almost the same distribution as of fraud cases. The problem with this technique is that we will endup with throwing lot of useful data and informations which is not prefered in general. 

**Both** -

You can perform both ROS and RUS by increasing the fraud cases and decreasing the legitimate cases.

**Synthetic Minority Over-Sampling (SMOTE)** -

In this technique we over-sample the minority class (i.e fraud) by creating synthetic fraud cases.

Read more about SMOTE [link-1](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/), [link-2](https://en.wikipedia.org/wiki/Oversampling_and_undersampling_in_data_analysis)

## Implementation

Dataset:  

Code:  

Lab Environment: RStudio

---














