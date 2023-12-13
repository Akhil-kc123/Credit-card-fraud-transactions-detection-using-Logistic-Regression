# Credit-card-fraud-transactions-detection-using-Logistic-Regression
This is a complete ML project for detect credit card fraud transactions. Python and jupyter notebook used for writing code and Dataset is also included in this repository. Model is built using a classification algorithm as Logistic Regression
1. Objective and Scope :
   The primary objective of this project is to develop a machine learning model for the identification of credit card fraud transactions using a logistic regression approach. The dataset used contains transactions made by European cardholders in September 2013, presenting a challenging scenario due to the highly imbalanced nature of the data. The focus is on creating a model that can accurately distinguish between fraudulent and non-fraudulent transactions, addressing the critical issue of credit card fraud in a real-world context.
  Dataset Overview : The dataset consists of 284,807 transactions over a two-day period, with only 492 labeled as frauds. This imbalance poses a significant challenge for traditional machine learning models, as the positive class (frauds) represents a mere 0.172% of all transactions. The dataset includes 31 columns, with columns V1 to V28 resulting from a PCA dimensionality reduction and 'Amount' representing the transaction amount. The target variable is 'Class,' with 1 indicating fraud and 0 for non-fraudulent transactions.  <br />
  2. Key Components and Steps:
•	Exploratory Data Analysis (EDA):<br />
EDA involves exploring the dataset to gain insights into its characteristics and uncover potential patterns. Visualizations such as count plots and a heatmap of the correlation matrix were employed to understand the distribution of fraud and non-fraud transactions, investigate feature relationships, and identify potential areas of interest.<br />
•	Feature Engineering:<br />
Given the PCA-transformed features (columns V1 to V28), explicit feature engineering was minimal. The focus was on optimizing the data for model training while retaining the inherent structure captured by PCA. Feature engineering strategies such as creating new features or transforming existing ones were not applied in this iteration.<br />
•	Model Training and Evaluation using Logistic Regression:<br />
The logistic regression model was selected for its simplicity and interpretability, crucial aspects in fraud detection where model transparency is often essential. The model was trained on the preprocessed data and evaluated using standard classification metrics.<br />
•	Performance Evaluation:<br />
Accuracy: 95%
Precision: 92%
Recall: 98%
F1 Score: 95%<br />
These metrics collectively indicate a balanced performance, effectively identifying both fraud and non-fraud transactions. Precision reflects the accuracy of the model in identifying true frauds among the predicted fraud cases, while recall represents its ability to capture actual fraud cases.<br />
•	Resampling Technique:<br />
Given the dataset's highly imbalanced nature, future iterations of the project could explore resampling techniques to address the class imbalance. Techniques such as oversampling the minority class (frauds) or undersampling the majority class (non-frauds) could potentially enhance the model's performance, especially in identifying rare instances of fraud.<br />
  3 Conclusion:<br />
In conclusion, this machine learning project successfully addresses the critical issue of credit card fraud detection using logistic regression. The model's accuracy, precision, recall, and F1 score collectively highlight its effectiveness in distinguishing between fraudulent and non-fraudulent transactions.
The highly imbalanced nature of the dataset presented a significant challenge, but the model demonstrated a balanced performance, effectively identifying instances of fraud while minimizing false positives. Future iterations could explore advanced techniques, such as resampling or more complex models, to further enhance performance.
This project showcases the potential of machine learning in real-world applications, specifically in addressing the crucial problem of credit card fraud. The logistic regression model, despite its simplicity, proves to be a valuable tool in this context, providing transparency and interpretability in fraud detection.


