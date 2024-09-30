# customer_insights
Data Quality Assessment

Transactions Sheet:

1. Empty/Null Cells: The "Transactions" sheet contains several columns with multiple empty/null cells. For instance, the "online_order" column has 360 missing/null values. I recommend either deleting these rows or treating them based on the nature of the analysis.

2. Data Uniqueness: The data in the "Transactions" sheet appears to be unique, with no duplicate values. Therefore, the dataset maintains its uniqueness.

3. Datatype Consistency: The "list_price" column, which represents currency values, should have its datatype changed from accounting to currency format. This change will help ensure consistency and validity in the dataset.

4. Datetime Conversion: The "product_first_sold_date" column currently displays simple numbers, such as '38206', instead of the expected date and time values. It is essential to convert the datatype of this column from integer to datetime to accurately represent the date and time information.

5. Inconsistent Dates: Upon review, the values in the "product_first_sold_date" column seem incorrect as they display everything happening on the same day but at different times. To maintain currency and consistency, I suggest either deleting these rows or treating them based on the nature of the analysis.

NewCustomerList Sheet:

1. Empty Cells: The "NewCustomerList" sheet contains multiple columns with empty cells. Similar to the previous sheet, I recommend either deleting these rows or treating them based on the nature of the analysis.

2. Data Uniqueness: The dataset in the "NewCustomerList" sheet maintains its uniqueness with no duplicate values.

3. Incomplete Columns: There are four columns in the "NewCustomerList" sheet that have no names. To avoid ambiguities and incompleteness, it is advisable to delete these columns.

4. Datatype Correction: The columns named "past_3_years_bike_related_purchases," "postcode," and "property_valuation" currently have their datatype set as text. To ensure consistency and enable numerical calculations, I recommend changing the datatype of these columns from text to numbers.

CustomerDemographic Sheet:

1. Empty Cells: The "CustomerDemographic" sheet contains multiple columns with cells that do not contain any values. To maintain data integrity, I suggest either deleting these rows or treating them based on the nature of the analysis.

2. Data Uniqueness: The dataset in the "CustomerDemographic" sheet is unique, with no duplicate values.

3. Gender Categorization: The "gender" column exhibits six different categories: 'M,' 'F,' 'Male,' 'Female,' 'Femal,' and 'U.' To maintain data validity and consistency, I recommend merging 'M' into 'Male,' 'F' and 'Femal' into 'Female,' and keeping 'U' as it is.

4. Inconsistent Values: The "default" column contains inconsistent values. To ensure data consistency, completeness, and validity, it is recommended to delete this column.

CustomerAddress Sheet:

The "CustomerAddress" sheet exhibits no empty/null cells, duplicate values, or inconsistencies. The values appear consistent and correct.

It is imperative to address these data quality issues to maintain the integrity and reliability of the dataset. I recommend implementing the necessary strategies mentioned above to mitigate these issues effectively.

