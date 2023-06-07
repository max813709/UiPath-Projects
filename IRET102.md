# <strong> IRET102 </strong> #

## <strong> Description </strong> ##

An automated method of logging into IBS Insight to acquire page-scrapped details and record several account details on Excel.

## <strong> Technologies Used </strong> ##

[UiPath Studio 2020.10.7+](https://www.uipath.com/product/studio): Development Environment.

[IBS Insight](https://insight.fisglobal.com/opstopb1/OpstopServlet/Logon): A webpage that holds customer banking info.

[UiPath Orchestrator](www.cloud.uipath.com/): A functionality that enables the timed trigger for stock price recording.

[Microsoft Excel]: Used to store customer information.

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/6ef05568445046edd9a049cbb39eda4595a36ad4/Picture2.png">

## <strong> Features </strong> ##

•	Used app/recorder and logged into IBS insight
•	Used type into activities to enter each account number into the search bar
•	Used for each row activity and variable manipulation to cycle through a list of account numbers
•	Used the assign activity and row.item for each account
•	Logged details of automation for consistency
•	Scraped contents of page and used get text and click activities for each account number to gather bank branch details, as well as email automation and return code details
•	Used an add data row activity to record the details to an excel sheet
•	Split project goals into several workflows
•	Used Email automation to forward excel file to user

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/3ca8c45c98dd94236520d8dcaded3765c86c1014/image-2.png">


## <strong> Contributors </strong>
Matthew Emsak

## <strong> License </strong>
This project uses the following license: MiT.
