# Customer Churn Analysis & Prediction

## 📊 Project Overview
This project analyzes customer churn for a telecommunications company using machine learning. The goal is to identify patterns in customer behavior that lead to churn and build a predictive model to help reduce customer attrition.

## 🔍 Key Insights
- **Churn Rate**: Approximately 27% of customers churn, indicating significant revenue loss.
- **Critical Factors**:
  - **Tenure**: Newer customers are more likely to churn.
  - **Contract Type**: Month-to-month contracts have higher churn rates.
  - **Payment Methods**: Electronic checks show higher churn compared to automatic payments.
  - **Monthly Charges**: Higher charges correlate with increased churn.
  - **Internet Service**: Fiber optic customers have higher churn rates.

## 🛠 Technical Implementation
1. **Data Preprocessing**:
   - Handled missing values and encoded categorical variables
   - Normalized numerical features
   - Split data into training and testing sets

2. **Modeling**:
   - Implemented Logistic Regression with hyperparameter tuning
   - Achieved X% accuracy in predicting churn
   - Identified key features driving churn predictions

3. **Evaluation**:
   - Confusion matrix analysis
   - Precision, Recall, and F1-score metrics
   - ROC curve and AUC score

## 📈 Business Impact
- **Cost Savings**: Reducing churn by X% could save $Y annually
- **Targeted Retention**: Identified high-risk customer segments for focused retention efforts
- **Service Improvements**: Insights into service aspects needing enhancement

## 🚀 How to Use
1. Install required packages: `pip install -r requirements.txt`
2. Run notebooks in order:
   - [Data_Cleaning.ipynb](cci:7://file:///c:/Users/hp/Desktop/data_practice_room/Data_Cleaning.ipynb:0:0-0:0)
   - `Exploratory_Data_Analysis_(EDA)_–_Churn_Insights.ipynb`
   - [CHURN_MODELLING.ipynb](cci:7://file:///c:/Users/hp/Desktop/data_practice_room/CHURN_MODELLING.ipynb:0:0-0:0)

## 📂 Project Structure
- [CHURN_MODELLING.ipynb](cci:7://file:///c:/Users/hp/Desktop/data_practice_room/CHURN_MODELLING.ipynb:0:0-0:0): Predictive modeling implementation
- `Exploratory_Data_Analysis_(EDA)_–_Churn_Insights.ipynb`: Data exploration and visualization
- [Data_Cleaning.ipynb](cci:7://file:///c:/Users/hp/Desktop/data_practice_room/Data_Cleaning.ipynb:0:0-0:0): Data preprocessing and cleaning pipeline

## 📝 Requirements
- Python 3.7+
- pandas, numpy, scikit-learn
- matplotlib, seaborn
- jupyter
