Data set : House hold Energy consumption Analysis
Removed duplicates and cleaned the data using duplicate , replace , sum and Average.
Imported the data in power BI 
Visulized and analysed the data using pie charts , bar charts , cards and Guage charts
Total Electricity = SUM('Households'[Electricity Usage])
Total Gas = SUM('Households'[Gas Usage])
Avg Elec per Person = DIVIDE([Total Electricity], SUM('Households'[Family Size]))
Created the cards for sum of electrical usage , Gas usage and Family size in the dashboard
As per the analysis if the Appliance count is less than 8 The electricity usage will be less
If the family size is less than 4 the electrical or gas usage will be less



