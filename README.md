# Shopify Provider App

Shopify Provider App is a demo application to provide examples for composer package, PHPSpreadsheet, Shopify API etc. usages.

This project aims to take an Excel file from user, parse it and save each product from each row to projects own database. Then read that data and import each product to Shopify through their API.

-   A web page asks for an Excel file
-   User uploads an Excel file from that form
-   System reads and validates Excel 
-   Translates to any language if need (with Google Cloud Translate api)
-   Saves every row in sheets.
-   Imports those data to Shopify
