# Bad-Debt-Prediction-Model_Hackatton
The Hackathon was to predict timely risk analysis of the accounts that can help lenders forecast the number and value of accounts that are at risk of developing into a Bad Debt in near future and eventually help mitigate the losses.
Business Context
The real estate sector can be very unpredictable and susceptible to a downturn in times of economic crisis. Whenever the economy suffers, the number of stressed assets can become a huge problem for housing finance companies. The bad debt and stressed assets result in a liquidity crunch and impact the banks that are lenders to both developers and property buyers. Timely risk analysis of these accounts can help lenders forecast the number and value of accounts that are at risk of developing into a Bad Debt in near future and eventually help them mitigate the losses.

About the Data
The data belongs to the billing systems of various societies. These societies could be residential or public. The data has been collected over the years and has been summarised according to the total amount billed versus the total amount generated from the consumers. For each account, there is a label indicating whether an account resulted in a Bad Debt (the account that would be unable to pay the amount).

Feature Summary
AccID: An unique id for the account

CategoryID: An unique id for the category of the society

Category: Category of society

Value: The market value of the particular property (account)

PropertySize: The size of the property in square meters

BillingAmt: The total amount payable by the resident to the society management

AverageBillingAmt: The average amount payable by the resident to the society management

CollectedAmt: The total amount collected from the resident

AverageCollectedAmt: The average amount collected from the resident

DebtAmt: The Total Debt that is at 90 days or more

WriteOffAmt: The Total amount of debt that has been written off

CollectionRatio: The ratio between the Total amount collected and Total Billing (ie. CollectedAmt/ BillingAmt)

DebtBillingRatio: The ratio between the Total Debt and Total Billing (ie. (Total Debt + Total Write Off)/Total Billing)

TotalElectricityBill: The total amount billed for electricity. This field was put in place because it is used as a means to recover debt - ie. If an amount is outstanding for any service the management has the right to cut a consumer's electricity connection.

HasID: The resident has an ID number.

Label: 1 = Is considered to be a Bad Debt, 0 = Not considered to be a Bad Debt
