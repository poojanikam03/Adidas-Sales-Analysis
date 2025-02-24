
An Adidas sales dataset is a collection of data that includes information on the sales of Adidas products. This dataset includes details such as the number of units sold, the total sales revenue, the location of the sales, the type of product sold, and any other relevant information.
Adidas sales data can be useful for a variety of purposes, such as analyzing sales trends, identifying successful products or marketing campaigns, and developing strategies for future sales. It can also be used to compare Adidas sales to those of competitors, or to analyze the effectiveness of different marketing or sales channels.
There are a variety of sources that could potentially provide an Adidas sales dataset, including Adidas itself, market research firms, government agencies, or other organizations that track sales data. The specific data points included in an Adidas sales dataset may vary depending on the source and the purpose for which it is being used.
Columns :-
Retailer : Represents the business or individual that sells Adidas products directly to consumers.
Retailer ID : A unique identifier assigned to each retailer in the dataset.
Invoice Date : The date when a particular invoice or sales transaction took place.
Region : Refers to a specific geographical area or district where the sales activity or retail operations occur.
State : Represents a specific administrative division or territory within a country.
City : Refers to an urban area or municipality where the sales activity or retail operations are conducted.
Product : Represents the classification or grouping of Adidas products.
Price per Unit : The cost or price associated with a single unit of a product.
Units Sold : The quantity or number of units of a particular product sold during a specific sales transaction.
Total Sales : The overall revenue generated from the sales transactions.
Operating Profit : The profit earned by the retailer from its normal business operations.
Sales Method : The approach or channel used by the retailer to sell its products or services.

Data Cleaning:-
Reading CSV file into Python.
Checking for Null Values and Replacing Null Values with 0 by using Fillna Method in Python.
Checking For Duplicate Values.
Converting the Price Per Unit Column i.e. in dollar into Indian Rupees and Replacing “$” sign with spaces 
and  also changing dtype to float.
Replacing Commas(,) in any Columns with spaces.
Standardizing the datatypes for data visualization.
Extracting Year, Month as well as Month Name from Invoice Date column.
Calculating the Profit Margin By the Formula:-
df['Profit Margin'] = (df['Operating Profit'] / df['Total Sales']) * 100










