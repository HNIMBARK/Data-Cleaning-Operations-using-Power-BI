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

•  Connect to this **CSV** using Power BI Desktop by selecting **Get data** in the toolbar (as shown) and then selecting **Excel workbook**:

<img width="1426" height="716" alt="image" src="https://github.com/user-attachments/assets/013d6a4a-99c2-4d76-a845-9d33ec94488f" />


### Select **Products.xlsx** file

<img width="651" height="463" alt="image" src="https://github.com/user-attachments/assets/a6a51a03-217f-4874-aae5-bfe94c6309b2" />

select **Transform data**

<img width="1267" height="965" alt="image" src="https://github.com/user-attachments/assets/dfe21c95-cab2-4909-b6f5-3a152c0c7691" />

### Transform Data view

<img width="1523" height="747" alt="image" src="https://github.com/user-attachments/assets/207337e4-dfdf-4b0a-82f3-01d81ca5fcdc" />


## Remove Duplicates

Navigate to the**Home** tab in the toolbar  and then select **Transform Data** to access the Power Query Editor.

2. Now select the column in which the main identifier and duplicate is located. In this case, we want to select **Product_Name**.
3. With that column selected, you can now select **Remove Rows** within the toolbar and select  **Remove Duplicates**

<img width="1438" height="620" alt="image" src="https://github.com/user-attachments/assets/f33d6b21-cdd1-4c37-8ec8-25265a84f9d6" />

## Removing missing data

•  Resolve the **null values** problem by selecting **Remove Blank Rows**
•  The UI for the Remove **Bottom Rows** or **Top Rows** or **Alternate Rows** function within **Power Query**.


<img width="1307" height="651" alt="image" src="https://github.com/user-attachments/assets/56dc8286-0d42-42fb-8213-6dfaf96aead8" />


## Splitting columns

•  The drop-down menu above the split column function (left) and a close-up of the UI for the Split Column by **Delimiter**function (right)

<img width="1251" height="440" alt="image" src="https://github.com/user-attachments/assets/26fb7da6-1700-4bc0-94ac-9b61195fcded" />

### Specify the delimiter

<img width="1008" height="820" alt="image" src="https://github.com/user-attachments/assets/65f25f36-c3a9-467f-8409-7eadb8b7fced" />


#### Then rename the columns to the appropriate fields, as shown. This can be done by right-clicking on the column headers and selecting **Rename**.


## Merging columns

•  In the **Merge Columns** confguration window, you can select a separator to sit between the merged values. As we are working with dates, we can select **Custom** and add **/** as the custom separator.


<img width="1023" height="482" alt="image" src="https://github.com/user-attachments/assets/2c23191c-8538-4cc8-9271-556225c939e8" />

#### Specify the separator

<img width="1001" height="444" alt="image" src="https://github.com/user-attachments/assets/c8241463-0250-4753-b199-8451ba3e3f17" />


## Replacing values
•  The UI for the **Replace Values** function within Power Query

![télécharger (8)](https://github.com/user-attachments/assets/18b435b9-ead6-418c-8fff-b963286ec232)

•  Creating calculated columns versus measures.

## Measures

•  The new measure has been added to the products table within the **Power BI** service
•  Measures can be identified with the calculator logo and calculated columns can be identified with the table logo to the left of the value.

![télécharger (11)](https://github.com/user-attachments/assets/f2463dbc-eeaa-4edd-bd52-a4af3401b4e5)

## Calculation group
•  Calculation groups were introduced in **Power BI** to tackle the challenges associated with managing a large number of repetitive measures and to simplify the logic applied in diverse calculations.

![télécharger (10)](https://github.com/user-attachments/assets/3a5670c7-f712-4863-adf0-683df4630eaf)


## License
•  This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
•  Contributions .
•  Educational resources and datasets from renowned institutions and projects in the field.
