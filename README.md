# Predective_analysis_CrediCard_FraudDetection_2

** DESCRIPTION**  : In this task, I built machine learning models to predict whether a credit card transaction was fraud or not. The idea was to take the big dataset I processed in Task 1 and train models that can automatically recognize patterns of fraud.

Since fraud detection is a classification problem (predicting fraud or no fraud), I used three popular machine learning algorithms: Logistic Regression, Random Forest Classifier, and XGBoost Classifier.

First, I prepared the data for machine learning. This involved splitting the data into two parts: one part for training the model (so it can learn from known data), and the other part for testing (to see how well the model can predict new data). I made sure that the class distribution remained balanced while splitting, because as we know from Task 1, fraud cases are very rare compared to normal transactions.

Then, I started with Logistic Regression, which is one of the simplest and most commonly used algorithms for classification problems. After training, the model gave very high accuracy, which was surprising. But in fraud detection, accuracy alone is not enough because predicting everything as “normal” would give high accuracy but fail to catch actual fraud. So, I checked other important metrics like AUC (Area Under Curve) and plotted ROC curves. The model performed very well, indicating it was able to detect fraud cases effectively.

Next, I moved on to more advanced models — Random Forest and XGBoost. Random Forest works by creating many small decision trees and combining them to make a final prediction. XGBoost is even more powerful and works by boosting weak learners iteratively. Both these models performed even better than Logistic Regression.

For example, Random Forest and XGBoost achieved an accuracy of about 99.92% and excellent AUC scores greater than 0.96, which means the models were very good at distinguishing between fraud and non-fraud cases.

I also checked for overfitting, which means the model works well on training data but poorly on new unseen data. Fortunately, both models showed good balance and didn’t overfit, which is very important for real-world applications.

The main outcome of this task was that I successfully built, trained, and evaluated multiple machine learning models for fraud detection. In real life, such models are very important for banks and financial companies because they help automatically flag suspicious transactions in real-time, reducing losses and improving customer trust.

This task gave me hands-on experience with how machine learning is applied in finance, how to prepare data, how to select models, and how to evaluate performance using different metrics. It also taught me that relying only on accuracy is not enough in problems like fraud detection — we must look at other metrics like precision, recall, AUC, and ROC curves to ensure the model is truly effective.

In the end, I completed predictive analysis successfully and created models ready to be used for automated fraud detection systems.
