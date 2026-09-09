# ChurnGuard

ChurnGuard is a Streamlit dashboard for customer churn prediction, exploratory analysis, and customer segmentation.

## Features

- Logistic regression churn prediction
- Customer churn probability estimates
- K-means customer segmentation
- Dataset overview and summary statistics
- Interactive exploratory plots

## Run locally

```bash
git clone https://github.com/reyansh12345678890/churnguard-customer-churn-prediction.git
cd churnguard-customer-churn-prediction
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

The app expects `telecomdata.csv` in the project root.

## Deployment

The app can be deployed on Streamlit Community Cloud using `app.py` as the entry point.
