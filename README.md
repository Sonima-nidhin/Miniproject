# Miniproject
Sample-superstore-salesdata
cleaned data in power query remove null values, remove duplicate,trim, cleaned and capitalised each word in
shipmode, customer name,segment, country, city,state, category, subcategory, product name columns
change the date in localise,date,english united kingdom
change sales column as number,profit-currency, discount - percentage
add new column total cost =[@Sales]-[@Profit]
unit price =[@Sales]/[@Quantity]
profit status =IF([@Profit]>0,"profit","loss")
