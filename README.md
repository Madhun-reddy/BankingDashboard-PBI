
# Loan Risk Analysis

## Details of Assignment

![Details of Assignment](https://github.com/Madhun-reddy/BankingDashboard-PBI/assets/119162777/4a2ca0f3-e524-4884-9a18-d3108460f83b)

# Loan Risk Dashboard

![Risk Dashboard](https://github.com/Madhun-reddy/BankingDashboard-PBI/assets/119162777/3cd500a5-8785-49a6-a60c-ad87009d0c15)


## Problem Statement

![Requirements](https://github.com/Madhun-reddy/BankingDashboard-PBI/assets/119162777/1db127f6-6e24-4fe8-aa66-8917ac133769)


## Data Sourcing

Data sourced from an Assessment test in Excel format. Then uploaded into Power BI using GET DATA --> Excel Worksheet to Power Query.

## Data Transformation

Data cleaning and transformation was carried out using Power Query. After scrutinising all the Columns, they were found to be valid and devoid of empty cells and errors. However, it was highly important that I transformed the Loan Amount & DPDs columns which were needed for Summarizing Data.

Therefore, I created 4 new columns all extracted from the source columns mentioned above.

	• The first column contained Loan amount details through which derived to Loan Band and Loan Band Sort columns 
	• The second column was also manipulated from DPDs column to DPD Band and DPD Band Sort columns which were later used in summarizing data.
	• For consistency columns have been renamed.
    	![Screenshot 2024-01-31 174321](https://github.com/Madhun-reddy/BankingDashboard-PBI/assets/119162777/9ec7520e-2dd6-4505-beba-470ff020383f)



## Data Modelling

No modelling was required since it was just a single spreadsheet.


## Analysis & Visualisation

Here we could discover the following insights:

	. There has been 493 total number of loans are comes under risk segment with an average ticket value of 18.3lacs in that salaried group accounts for 57% with a 90+ DPD rate of 32% for May 2023.
	. Day Range slicer given for opting any range in a MTD of May 2023
	. Approx 65% share of Loans in loan band 10 - 20 lacs range and which is contributing 30% of Default Risk.
	. We can also see % share of loans to 90+ DPD loans rate each Region wise and also in Map. 
	

## Conclusion and Recommendation

We can come to a conclusion that this is huge high risk indicator having greater than 32% of 90+ DPD puts lender at bankruptcy. Since this dataset is a sample we need not worry much.


# Loan Sales Dashboard

## Analysis & Visualisation

![Loan Sales Dashboard](https://github.com/Madhun-reddy/BankingDashboard-PBI/assets/119162777/73fdb3d5-7a44-4ffb-9753-f885ed34f2c3)


## Problem Statement

![Requirements](https://github.com/Madhun-reddy/BankingDashboard-PBI/assets/119162777/2c600593-98ff-44ec-b98c-52fe06f6604c)



