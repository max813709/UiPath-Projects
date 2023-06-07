# <strong> Nymbus </strong> #

An automated method of logging into IBS Insight, recording several balances throughout the day, listing them on an excel spreadsheet and forwarding them to the user.

## <strong> Technologies Used </strong> ##

[UiPath Studio 2020.10.7+](https://www.uipath.com/product/studio): Development Environment.

[IBS Insight](https://insight.fisglobal.com/opstopb1/OpstopServlet/Logon): A webpage that holds customer banking info.

[UiPath Orchestrator](www.cloud.uipath.com/): A functionality that enables the timed trigger for stock price recording.

[Microsoft Excel]: Used to store customer information.

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/6ef05568445046edd9a049cbb39eda4595a36ad4/Picture2.png">

## <strong> Features </strong> ##

•	Logged into IBS insight
•	Used the readcell activity to record account numbers and a deposit listing for each customer
•	Used Item.replace and assign activities to format variables
•	Logged details of automation for consistency
•	Used variable manipulation, type into and click activities to navigate to screen scraped pages
•	Screen scraped and used get text activities as well as if statements and write cell activities

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/3ca8c45c98dd94236520d8dcaded3765c86c1014/image-3.png">

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/3ca8c45c98dd94236520d8dcaded3765c86c1014/image-4.png">
  
## <strong> Contributors </strong>
Matthew Emsak

## <strong> License </strong>
This project uses the following license: MiT.

