# <strong> Month-to-Month Deposit Recorder To Scale </strong> #

An automated recorder from excel file to excel file of the Daily Ending Ledger for several customers, printed every day for several months.

## <strong> Technologies Used </strong> ##

[UiPath Studio 2020.10.7+](https://www.uipath.com/product/studio): Development Environment.

[IBS Insight](https://insight.fisglobal.com/opstopb1/OpstopServlet/Logon): A webpage that holds customer banking info.

[UiPath Orchestrator](www.cloud.uipath.com/): A functionality that enables the timed trigger for stock price recording.

[Microsoft Excel]: Used to store customer information.

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/6ef05568445046edd9a049cbb39eda4595a36ad4/Picture2.png">

## <strong> Features </strong>

•	Acquired a collection of months in an array construct
•	Used excel automation and string manipulation to modify and transpose results
•	Used the Split-String method the String.Replace method and Row.Item to format results
•	Monitored progress through structured logging of events throughout the automation
•	Used the remove duplicate rows activity and the filter data table activity
•	Used for each row and several if statements containing the write cell activity
•	Used variable manipulation, concatenation and the assign activities

## <strong> Contributors </strong>
Max Emsak

## <strong> License </strong>
This project uses the following license: MiT.


