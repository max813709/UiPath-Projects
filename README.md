
# <strong>RoSA Bot</strong>

A robotic shopping assistant.

## <strong>Technologies Used</strong>

[UiPath Studio 2020.10.7+](https://www.uipath.com/product/studio): Development environment.

[Pega](https://training.openspan.com/login): a simulated purchase order website.

[Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads): A database to store customer shopping lists/identifying information.

Microsoft Excel: A media used to store customer reciepts for email automation and record keeping.

## <strong>Features</Strong>

Takes customer information stored on SQL server.
Uses UI Attended Automation to shop for items listed on the database through the Pega website.
Uses UIPath Web Scraping and UI Explorer to enter customer identifying information into the required fields on the Pega Website.
Submits orders and calculates order totals and subtotals on an excel spreadsheet.
Emails excel expense reports including order totals, items purchased and service fees.
Emails the user a profit report detailing the accumulation of service fees for every simulated customer.

## <strong>Getting Started</strong>

Set up a SQL database containing all of the simulated customer orders

![]()<img width="723" alt="image" src="https://user-images.githubusercontent.com/104387212/174142399-2b04dd51-7e14-4e78-aa12-be581b698770.png">

Scrapes shopping order items from the database and using UI Attended Automation orders from the Pega website.

Proceeds to scrape from the SQL database containing all of the simulated customer information.

![]()<img width="568" alt="image" src="https://user-images.githubusercontent.com/104387212/174142675-bbfc06bd-1685-4c81-9958-5623457c679a.png">

Using UI Attended Automation enter the simulated customer information into the Pega website.

Purchase orders and using UI Automation and Excel Automation writes the purchase orders onto an Excel file.

Writes a profit report using email automation and excel automation to include the items purchased, the subtotal, the service fee and the purchase total for the entire order for each customer.

Writes a profit report for all simulated customers that is automated to be emailed to the user.

## <strong>Contributors</strong>

Matthew Emsak

Marielle Nolasco (trainer)

Marielle's RPA Batch 4.25.22

## <strong>License</strong>

This project uses the following license: MIT.
