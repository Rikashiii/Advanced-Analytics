#Assignments
---
1. Do outlier analysis on total bill column of tips dataset.

-  Do outlier analysis on age column of titanic dataset.

-  Do skewness analysis and plotting for 'on-board Service' column of 'airline passenger service' dataset. Also find CoV for first time versus returning customers for the 'Ease of online booking' column.

-  Pandas practice

	Use titanic csv dataset.

	1. Do Exploratory Data Analytics (EDA) on the dataset. (Hint: head(), columns, etc)
	2. Find passengers whose age is between 20 and 2.
	3. Find passengers where gender is female and passenger class is 1.
	4. Find average age of female and male passengers.
	5. Count number of passengers in each passenger class.
	6. Separate passengers who survived (survived column contains 0) and who did not survive (survived column contains 1) into two separate dataframes.
	7. For the above two dataframes, find number of females and males.
	8. Sort the original dataframe on age in descending order and display the top 3 records.
	
	Note : If u want to convert any columns data type to integer, use this:
	
	###df['age'] = df['age].astype('Int64')
	
	To rename columns :
	
	###df.rename(columns={'age':'passenger_age','pclass':'Class'}, inplace = True)