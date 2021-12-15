# Classification of Customers Churn (MVP)
## The purpose of the classification is to understand the influence of various factors on the bank customers who are closing their accounts (Churn).


### Figure 1
![correlation](https://user-images.githubusercontent.com/93079224/146169594-d7af72af-4501-48e2-b707-04cafbb5832a.png)
##### features that has big correlation with exiting the bank
> - Age (29%)
> - Customers in Germany (17%)
> - Female customers (11%)


Logistic regression before oversampling training and validation set metrics: 
|       Training         |    Validation      |
|------------------------|--------------------|
|Accuracy: 0.7869        |Accuracy: 0.7894    |
|Precision: 0.3864       |Precision: 0.3757   |
|Recall: 0.0520          |Recall: 0.0539      |
|F1: 0.0916              |F1: 0.0943          |


### Figure 2
##### The following figure is our baseline model before oversampling: Logistic Regression.
![baseline](https://user-images.githubusercontent.com/93079224/146169511-250b9a02-5f0a-41fb-b48f-0ec0faf1e6d3.png)

#### The score of our baseline was actually good with an accuracy of: 0.7869

### Figure 3
##### The following figure is our data with oversampling
![oversampling](https://user-images.githubusercontent.com/93079224/146174338-20089757-0ded-4b50-bc48-50806eb1171e.png)

Logistic regression after oversampling training and validation set metrics: 
|       Training         |    Validation      |
|------------------------|--------------------|
|Accuracy: 0.6643        |Accuracy: 0.6799    |
|Precision: 0.6621       |Precision: 0.6753   |
|Recall: 0.6950          |Recall: 0.7149      |
|F1: 0.6950              |F1: 0.6945          |

## In conclusion after we did the oversampling, the accuracy has been reduced from 79% to 63%




