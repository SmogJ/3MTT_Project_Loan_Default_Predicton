# HMEQ LOAN DEFAULT PREDICTION

## DESCRIPTION
This Project is one amongst project carried out in the 3MTT program. 

### PROBLEM STATEMENT
A bank's consumer credit department aims to simplify the decision-making process for home equity lines of credit
to be accepted. To do this, they will adopt the Equal Credit Opportunity Act's guidelines to establish an empirically
derived and statistically sound model for credit scoring. The model will be based on the data obtained via the
existing loan underwriting process from recent applicants who have been given credit. The model will be built
from predictive modeling techniques, but the model created must be interpretable enough to provide a
justification for any adverse behavior (rejections).

• Perform EDA and feature analysis to give recommendations to the bank on the key features to consider
while approving a loan.
• Build a classification model to predict clients who are likely to default on their loan
• **Maximizing Recall (false negatives)** as banks are more fearful of defaulters given they result in greater
loss.
• Preferably maintaining a **high F1-Score (overall accuracy) as false positives** would result in a loss of
interest profit for the bank.
• Build a classification model to predict clients who are likely to default on their loan
• Give recommendations to the bank on the important features to consider while approving a loan.


### DATA DESCRIPTION
The **Home Equity dataset (HMEQ)** contains baseline and loan performance information for 5,960 recent home
equity loans. The target (BAD) is a binary variable that indicates whether an applicant has ultimately defaulted or
has been severely delinquent. This adverse outcome occurred in 1,189 cases (20 percent). 12 input variables were
registered for each applicant.

__BAD:__ 1 = Client defaulted on loan, 0 = loan repaid
__LOAN:__ Amount of loan approved.
__MORTDUE:__ Amount due on the existing mortgage.
__VALUE:__ Current value of the property.
__REASON:__ Reason for the loan request. (HomeImp = home improvement, DebtCon= debt consolidation which
means taking out a new loan to pay off other liabilities and consumer debts)
__JOB:__ The type of job that loan applicant has such as manager, self, etc.
__YOJ:__ Years at present job.
__DEROG:__ Number of major derogatory reports (which indicate a serious delinquency or late payments).
__DELINQ:__ Number of delinquent credit lines (a line of credit becomes delinquent when a borrower does not make
the minimum required payments 30 to 60 days past the day on which the payments were due).
__CLAGE:__ Age of the oldest credit line in months.
__NINQ:__ Number of recent credit inquiries.
__CLNO:__ Number of existing credit lines.
__DEBTINC:__ Debt-to-income ratio (all your monthly debt payments divided by your gross monthly income). This
number is one-way lenders measure your ability to manage the monthly payments to repay the money you plan
to borrow.

### METHOD OF EVALUTION 
**_Recall_**
**_F1 Score_**

## PROJECT DEVELOPMENT PROCESS

- EDA
viusalizing data for: 
    * Correlation, 
    * anomalies, 
    * cental tendencies
    * Feature importance.
- Date wrangling
    * Handling missing value usig mean, median, and fill.
    * Ecoding Categorical Variable
    * Standardizing features