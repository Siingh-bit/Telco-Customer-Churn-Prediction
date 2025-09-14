# Telco Customer Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecommunications company using machine learning. The goal was to clean the data, perform exploratory analysis, and build a classification model to identify customers at risk of leaving.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Algorithm:** Logistic Regression

## Key Steps
1.  **Data Cleaning:** Handled missing values and converted data types (e.g., `TotalCharges` to numeric).
2.  **Feature Engineering:** Performed one-hot encoding on categorical variables.
3.  **Model Training:** Split the data and trained a Logistic Regression model.
4.  **Evaluation:** Achieved **79% accuracy** and analyzed performance using a confusion matrix and classification report.

## Results and Insights
The model was successful in predicting customer churn with 79% accuracy. However, deeper analysis revealed its strength lies in identifying loyal customers, while there's room for improvement in precisely targeting at-risk churners.

**Key Metrics:**
- **Accuracy:** 79%
- **Precision (Churn Class):** 62%
- **Recall (Churn Class):** 52%
- **F1-Score (Churn Class):** 56%

**Confusion Matrix:**
| Actual \ Predicted | Did Not Churn | Churned |
|--------------------|---------------|---------|
| **Did Not Churn**  | 915           | 118     |
| **Churned**        | 181           | 193     |

## How to Run
1.  Clone the repository.
2.  Ensure you have Python and Jupyter Notebook installed.
3.  Install required libraries: `pip install pandas numpy scikit-learn matplotlib`
4.  Open `Customer_Churn_Analysis.ipynb` and run the cells.

## Future Work
- Experiment with more complex models like Random Forest or XGBoost to improve recall for the churn class.
- Perform feature importance analysis to identify the top factors driving churn.
