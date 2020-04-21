## Exploratory Data Analysis on Loan Defaulters and Driving Factors towards Loan Defaults

### Abstract
This project is related to a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss).

Business objective: The objective is to identify the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

### Approach
1.Clean the Loan Database
2.Considering the data dictionary identify the columns related to Consumer attributes and Loan attributes
3.Build derived variables to extract more insight out of data
4.Run univariate and multivariate segment analysis to check the behavior of the attributes and their relation to loan default
5.Ensure that the conclusions make business sens

### Notebook
Please refer the Jupyter Notebook for extensive analysis.

### Conclusion
To summarize our findings:

1. Borrowers with Home Ownership status as OTHER and with low annual income had a higher tendency of default
2. Same trend applies to Borrowers with high debt to income ratio, the higher the ratio the higher the default rate
3. Borrowers from states like NE, NV, SD, AK, FL had a higher default rate compared to the rest of the country
4. Borrowers inquiring for loans multiple times in the past 6 months are in general, high defaulters and care should be taken while dealing with them
5. Borrowers with a public record or having earlier bankruptcy instances have higher default rate
6. Those who have a previous history of closed loans were in general trustworthy and defaulted less
7. Loans given for the purpose of small business, renewable energy, education tended to default more
8. The default rate was directly proportional to the interest rate and inversely to the loan grade
9. Also last but not the least a trend was observed that the loans of term 60 months defaulted much more than that of 36 months

In general if caution is exerted focusing on these factors while lending out money we believe that the default rate would drop.
