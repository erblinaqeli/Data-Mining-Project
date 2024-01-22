# Data-Mining-Project
## Telecom Churn Prediction
Every business has competitors and customers usually switch between the ser- vice providers based on their experience, price difference, quality of service, etc. Telecommunication companies are no different. Customer churn, in the context of telecom services, occurs when subscribers switch from one network provider to another due to various reasons. For instance, a customer might initially choose network provider X because they offer a more appealing monthly talk-time plan, while another customer opts for network provider Y because their services align better with their specific needs. However, over time, factors such as increased pricing by network provider X or the introduction of superior plans by competi- tor Y may entice customers of X to switch to Y, thereby illustrating the concept of churn.

## Evaluation
We performed Cross Validation for every Classification Model we trained in addition to hyper-parameter tuning. It considerably increased the accuracy of our models. For Logistic Regression and KNN Model, the ROC-AUC was 0.65 initialy. After performing Cross Validation, the ROC-AUC was 0.84 for both the models. We also performed Feature Selection which increased the score by 0.01 for logistic regression but decreased by 0.01 for CatBoost Classifier.

## Dataset and Features
We have fetched the dataset from kaggle: [Telecom Churn Dataset Kaggle] (https://www.kaggle.com/competitions/advanced-dls-spring-2021/data).
