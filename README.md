# Credit Card Fraud Detection Using Machine Learning

# Task
Identify fraud credit card transactions using Machine Learning 

# Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Methodology
1) Data fetching
2) Exploratory Data Analysis and Data Visualization
3) Train-Test Split
4) Synthetic Minority Oversampling
5) Principal Components Analysis
6) Training the model
6) Testing using Test data 
7) Evaluation of Model
8) Saving the model

# Tags
Data Preparation, Data Exploration, Visualization, Imbalanced Data, Model Training and Testing, Confusion Matrix, Rare Class Classification, Principal Components Analysis, Recall, Synthetic Minority Oversampling, ROC Curve

# Tools
Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn, Imblearn, Pickle

# Metric
In case of an algorithm for fraud detection, Recall is a more important metric. It is obviously important to catch every possible fraud even if it means that the authorities might need to go through some false positives. On the other hand, if the algorithm is created for sentiment analysis and all you need is a high-level idea of emotions indicated in tweets then aiming for precision is the way to go.

In this project I secured 80% Recall for the Fraud Cases.




















# Acknowledgements
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project

Citations:

Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015

Dal Pozzolo, Andrea; Caelen, Olivier; Le Borgne, Yann-Ael; Waterschoot, Serge; Bontempi, Gianluca. Learned lessons in credit card fraud detection from a practitioner perspective, Expert systems with applications,41,10,4915-4928,2014, Pergamon

Dal Pozzolo, Andrea; Boracchi, Giacomo; Caelen, Olivier; Alippi, Cesare; Bontempi, Gianluca. Credit card fraud detection: a realistic modeling and a novel learning strategy, IEEE transactions on neural networks and learning systems,29,8,3784-3797,2018,IEEE

Carcillo, Fabrizio; Dal Pozzolo, Andrea; Le Borgne, Yann-Aël; Caelen, Olivier; Mazzer, Yannis; Bontempi, Gianluca. Scarff: a scalable framework for streaming credit card fraud detection with Spark, Information fusion,41, 182-194,2018,Elsevier

Carcillo, Fabrizio; Le Borgne, Yann-Aël; Caelen, Olivier; Bontempi, Gianluca. Streaming active learning strategies for real-life credit card fraud detection: assessment and visualization, International Journal of Data Science and Analytics, 5,4,285-300,2018,Springer International Publishing
