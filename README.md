# Google_Advanced_Data_Analytics__Course_5_Project__Waze_Regression_Analysis

At this stage, a logistic regression model was built, leveraging several independent variables (features) with the most predictive power.

Some variables were encoded, new ones were engineered from existing ones, and conditions such as collinearity, independent observations, and outliers were checked.

Once the model was built and fit, scores such as precision, recall, and F1 were acquired. The model exhibited satisfactory precision (correctly predicted positive observations divided by all predicted positives) but very low recall (correctly predicted positive observations divided by all actual positive observations). Recall was a crucial metric for this model, and the very low score indicated numerous false negative predictions, suggesting that it cannot accurately predict users at risk of churn.

Due to this limitation, the model cannot be used to drive business decisions but can be leveraged for further analysis of the dataset.
