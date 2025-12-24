# Data-Cleaning-Operations-using-Power-BI
Most Commun Data Cleaning Operations using Power BI

In this project we will cover the following specific topics:
•  Removing duplicates
•  Removing missing data
•  Splitting columns
•  Merging columns
•  Replacing outliers
•  Creating calculated columns versus measure

## Load Dataset
Connect to this CSV using Power BI Desktop by selecting Get data in the toolbar (as shown) and then selecting Excel workbook: Products.xlsx
select Transform data
## Remove Duplicates
Navigate to the Home tab in the toolbar  and then select Transform Data to access the Power Query Editor.
2. Now select the column in which the main identifier and duplicate is located. In this case, we want to select Product_Name.
3. With that column selected, you can now select Remove Rows within the toolbar and select  Remove Duplicates
licates Remove Duplicates
## Removing missing data
if you have an entire row with null values, then you can resolve 
this by selecting Remove Blank Rows
The UI for the Remove Bottom Rows function within Power Query
## Splitting columns

The drop-down menu above the split column function (left) and a close-up of the UI for the Split Column by Delimiter function (right)

Then rename the columns to the appropriate elds, as shown. is can be done by right-clicking on the column headers and selecting Rename
## Merging columns
In the Merge Columns conguration window, you can select a separator to sit between the merged values. As we are working with dates, we can select Custom and add / as the custom separator.
## Replacing values
The UI for the Replace Values function within Power Query
Creating calculated columns versus measures
## Measures

The new measure has been added to the products table within the Power BI service
Measures can be identified with the calculator logo and calculated columns can be identified with the table logo to the left of the value.
## Calculation group
Calculation groups were introduced in Power BI to tackle the challenges associated with managing a 
large number of repetitive measures and to simplify the logic applied in diverse calculations

