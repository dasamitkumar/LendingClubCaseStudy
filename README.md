# LendingClubCaseStudy 
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The objective of the exercose is to identify factors or parameters which can potentially lead to a loan in 'charged off' status to reduce the financial loss. The case study would be done using Exploratory Data Analysis (EDA) on the provided dataset loan.csv. 

As an outcome, the Case study will provide strong indicators which the Institution can use to reject a loan application as a potential defaulter.

The dataset is provided by the business which corresponds to about 40k loan applicants, with mixed statuses "Fully-Paid", "Charged-Off" and "Current". We will filter only the "Charged-Off" rows as we have to determine drivers for defaulters.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Loan Grades and Sub-Grades - Loans granted to B,C,D amount to majority of defaulters. So, the firm should exercise caution while granting loans to applicants falling in this category. Futher, the company pay attention to applicants who fall in the subgrades B3, B4, B5, C1, C2 as they have tendency to default frequently.
2. Loan Term - Considering 36 months are defaulting more, so Company should device more evaluation while granting short term loan of 3 years.
3. Employment Length - From the data it is evident that applicants who have 10+ years of experience tend to default more. This indicates that experience or employment legth may not give a very indicator or creditworthiness of the individual. Company should more closely evaluate the credit scores of such individuals.
4. House Ownrship - From the data it is clear that individuals in "Rented" house tend to default, indicating that such indiviuals find it difficult in managing Rent and Installaments simultaneously.
5. Verification Status - It is interesting to note that the number of defaulters are more in case of "Verified" individuals. This indicates that company should strengthen the overall verification process.
6. Geographic Indicators: Loan applicants from states like California (CA), Florida (FL), and New York (NY) are more likely to default. The company should check on regional risks, economic activities/trends and modify their loan strategies.
7. Year and Month of Issue Date - It is evident to note that the defaulters are more from the 2011, along with the number of loan applicants which indicates that there is a good economic boost, however to minimise on the risks, company should make their approval process robust. Also it is interesting to note that the loans which are granted in last quarter of the year tesnd to default more, so the Firm should employ caution when granting loans during the holiday season.
8. Loan Interest Rates - Most of the defaulters are between 11% to 16%, which indicates financial stress induced due to the higher interest rates. The company should strive to reduce the interest rates wherever possible to reduce probability of defaulting.
9. DTI - High DTI means applicant have more debt which translates to increased financial burden. Company carefully study the creditworthiness of such individuals who have high DTI. Individuals with 15% and above should be avoided.
10. Annual Income - From provided data we see that most of the defaulters are in bracket of $40k-$60k. Company should evaluate these individuals who fall in this bracket of annual income.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python
Matplotlib
Seaborn
Pandas

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
upGrad EDA module



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
