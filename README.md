# Bank-Crisis-Forecaster
Bank Crisis Forecaster a model for forecasting banking crises using Python's Scikit-learn, Pandas, and NumPy

### **Overview**

The "Bank Crisis Forecaster" is a machine learning project designed to predict potential bank crises by analyzing economic indicators and financial data. This model aims to help financial institutions mitigate risks by providing early warnings.

### **Dataset & Libraries**

**Dataset**: The project uses a comprehensive dataset containing historical data on banking crises, economic factors, and other relevant financial indicators across multiple countries.

**Libraries**: Essential Python libraries for this project include Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and Scikit-learn for building and evaluating machine learning models.

### **Results Summary**

- **Accuracy of Models**: Various machine learning models were tested. The model with the highest accuracy achieved an accuracy score of 85%, which indicates a strong ability to predict potential banking crises correctly.
- **Precision and Recall**: The best-performing model demonstrated a precision of 82% and a recall of 79%. This balance suggests that the model is effective in identifying true bank crisis events while maintaining a low rate of false positives.
- **Feature Importance**: The model analysis highlighted that certain economic indicators such as "capital adequacy ratio" and "non-performing loans" were among the most influential features, impacting the model's predictions significantly.
- **Model Evaluations**: The notebook includes detailed evaluations of each model, providing insights into their performance under various parameters. For example, logistic regression showed a standard deviation in precision of approximately 0.05, indicating consistent performance across different test sets.

### **Features**

- **Predicts potential bank crises** using classification models that analyze key financial stability indicators. This includes Capital Adequacy Ratios to assess a bank’s ability to withstand financial distress, Loan-to-Deposit Ratios to gauge liquidity, and Non-performing Loans to evaluate credit risks.
- **Utilizes a rich dataset** of economic indicators and banking sector metrics from multiple countries, enhancing model development. This dataset features Return on Assets (ROA) and GDP Growth to analyze their impact on banking stability.
- **Employs advanced data preprocessing and feature engineering techniques** to optimize the dataset for analysis, enhancing the predictive accuracy of the models.
- **Incorporates a suite of advanced machine learning libraries**, including numpy, pandas, matplotlib, seaborn, scikit-learn, and XGBoost, for robust model development and in-depth data analysis.


