## ZOHO TICKET GENERATION.
Help desk agents get inputs from a variety of channels, including phone, email, and spreadsheets, to create and update support tickets. Support tickets are the requests that you raise by calling help desk agents to get your issues resolved; for example, your laptop is not working, or you have internet issues.

For this project, we will be covering the automation of inputting tickets from spreadsheets that a requester places in a certain folder. We are assuming a very simple use case of ticket creation for this first project. All you have to do in this project is to input support ticket data in a spreadsheet and place it in a folder. The bot, once invoked, automatically creates a support ticket within the help desk system for you.

This Project helps one to understand below.
## 1.Attended RPA concepts
## 2.UiPath Excel automation
## 3.UiPath automation for web-based apps
## 4.Creating automation workflows and invoking them
## 5.Using Try and Catch for exceptions


## Technical requirements
The hardware and software that will be required for this project are as follows:

## A PC with UiPath Community edition version 19+ installed (we covered the hardware relating to installation in Chapter 1, 
## Getting Started with RPA).
## A Chrome browser with a UiPath add-on.
## A Zoho Desk SaaS application. You can sign up for free at https://desk.zoho.com.
## Microsoft Excel 2007 and later.
## Check out the following video to see the Code in Action: https://bit.ly/36gX89C.
## You can find the code files present in this chapter on GitHub at https://github.com/PacktPublishing/Robotic-Process-Automation- 
## Projects/tree/master/HelpdeskAgentAttendedAutomation.

 
## Project overview
We will automate the creation of help desk tickets using data from an Excel sheet. 

In this project, once the bot is invoked, it will check whether there are new request files available to process. If available, the bot will read the ticket data from this spreadsheet. The data is then used to create support tickets in the Zoho Desk application.
