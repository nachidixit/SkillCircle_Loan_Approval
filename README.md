# SkillCircle_Loan_Approval

# Loan Approval EDA Project

This project performs **Exploratory Data Analysis (EDA)** on a dataset related to **Loan Approval**. It includes:
- Data cleaning and preprocessing
- Univariate, bivariate, and multivariate visualizations
- Correlation and categorical cross-tab analysis
- Recommendations based on patterns and trends

---

## Project Structure

```
Loan_Approval_EDA/
│
├── Loan_Approval/
│   └── loan_sanction_test.csv              # Dataset file
     ├── loan_eda.ipynb                     # Jupyter notebook version
│
├── requirements.txt                        # Python dependencies
└── README.md                               # Project overview and setup instructions
```

---

## How to Run

1. **Clone this repository** or download the files.
2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Place the dataset** in the `data/` folder.
4. **Run the analysis**:
   loan_approval_analysis

---

## Output
- Visualizations will display inline.
- Insights will be printed in the terminal.

---

## Dataset Fields
- `Loan_ID`: Unique identifier
- `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`
- `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`
- `Property_Area`

---

## Recommendation Highlights
- High-income applicants generally request higher loans
- Credit history plays a significant role in loan approval
- Urban areas dominate the dataset, but rural zones show unique patterns

---

## License
Open License
