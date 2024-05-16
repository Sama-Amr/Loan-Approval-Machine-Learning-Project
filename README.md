# Loan-Approval-Machine-Learning-Project
The approval of loans is an immensely tedious procedure because of the growing demand for loans. In addition, each applicant’s credentials must be thoroughly processed before arriving at the conclusion of approving the loan or not. However, this process is inevitable, so the banking sector could take advantage of the current technological breakthroughs to be more effective and save time. This could be done by implementing a machine learning model on a dataset consisting of a group of applicants to predict whether they are eligible for a loan. 

### Chosen Model
The algorithm of best fit turned out to be the Decision Tree algorithm for a variety of reasons. The Decision Tree algorithm is a classification algorithm that reaches general conclusions from a successive set of facts. Moreover, it is a rule-based model that classifies the data based on the information gained from each label, and it is in the form of a tree structure, hence the name. The primary reason behind this choice is the outstanding performance metrics. The performance metrics put into consideration are accuracy, precision, recall, and the F1 score, which is a combination of both precision and recall. The following table shows the performance metrics of the Decision Tree algorithm in comparison to other machine learning algorithms: 
![image](https://github.com/Sama-Amr/Loan-Approval-Machine-Learning-Project/assets/100078180/845f6c21-8661-42a3-ae72-34a9d9c27cef)
It is clear that the Decision Tree algorithm has the highest accuracy, recall, and F1 score. Even though it did not have the highest precision, 86.6% was not that far off, and it had the best performance metrics overall. Therefore, the Decision Tree algorithm was picked as the best fit for loan approvals. It is also worth mentioning that all of this was prior to optimizing the parameters, which is the following step. 

### Model Design
As for the design of the model, it will be implemented and adjusted so that it best fits the data, and achieve the most accurate and precise predictions. This was done by searching for the optimum parameter, which turned out to be the entropy. In addition, the optimum maximum depth, minimum samples leaf, and minimum sample split turned out to be 10, 1, and 2 respectively.  The testing for this step was conducted using the F1 score because it is the most robust due to it including both precision and recall. The outcome was a score of approximately 0.987. In addition, this optimization leads to 100% training accuracy, 98% testing accuracy, and approximately 99% mean accuracy from cross-validation.  The following table shows the confusion matrix for the Decision Tree algorithm after optimization of the parameters:

### Application Flow 




