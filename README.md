# YSP-Project
Maitreyi's Github User: maitreyis15
Nate's Github User: natelevy1

**Research Question:** What is the correlation between race, economic status, and age in terms of health insurance coverage?



**Documentation for Census Data:** https://www2.census.gov/programs-surveys/cps/techdocs/cpsmar22.pdf

**Documentation Analysis that Would be Neccessary for Code:**

*Health Insurance Coverage:*
HCOV - Health insurance in the last year per household
NOW_HCOV - Current health insurance per household
HPUB - public coverage in household in last year
HPRIV - private coverage in household in last year

*Demographic Data:*
PRDTRACE - numerical values for race

*Age Data:*
HUNDER15 - age code for people under 15+
AGE1 - age code for people over 15+

*Economic Status:*
FTOT_R - total family income
HHINC - total household income
FAMLIS - families in poverty



**Basic Coding Steps that are Expected:**
1. Importing all the csvs files utilized as data
2. Analyzing the data and inputting them into arrays or lists in order to be plotted
3. Plot each variable individually such as age, race, and economic status to see trends
4. Plot all of the data together onto one plot
5. Use a regression model in order to model the data accurately
    -Regression Model - regresses insurance status onto age and ethnicity and economic status as a random variable


**Packages:**
-panda
-collections
-statsmodels.api
-matplotlib


**Link to all the Datasets that we will be using in this project:**
https://www.census.gov/data/datasets/time-series/demo/cps/cps-asec.html

**Expected Results:**
We expect to see a significant correlation between race,age, and economic status with the rate of health insurance coverage. On the regression model we expect to see a line of best that will accurately show the relationship between the two variables.

**Link to Repository:** https://github.com/nathanielslevy/YSP-Project
