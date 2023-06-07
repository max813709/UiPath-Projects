# <strong> Sendpoint Project </strong> #

## <strong> Project Description </strong> ##

An automation based on logging into FIS Global, retrieving a monthly deposit statement 
and a merchant summary statement and downloading both to the local user’s location.

## <strong> Technologies Used </strong> ##

[UiPath Studio 2020.10.7+](https://www.uipath.com/product/studio): Development Environment.

[FIS Global Webpage](https://insight.fisglobal.com/opstopb1/OpstopServlet/Logon): A banking webpage that stores the files we need.

[UiPath Orchestrator](www.cloud.uipath.com/) A component of UiPath that enables the timed trigger for daily report download.

## <strong> Features </strong> ##

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/1e9069c8926d5cab5f017ac92ca19b24541db0a4/Picture1.png">

•	Logs into the FIS Global portal with a secure account/password.
•	Orients using the app recorder to retrieve the Merchant Account Summary Report and a Merchant deposit report in .csv format
•	Downloads both files to the user’s desktop
•	Ends the automation by logging out of the portal
•	Uploaded to orchestrator and set up a weekly trigger
•	Used Github for version control.
![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/1e9069c8926d5cab5f017ac92ca19b24541db0a4/Picture3.png">

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/6ef05568445046edd9a049cbb39eda4595a36ad4/image-1.png">

## <strong> Contributors </strong> ##
Matthew Emsak

## <strong> License </strong>
This project uses the following license: MiT.
