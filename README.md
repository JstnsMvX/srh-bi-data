# CompuWorld – Business Intelligence course data

Fictional practice data for the CompuWorld case in the Business Intelligence module at SRH Haarlem.

![CompuWorld](Logo.png)

## Files

| File | Contents | Link to use in Power BI |
|---|---|---|
| CW_Sales_2021.xlsx | Sales orders 2021 | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Sales_2021.xlsx` |
| CW_Products.xlsx | Product list with specs and price | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Products.xlsx` |
| CW_Managers.xlsx | Manager per region | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Managers.xlsx` |
| CW_Region_Lookup.csv | Regions (continent, country, city) | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Region_Lookup.csv` |
| Logo.png | CompuWorld logo for your report | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/Logo.png` |

## Connect in Power BI (online)

1. Choose **Get data** and pick **Excel workbook** (for the .xlsx files) or **Text/CSV** (for the .csv file).
2. Select **Link to file** and paste the link from the table above.
3. Fill in the connection settings:
   - Connection: **Create new connection**
   - Data gateway: **(none)**
   - Authentication kind: **Anonymous**
   - Privacy level: **Public**
4. Click **Next** and select the table you need.

Repeat for each file. The CSV file uses a semicolon (`;`) as delimiter.

## Connect in Power BI Desktop

**Get data > Web**, paste the link and choose **Anonymous** when asked for credentials.
