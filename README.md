# Student-Job-Placement-Prediction

This project predicts whether a college student will be placed in a job by applying machine learning to academic and personal attributes. With an increasingly competitive job market, understanding which factors are associated with employment outcomes can help students and colleges identify areas that may deserve greater attention. The project uses a dataset containing 10,000 student records and features such as cumulative GPA, IQ, internship experience, and number of projects completed. Logistic Regression and Gaussian Naive Bayes models were developed in Python, evaluated on a separate test set, and fine-tuned using stratified 5-fold cross-validation. Both models achieved around 90% test accuracy, while the analysis identified communication skills, CGPA, IQ, previous semester results, and projects completed as important predictors of job placement.

Key Features:

• Preprocessed student data by encoding categorical variables and standardizing numerical features before model training

• Developed Logistic Regression and Gaussian Naive Bayes models to predict student job placement outcomes

• Applied stratified train-test splitting and 5-fold cross-validation to address class imbalance and tune model hyperparameters

• Evaluated model performance using accuracy, precision, recall, F1 score, ROC-AUC, and confusion matrices, with both models achieving approximately 90% test accuracy

• Analyzed feature importance to identify academic and personal factors most strongly associated with student job placement outcomes
