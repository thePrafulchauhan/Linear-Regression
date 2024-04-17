# Linear-Regression
Problem Statement: Given a set of attributes for an Individual, determine if a credit line should be extended to them. The main challenge is to minimise the risk of NPAs by flagging defaulters while maximising opportunity to earn interest by disbursing loans to as many customers as possible
Data dictionary
1. loan_amnt : The listed amount of the loan applied for by the borrower. If at some
point in time, the credit department reduces the loan amount, then it will be
reflected in this value.
2. term : The number of payments on the loan. Values are in months and can be either
36 or 60.
3. int_rate : Interest Rate on the loan
4. installment : The monthly payment owed by the borrower if the loan originates.
5. grade : LoanTap assigned loan grade
6. sub_grade : LoanTap assigned loan subgrade
7. emp_title :The job title supplied by the Borrower when applying for the loan.
8. emp_length : Employment length in years. Possible values are between 0 and 10
where 0 means less than one year and 10 means ten or more years.
9. home_ownership : The home ownership status provided by the borrower during
registration or obtained from the credit report.
10. annual_inc : The self-reported annual income provided by the borrower during
registration.
11. verification_status : Indicates if income was verified by LoanTap, not verified, or if the
income source was verified
12. issue_d : The month which the loan was funded
13. loan_status : Current status of the loan - Target Variable
14. purpose : A category provided by the borrower for the loan request.
15. title : The loan title provided by the borrower
16. dti : A ratio calculated using the borrower’s total monthly debt payments on the
total debt obligations, excluding mortgage and the requested LoanTap loan, divided
by the borrower’s self-reported monthly income.
17. earliest_cr_line :The month the borrower's earliest reported credit line was opened
18. open_acc : The number of open credit lines in the borrower's credit file.
19. pub_rec : Number of derogatory public records
1/28/24, 12:05 AM praful_LoanTap_Assignment
localhost:8889/nbconvert/html/Downloads/praful_LoanTap_Assignment.ipynb?download=false 2/30
20. revol_bal : Total credit revolving balance
21. revol_util : Revolving line utilization rate, or the amount of credit the borrower is
using relative to all available revolving credit.
22. total_acc : The total number of credit lines currently in the borrower's credit file
23. initial_list_status : The initial listing status of the loan. Possible values are – W, F
24. application_type : Indicates whether the loan is an individual application or a joint
application with two co-borrowers
25. mort_acc : Number of mortgage accounts.
26. pub_rec_bankruptcies : Number of public record bankruptcies
27. Address: Address of the individual
