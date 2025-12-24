# Data-Cleaning-Operations-using-Power-BI Project

Most Commun Data Cleaning Operations using Power BI Project

<img width="1684" height="729" alt="image" src="https://github.com/user-attachments/assets/d7902a0e-f987-4844-96ab-9bdda6a8aaa3" />


In this project we will cover the following specific topics:

•  Removing duplicates
•  Removing missing data
•  Splitting columns
•  Merging columns
•  Replacing outliers
•  Creating calculated columns versus measure

## Load Dataset

•  Connect to this **CSV** using Power BI Desktop by selecting **Get data** in the toolbar (as shown) and then selecting **Excel workbook**: **Products.xlsx**

<img width="1426" height="716" alt="image" src="https://github.com/user-attachments/assets/013d6a4a-99c2-4d76-a845-9d33ec94488f" />


<img width="651" height="463" alt="image" src="https://github.com/user-attachments/assets/a6a51a03-217f-4874-aae5-bfe94c6309b2" />

select **Transform data**

<img width="1267" height="965" alt="image" src="https://github.com/user-attachments/assets/dfe21c95-cab2-4909-b6f5-3a152c0c7691" />


<img width="1523" height="747" alt="image" src="https://github.com/user-attachments/assets/207337e4-dfdf-4b0a-82f3-01d81ca5fcdc" />




## Remove Duplicates

Navigate to the Home tab in the toolbar  and then select Transform Data to access the Power Query Editor.

2. Now select the column in which the main identifier and duplicate is located. In this case, we want to select **Product_Name**.
3. With that column selected, you can now select **Remove Rows** within the toolbar and select  **Remove Duplicates**

<img width="1438" height="620" alt="image" src="https://github.com/user-attachments/assets/f33d6b21-cdd1-4c37-8ec8-25265a84f9d6" />

## Removing missing data

•  Resolve the **null values** problem by selecting **Remove Blank Rows**
•  The UI for the Remove **Bottom Rows** or **Top Rows** or **Alternate Rows** function within **Power Query**.


<img width="1307" height="651" alt="image" src="https://github.com/user-attachments/assets/56dc8286-0d42-42fb-8213-6dfaf96aead8" />


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
## License
•  This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
•  Contributions .
•  Educational resources and datasets from renowned institutions and projects in the field.
