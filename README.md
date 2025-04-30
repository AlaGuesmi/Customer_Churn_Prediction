# Customer_Churn_Prediction

📊 **Overview**
This project simulates a synthetic e-commerce dataset to explore key business analytics tasks such as customer churn prediction and return analysis. The dataset includes both transactional and behavioral data and presents real-world data challenges such as missing values, outliers, mixed data types, and high dimensionality.

📁 **Dataset Overview**

The dataset contains 12 features and 1 target variable:

- CustomerID: Unique identifier for each customer

- Age: Age of the customer (some values missing)

- Gender: Male, Female, Non-binary

- Country: Customer's country

- ProductCategory: Electronics, Clothing, Home, Beauty, Books

- PurchaseAmount: Amount spent (includes outliers)

- Rating: Customer product rating (1 to 5, with some missing values)

- Review: Ordinal textual feedback

- PurchaseDate: Transaction date (with some invalid entries)

- LoyaltyMember: Whether the customer is in the loyalty program

- Returned: Whether the product was returned

- Churn: Target variable indicating if the customer churned (Yes/No)

🛠️ **Tools & Libraries Used**

- Python (Pandas, NumPy) – Data manipulation

- Seaborn, Matplotlib – Visualization

- Scikit-learn – Machine learning (Logistic Regression, Random Forest, Gradient Boosting)

- KNNImputer, SimpleImputer – Missing value handling

- StandardScaler, LabelEncoder – Preprocessing

- GridSearchCV – Hyperparameter tuning

- PCA – Dimensionality reduction

🔁 **Process & Methodology**

- Data Loading & Exploration

  Summary stats, missing data patterns, and data types.

- Handling Missing Data

  Used SimpleImputer for numerical data and KNNImputer for multivariate imputation.

- Outlier Treatment

  Identified and capped extreme values in PurchaseAmount and Age.

- Categorical Encoding

  Label encoding and ordinal mapping for review and churn-related features.

- Feature Engineering

  Interaction terms, purchase frequency, total spend per customer, etc.

- Dimensionality Reduction

  Applied PCA to improve performance and reduce noise.

- EDA

  Correlation heatmaps, rating vs. churn analysis, category-wise trends.

- Model Building

  Trained and compared:

-  Logistic Regression

-  Random Forest Classifier

-  Gradient Boosting Classifier

-  Model Evaluation & Tuning

- Accuracy, classification report, and cross-validation with GridSearchCV.

✅ Outcomes

- Identified key predictors of churn, including product return behavior, low ratings, and lack of loyalty membership.

- Boosted model accuracy through feature interactions and parameter tuning.

- Gained insights into customer behavior patterns for business decision-making.
