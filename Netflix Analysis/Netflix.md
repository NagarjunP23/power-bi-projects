### Netflix Data Analysis

Performed the below tasks to analyze the Netflix data:

Download the dataset from: https://www.kaggle.com/datasets/shivamb/netflix-shows/data

Load the data into Power BI.

1) Column Profiling

2) Dealing with missing values (empty/blank):
	- If the missing values will not impact our analysis, then we can keep it as it is.
	- If we know the source of the dataset, we can try to get the missing data.
	- If we don't want any blank values we can fill in some other value.
	
3) Encoding nulls:
	- Using the "Replace Value" under Transform tab we can replace Blanks with other value.
	
4) Imputing missing values:
	- By using Column Distribution and Column Profile, we can use the most popular value to replace Blanks.
	
5) Working with Dates:
	- Set the DataType of Date column as Date, Using Locale if required.

6) Adding new columns of data:
	- Create a new column using Conditional Column.
	
7) Splitting/Extracting data:
	- Extract the text value from a different column to get only the required part using delimiter.
	- Remove Leading/Trailing spaces using Trim.
	
8) Extracting just the first item:
	- If the column contains multiple values seperated by delimiter, based on our requirement we can also extract only 1st value using Extract(Text Before Delimiter).
	
9) Text/Sentiment Analysis:
	- Based on certain values in a column, we can categorize it into custom groups using COnditional column.
	- One problem with this approach is that, we have to build multiple conditiona for Text values as it is Case Sensitive.
	- In order to overcome this we have to change entire text either to UPPER or lower case.
	
10) Filtering unnecessary data (rows or columns):
	- Filter the data based on the Analysis requirements.


