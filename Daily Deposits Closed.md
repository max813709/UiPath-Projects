# <strong> Daily closed Accounts </strong> #

## <strong> Description </strong> ##

An automated method of downloading the latest report from a directory, while logging into IBS insight, 
downloading a .csv report from a webpage, and comparing the two Excel spreadsheets for account numbers, 
while simultaneously formatting one of these reports with a macro.

## <strong> Technologies Used </strong> ##

[UiPath Studio 2020.10.7+](https://www.uipath.com/product/studio): Development Environment.

[IBS Insight](https://insight.fisglobal.com/opstopb1/OpstopServlet/Logon): A webpage that holds customer banking info.

[UiPath Orchestrator](www.cloud.uipath.com/): A functionality that enables the timed trigger for stock price recording.

[Microsoft Excel]: Used to store customer information and is the environment for the macro.

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/6ef05568445046edd9a049cbb39eda4595a36ad4/Picture2.png">

## <strong> Features </strong> ##

•	Used string manipulation to find the latest report in a directory
•	Logged into IBS insight using a w number to download a .csv report for comparison
•	Used a for each file in a folder activity Copy File to activities to open an restricted version of the excel spreadsheet
•	Used an Excel Macro to open the latest report in the directory
•	Compared the two reports for an account number column
•	Saved both reports in the restricted directory

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/654bcbce720f972b725548dfb7e25a2643181bcd/image-7.png">

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/654bcbce720f972b725548dfb7e25a2643181bcd/image-8.png">

## <strong> Contributors </strong> ##
Matthew Emsak

## <strong> License </strong> ##
This project uses the following license: MiT.
