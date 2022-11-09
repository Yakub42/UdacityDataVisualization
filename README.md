# UdacityDataVisualization
## PROSPER LOAN EXPLORATION 
## by Adedeji Yakub

### INTRODUCTION
This project is focused on the analysis and visualization of a loan dataset.
The objectives of this project is to generate insights using visualization techniques in the python programming language modules.
The python modules used include:
- Pandas
- Matplotlib
- Numpy
- Seaborn

The dataset consists of information 114,000 rows of loan data, and 81 variables including Loan amount, Borrower Income( Stated Monthly Income), Debt-Income-Ratio, Loan Term, Prosper Score and many others. The dataset can be found here, with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Data Wrangling
1. A subset of dataframe was created with necessary columns.
2. Dataframe was assessed for Data Quality and Tidiness Issues.
2. Missing values were appropriately treated.
3. Categorical variables that are ordinal, are converted using pandas Categorical Dtype.
4. Homeowner colummn was converted to string format.


## Summary of Findings
In the exploration process, I discovered that with borrowers with a relatively low Monthly Income, the probabilities of getting a Low or High 
Loan Amount is slightly similar. However, with a High Monthly Income, the Loan Amount received is Higher.

A strong relationship exists between the Monthly Payments and the Loan amount with modifying effect from the Loan Term. On encoding a bivariate plot, with a third variable Loan Term, the Visualization shows that Borrowers with longer Loan Term (36 or 60 months) receives larger Loan amounts.

There was also an interesting relationship between Loan Amount and the Categorical features. More Loans are associated with Borrowers with a Longer loan Term, Low risk involved(high Prosper Score), Owning a Home and being successfully employed.
