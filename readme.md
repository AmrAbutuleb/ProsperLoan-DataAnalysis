# ProsperLoan Dataset
## by Amr Abutuleb


### Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This data dictionary explains the variables in the data set. we focus on a less number of variables in our exploration of only 23 variables and we drop any rows that has any missing values. Thus, ending with 76,312 loans to explore with our different methods. 


### Summary of Findings
<ol>
<li>LoanStatus of all Borrowers are with current and completed state </li>
<li> EmploymentStatus of all Borrowers are with Employed State </li>
<li> Top IncomeRange of all Borrowers are within $50,000-74,999 </li>
<li>Majority of the borrowers are with an occupation of Professional and Executive </li>
<li>Majority of the borrowers are with a rating or score from 4 to 8 </li>
<li>The borrowers rate follow an approximately unimodal distribution, with the peak around 0.15. </li>
<li>The origination amount of the loan is interesting. Here we see that the distribution is a right skewed with multiple peaks observed at 4000 USD, 10000 USD and 15000 USD. </li>
</ol>

### Key Insights for Presentation

For the presentation, I focused mainly with the features that are impactful for approval of loanstatus I start by looking at the distrbuiton of each and every numeric and categorical variables and did all the necessary univariate, bivariate and mulitvariate analysis on the selected varaibles.

The major insights obtained are :
<ol>
<li>The monthly income of borrowers are having higher values for employed, other and full time employment status with the prosper rating of AA, A and B.</li>
<li>For Applicants with prosper ratings from AA to D have the higher loan amount with increased salary.</li>
<li>Our Most important observation is that without homeowner tend to have a higher interest rate, and thus lower rating. However homeowner tends to have lower interest rate and higher rating. So we can safely say that homeowner is safest bet when gving a loan. We can also clearly observe that HR prosper rating applicants have higher interest rates</li>
<li>To conclude this analysis , We say that the loan approval status is heavily dependent on the applicant's information on IncomeRange, Homeownerstatus and employment status as our analysis showed that the LoanStatus is heavily dependant on these variables.</li> 
</ol>
