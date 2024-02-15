# Machine-Learning-Churn-Project-
This work shows the customer attrition issue for ConnectTel Telecom Company (a prominent telecommunication giant at the forefront of innovation and connectivity solutions), as it seriously threatens the company's viability and expansion. 
PROJECT DESCRIPTION
•	Customer attrition is an urgent issue for ConnectTel Telecom Company (a prominent telecommunication giant at the forefront of innovation and connectivity solutions), as it seriously threatens the company's viability and expansion. Due to the inaccuracy and ineffectiveness of the company's present customer retention tactics, it is losing out to competitors on important clients. 
•	Against this background, ConnectTel commissioned RELLNATrends (a Data science firm) to develop a strong customer churn prediction system, the company's solution to this problem. The firm uses machine learning and sophisticated analytics techniques on accessible customer data to accurately target retention activities and estimate client attrition. 
•	In line with this proactive approach, it is expected that ConnectTel will lower customer attrition, increase customer loyalty, and preserve a competitive edge in the fiercely competitive and dynamic telecommunications sector.
STEPS SUMMARY
•	Understanding the Problem: A review of the project description was carefully undertaken to understand the problem statement and objectives of ConnectTel.

•	Data collection and exploration: Access to the relevant customer data provided by ConnectTel was obtained. Exploration of the data to understand its structure, quality, and characteristics was done, and the key features that may influence customer churn were identified.

•	Data Preprocessing: Missing values, outliers, and inconsistencies in the dataset were checked. Feature engineering was performed to create new features or transform existing ones, and categorical variables were encoded. 

•	Data Splitting: The dataset was split into training and test sets (80-20%).
•	Model selection: Five (5) machine learning algorithms were chosen for customer churn prediction. These models include logistic regression, gradient boosting, random forests, SVC, and decision trees. 

•	Model Training: Selected models trained using the training dataset. 

•	Model Evaluation: The trained models were evaluated using the validation dataset. Evaluation metrics used are: accuracy_score, precision_score, recall_score, f1_score and AUC-ROC:

•	Model Interpretation: The table below shows the performance of various deployed models under the evaluated metrics. Deploying various models, logistic regression performance under the stated evaluation metrics predicted the churned customers in the following light: Accuracy score (81%), Precision score (68%), Recall score (56%), F1 score (62%), AUC-ROC score (68%) and Confusion matrix (98%). The gradient boosting model predicted the following scores: Accuracy score (81%), Precision score (69%), Recall score (53%), F1 score (60%), AUC-ROC score (72%), and Confusion matrix (91%). The Random Forests Classifier performance under the following metrics is Accuracy score (79%), Precision score (66%), Recall score (46%), F1 score (53%), AUC-ROC score (69%), and Confusion matrix (89%). SVC classifier performance under the following metrics is Accuracy score (74%), Precision score (0%), Recall score (0%), F1 score (0%), AUC-ROC score (0.5%), and Confusion matrix (89%). Finally, the decision trees model performance under the following metrics is Accuracy score (73%), Precision score (49%), Recall score (47%), F1 score (48%), AUC-ROC score (65%), and Confusion matrix (89%). Generally, Logistic regression performed best among other models, followed by gradient boosting. The worst-performing model is SVC, with the lowest evaluation metrics. 

Table 1: Assessment score of Classifiers by different Evaluation methods
S/n	Algorithms	Evaluation Metrics (%)
		Accuracy
score	Precision
score	Recall
score	F1 score	AUC-ROC score	Confusion
Matrix score
1	Logistic regression	81	68	56	62	73	98
2	Gradient boosting	81	69	53	60	72	91
3	Random forests	79	66	46	53	69	89
4	SVC	74	0	0	0	0.5	89
5	Decision trees	73	49	47	48	65	
By following these steps, RELLNATrends developed a strong customer churn prediction system for ConnectTel Telecom Company, helping them mitigate customer attrition, increase customer loyalty, and maintain a competitive edge in the telecommunications sector.

Insights from the Dataset
1.	There was no missing data found in the dataset.
2.	There were 7,043 customers; 5,175 (74%) were non-churners, while 1,869(26%) churned. 
3.	Electronic check was the most used payment method while the credit card is the least used method. 
4.	The customers are of almost equal gender.
5.	There exist weak positive and negative correlations among the variables.
6.	It was found that the customers on streaming movie subscriptions mostly churned in the first year.
7.	Customers with monthly charges between 50-90 churned in the first year. 
8.	The customers with charges ranging from 1,500 to 5,500 churned in the first year.
9.	The customers that subscribe to online security services churned mostly in the fourth year of service. 
10.	Most of the attrition occurred in the first year across all customers. 

Challenges
1.	Feature Engineering: Identifying meaningful features from the available data is essential for building a predictive model. There was a need to explore different variables to extract relevant features that can help predict churn accurately.
2.	Model selection and evaluation: Various models such as logistic regression, decision trees, random forests, gradient boosting, and SVC to find the best-performing solution were deployed. Also, it is necessary to evaluate the model's performance using appropriate metrics like accuracy, precision, recall, and F1-score to ensure its effectiveness.
3.	Model Accuracy and Generalization: Developing an accurate churn prediction model requires machine-learning techniques and analytics. Ensuring the model generalizes well to unseen data and diverse customer segments is critical for its effectiveness.
4.	Interpretability and Explainability: Interpreting the predictions of the churn prediction model was challenging. 
