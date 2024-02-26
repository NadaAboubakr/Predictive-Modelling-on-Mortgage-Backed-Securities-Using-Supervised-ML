# Predictive-Modelling-on-Mortgage-Backed-Securities-Using-Supervised-ML
**Overview:**
This project aims to predict prepayment risk for mortgage-backed securities (MBS) using supervised machine learning techniques. Prepayment risk refers to the possibility of borrowers paying off their mortgages earlier than expected, affecting the cash flows and returns on MBS investments.

**Dataset:**
The dataset used in this project is obtained from the Freddie Mac official portal for home loans. It contains 291,452 data points and 28 columns, representing various features such as borrower characteristics, loan details, property information, and more.

**Project Structure:**
- **Data Exploration and Cleaning:** Initial exploration of the dataset, handling missing values, outliers, and encoding categorical variables.
- **Feature Engineering and Selection:** Creation of new features, dropping irrelevant features, and selecting important features using techniques like SelectKBest and PCA.
- **Modeling:** Application of multiple linear regression, logistic regression, and handling class imbalance using undersampling.
- **Evaluation:** Assessment of model performance using various metrics such as mean squared error, accuracy, confusion matrix, and classification report.
- **Next Steps:** Suggestions for further improvement, model tuning, and deployment considerations.

**Requirements:**
- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn

**Usage:**
1. Clone the repository:
   ```git clone [https://github.com/your_username/mbs-prepayment-risk-prediction](https://github.com/NadaAboubakr/Predictive-Modelling-on-Mortgage-Backed-Securities-Using-Supervised-ML).git```

2. Navigate to the project directory:
   ```cd Predictive-Modelling-on-Mortgage-Backed-Securities-Using-Supervised-ML```

3. Install the required dependencies:
   ```pip install -r requirements.txt```

4. Run the main script to execute the analysis:
   ```python main.py```


