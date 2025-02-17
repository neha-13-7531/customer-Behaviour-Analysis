# customer-Behaviour-Analysis
Objective
Analyze customer behavior patterns to gain insights that help businesses improve decision-making, enhance customer experience, and optimize marketing strategies.

# Features in data set
- Age – The age of the customer in years.
- Income – The annual income of the customer.
- Marital_Status – The marital status (Single, Married, Divorced, etc.).
- Gender – The gender of the customer (Male, Female).
- Education_Level – The highest education level attained (High School, Bachelor’s, Master’s).
- Purchase_in_Last_Month – The number of purchases made in the last month.
- Online_Activity_Level – A measure of how active the customer is online (Low, Medium, High).
- Product_Interest – The type of products the customer is most interested in.
- Days_Since_Last_Purchase – The number of days since the customer's last purchase.
- Customer_Loyalty_Score – A numerical score indicating customer retention and engagement.
- Income_Category – Categorized income levels (Low, Medium, High).
- Age_Income_Ratio – A calculated metric of income relative to age.
- Is_Young_Professional – A flag (Yes/No) indicating if the customer is a young working professional.
- Online_Purchase_Tendency – The likelihood of making online purchases.
- Will_Purchase – A prediction (Yes/No) of whether the customer will make a purchase soon.
-Annual_Spending – The total amount spent by the customer in a year.
# Project Steps
1.Data Collection & Loading

- Load the dataset using pandas: df = pd.read_csv("customerbehaviouranalytics.csv")
-Inspect the data: df.head(), df.info(), df.describe()
-Check for missing values: df.isnull().sum()

2.Data Cleaning & Preprocessing
- Handle missing values (drop or impute missing data).
- Convert categorical features to numerical (e.g., One-Hot Encoding for Gender, Marital_Status).
- shape to get column and row of data.
- find unique values df.nunique()
- handling outlier Online_Purchase_Tendency,Age_Income_Ratio,Annual_spending.

3.Exploratory Data Analysis (EDA)
- Univariate Analysis: Histograms, boxplots, and bar charts for single features like Age, Income, and Spending.
- Bivariate Analysis: Correlation heatmaps and scatter plots to understand feature relationships.

4.Model Building
- Classification
 - Algorithms: Logistic Regression, Decision Trees, Random Forest, XGBoost,Random Forest,svc,KNN etc.
 - Evaluation: Accuracy, Precision, Recall, F1-score
- Regression (Predicting Annual Spending)
  - Algorithms: Linear Regression, Random Forest Regressor,Gradient boosting,XGBRegressor,Decision Tree.
  - Evaluation: RMSE, R² Score

5.Feature Importance
- shap using for feature importance.

6.Perform Random Search

7.Model Deployment
- use pickle file (.pkl) create new pickle file.
