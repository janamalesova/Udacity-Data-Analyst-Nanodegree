# Prosper Loans Exploration

## Dataset

The loans dataset contains 113k+ Prosper loans from the period 2005-2014 and 81 variables. Prosper is a US peer-to-peer landing company founded in 2005, so the dataset covers the first years of their business.<br>
I selected just a small subset from available variables with the help of the data dictionary.<br>
The data collection went through changes in 2009. Due to that, a new credit rating column was created to include a rating for loans of all ages regardless of their origin date.<br>
Once one of the redundant rating columns was deleted, we could clean duplicates from the data.<br>
Variables which are ordinal were converted to the ordinal type.<br>
Credit risk variable was created by grouping several credit ratings into one category.<br>


## Summary of Findings

Credit rating variables, namely CreditGrade and ProsperRating were investigated after merging them into a single CreditRating variable. Credit rating is highly related with the interest rate and loan amount. Results of this analysis are included in the explanatory presentation.<br>
Income range of borrowers and home ownership are also interesting viewpoints which were analysed and the income range results are included in the presentation.<br>
The strong relationship of monthly payments and loan amounts is pointed out in the presentation.<br>
I also looked into the development in time and included relevant parts in the presentation.<br>
Majority of loans are for the term of 36 months. Term interaction with other variables was investigated heavily, but since 36m months term makes such a large share of all loans, I did not include this part in the explanatory part.<br>
Some variables were problematic, like EmploymentStatus, categories of which seemed to have been changed in time, but not very consistently and so it is not very clear how categories are assigned and this part of the investigation is also not included in the explanatory presentation.<br>

Some of the main findings from the exploratory analysis are the following:

* The more risky the loan, the higher the interest rate and the lower the borrowed amount.
* Interest rate decreases and borrowed amount increases with higher income of the borrower.
* Home owners pay a lower interest and borrow higher amounts.
* Higher loan amounts are borrowed for longer term.


## Key Insights for Presentation

I chose some of the strongest variables for differentiation of borrower groups, and these are credit rating and income range.<br>
From the loans perspective, I looked into borrower annual percentage rate, loan amount and monthly payments.<br>
The polishing for presentation included grouping plots from various parts of the exploratory analysis together, labeling all axes and adding plot titles, removing spines and adjusting some legends.