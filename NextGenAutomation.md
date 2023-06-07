# <strong> Next Gen Automation </strong> #

## <strong> Project Description </strong> ##

Automation to construct an automation robot that establishes foundations (P1) project boards for new Next Gen cohorts on Trello.
Technologies Used
•	Tech 1 - Trello API
•	Tech 2 - UiPath Studio 2020.10.7
•	Tech 3 - Orchestrator 22.4.1

## <strong> Features </strong>

List of features ready and TODOs for future development
•	Consume data to create Next Gen Trello project boards for new associate cohorts.
•	Create a new list on the project board for each associate in the cohort with week 1 requirements upon initialization.
•	Add the weekly requirements at specific timeframes through Orchestrator triggers.

### <strong> To-do list: </strong>
•	Construct an automation robot that can distribute relevant information to cohort trainers and managers when a training phase begins and ends.
•	Set dates for the beginning and end of each training phase.
•	Request pdf exit evaluation reports from the QC analyst at the end of each phase.
•	Send automated emails to trainers at the beginning and end of each training phase.

### <strong> Setting Up Orchestrator and Accounts </strong>
1.	In Orchestrator, create a queue to contain the transaction items for the automation.
2.	Create assets and assign its file path in the value section.
3.	Create a Trello account that will have access to the workspace containing the Project 1 boards and generate an API key and token.
4.	Add the API key and token as text assets in Orchestrator.
Setting Up Automations
1.	Clone project repository using https://github.com/Revature-Capstone-1362/run-at-risk-assessment.git.
2.	Open project.json in both AtRiskAssessmentDispatcher and AtRiskAssessmentPerformer folders and publish the projects to Orchestrator.
3.	Assign processes to robots.
4.	Navigate to package directory on robot machines, usually located in %userprofile%.nuget\packages.
5.	Open config.xlsx in 1.x.x\lib\net45\Data directory of dispatcher and set the queue name.
6.	Optionally set the path to the directory for input data workbooks. The default directory for input data is the Input folder in this directory.

## Contributors ##
•	Thomas Vo
•	Zaur Yusupov
•	Esther Parson
•	Jonathan Barajas
•	Ying Fan
•	Trianna Nunes
•	Sylvester Gold
•	Matthew Emsak

