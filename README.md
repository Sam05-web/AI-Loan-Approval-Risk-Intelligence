# AI-Powered Loan Approval & Risk Intelligence Dashboard

## About the Project

This project analyzes loan application data and presents the main findings in an interactive Streamlit dashboard.

The dashboard looks at approval patterns, applicant information, financial indicators and some simple risk signals. It also includes a Logistic Regression model that gives an illustrative loan approval prediction.

## Tools Used

- Python
- Pandas
- NumPy
- Plotly
- Streamlit
- Scikit-learn

## Dataset

**Loan-Approval-Prediction-Dataset (Kaggle)**  
https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset

The dataset has 4,269 loan applications and 13 columns. It includes details such as income, loan amount, loan term, CIBIL score, education, employment status, asset values and loan status.

## Dashboard Sections

1. **Executive Overview** – basic application and approval statistics
2. **Applicant Intelligence** – approval patterns by applicant category and income/loan analysis
3. **Financial Risk** – loan-to-income, CIBIL and asset-related analysis
4. **Decision Intelligence** – converts the main findings into possible actions
5. **Loan Predictor** – gives an illustrative prediction using the trained model

## Files

- `Samruddhi_Misal_LoanIntelligence.ipynb` – project code
- `requirements.txt` – required Python libraries
- `Samruddhi_Misal_LoanIntelligence_ProjectReport.docx` – project report
- `README.md` – project information and setup details

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run loan_intelligence.py
```

## Note

The prediction model is included for project demonstration. It is not intended to be used as an actual loan approval or credit decision system.
