# LendingClubCaseStudy
Apply EDA technique to minimise risk of losing money while lending to customer

## Table of Contents
General Info
Conclusions
Contributors

# General Information and business requirement 
Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refusesto pay or runs away with the money owed.

The main objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default.
The company can utilise this knowledge for its portfolio and risk assessment.

# Using following steps for data processing.
Step 1: Data Cleaning
Step 2: Univariate Analysis
Step 3: Segemented Univariate Analysis
Step 4: Bivaraiate/Multivariate Analysis
Step 5: Results/Conclusion

# Conclusions

**Loan Purpose:** Debt consolidation and credit card payoff are the most common purposes, indicating a prevalent use of these loans for managing existing debt.

**Seasonal Trends:** There is a clear seasonal pattern in loan issuance, peaking in December, which may reflect borrowers financial planning trends at year-end.

**Income Verification and Default Rates:** The status of income verification does not consistently correlate with lower default rates, suggesting that it should not be overly relied upon, especially for larger loans.

**Account Number Risks:** The number of open accounts presents a U-shaped risk profile, where very low and very high counts are associated with increased default risks, highlighting the complexity of financial management among borrowers with extreme numbers of credit lines.


Loans with below criteria are highly contributing to charged off:
 * Loans with higher interest rate (>12%)
 * Loans with grade 'F' and loan amount > 20K
 * Higher amount loans (>13K) for small business, debt consolidation or credit card
 * Borrower Debit to income ratio > 25% and loan amount > 15K
 * Borrower annual income <50K and loan amount > 5K

# Contributors
Suhas Naik K
Subrata Das

Developed as part of the Exloratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
