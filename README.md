This is the capstone project of Google Advanced Data Analytics Professional Certificate.
Project Name : Waze user churn analysis and prediction with Binary Classification model.
For the public purpose, ataset is imported from kaggle. 
Dataset path - '/kaggle/input/waze-dataset-to-predict-user-churn/waze_dataset.csv'
Project Objectives are to understand the customer behvoiours by analyzing the dataset to make the data-driven insights and develop a custom churn prediction model to increase the growth of waze and customer rentention.
<img width="527" height="281" alt="image" src="https://github.com/user-attachments/assets/b2518773-957b-43c5-af0b-21d1ca025645" />

Two binary-classification models are developed. 
Statistical Logistic Regression Model

<img width="564" height="197" alt="image" src="https://github.com/user-attachments/assets/1b8e0682-4a21-43ed-896a-86bd63e71f8f" />

<img width="565" height="432" alt="image" src="https://github.com/user-attachments/assets/2729d2c8-4813-4dcd-aab4-7aec6ba4c87c" />

XG Boost Model 
Confusion Matrix values on training, validation and testing data

<img width="527" height="166" alt="image" src="https://github.com/user-attachments/assets/05425875-9c05-4e03-85a0-0d2ded4a175d" />

<img width="565" height="438" alt="image" src="https://github.com/user-attachments/assets/787b4369-f9ee-4cfd-9d1d-0a3549cdd1cd" />

XG Boost model shows consistent model performance across training, validation and unseen data testing but still have poor values on precision and recall. The performance metrics are stable across the cross-validation, validation, and test sets which means model is not overfitting to the training data.



