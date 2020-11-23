# InstacartResearchSymposium
### Members: Arrido Arfiadi, Christine Nguyen
### Mentor: Dr. Xiahua (Anny) Wei

## RESEARCH QUESTION

* What is the likelihood of a customer reordering a specific product?

* How should the company recommend relevant products to individual users


## MOTIVATION

* Collected and compiled 3 million daily transaction-level data from a popular-online grocery delivery company in 2017

* Utilized data to strategize decision-making to improve performance and sustain competitive advantage

* Further understanding the customer base and their purchasing behaviors 

## Tools

* Python
* Jupyter
* PostgreSQL
* Amazon S3
* Amazon Sagemaker

## GENERAL METHODOLOGY

![](https://github.com/arridoarfiadi/InstacartResearchSymposium/blob/master/photos/metho.png)

## Outputs

### Question 1

![](https://github.com/arridoarfiadi/InstacartResearchSymposium/blob/master/photos/output2.png)


### Question 2

![](https://github.com/arridoarfiadi/InstacartResearchSymposium/blob/master/photos/output1.png)


## RESULTS

### Research Question No.1
* Random Forest Classifier yields the best accuracy of 82.48% in comparison to Logistic Regression and Naives Bayes

* Product order share was the most important feature in comparison to User Total Order, User Total Product Order, User Product Total Reordered and User Median Days Since Prior Order

### Research Question No.2
* Recommendations for the users are unaffected by the K-Nearest Neighbors (KNN) model and is strictly reliant on the dataset

* Recommendation system occasionally outputs irrelevant products. Example: Recommending toiletries when ordering produce 

## Discussion 

### Research Question No.1
* The result allows us to categorize the users into different target groups based on their purchasing behaviors

* Promoting products that are at the tipping point between reordering and not-reordering for each target groups

### Research Question No.2
* The model looks at every user that purchases the same product and depending on the popularity of the product, the recommendation system may vary in accuracy. Example: Almost everybody purchases bananas with a variety of different products making the recommendation more random

* K-Nearest Neighbors (KNN) does not seem to be the best model for the recommendation system due to it’s high dependency on the dataset

## Future Work

* Further improve collaborative filtering algorithm by looking into Matrix Factorization, Deep Learning, and Neural Networks

* Create business strategies based on the results of research question 1





