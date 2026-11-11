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
| CW_Sales_2018.csv | Sales orders 2018 (exercise 9) | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Sales_2018.csv` |
| CW_Sales_2019.csv | Sales orders 2019 (exercise 9) | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Sales_2019.csv` |
| CW_Sales_2020.csv | Sales orders 2020 (exercise 9) | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/CW_Sales_2020.csv` |
| Logo.png | CompuWorld logo for your report | `https://raw.githubusercontent.com/JstnsMvX/srh-bi-data/main/Logo.png` |

## Connect in Power BI (online)

1. Go to app.powerbi.com and click **New report** (or **Create** in the left bar), then **Get Data**. Already in Power Query? Use **Home > Get data**.
2. Pick **Excel workbook** (for the .xlsx files) or **Text/CSV** (for the .csv files).
3. Select **Link to file** and paste the link from the table above.
4. The first time, fill in the connection settings:
   - Connection: **Create new connection**
   - Data gateway: **(none)**
   - Authentication kind: **Anonymous**
5. Click **Next** and select the table you need. Later links reuse the same connection: just click **Next**.

CW_Region_Lookup.csv uses a semicolon (`;`) as delimiter; the sales CSV files use a comma.

## Connect in Power BI Desktop

**Get data > Web**, paste the link and choose **Anonymous** when asked for credentials.
