# Flask-based-Meeting-viewer-app-
Note : this is sample application, for production it is recommended to use web server WSGI.
GUI based application to view the meetings and its settings using Graph API

This is python Flask based script using MS Graph API to retrieve the outlook calandar events. 
We are going to use Microsoft Graph API to fetch the data from tenant. (Please check Graph API endpoint and various url's) 
This  application pulls the calendar meetings details froms specific organization supplied in textbox. 
You can view the meeting details , This is helpful to view meetings of individuals as well as from resource mailbox accounts. 
It provides all require information associated with this meeting, Subject, date/time, Join Link, Organizer name and numberic meeting ID.


Please follow below steps to test this application.

Step 1 - create and register application in Azure AD. 
Step 2 -Note down the client ID, secret and Tenant ID to input it in code. 
Step 3 - open main python script and add client ID, secret and Tenanat ID details. 
step 4 - create folder with name templates  and save the HTML files in it, folder name should templates only or else application will not be able to read the HTML files.
Step 5 - Your application is ready to go, run the code which will present web GUI to input organizer email, date and time. 
Step 5 - click on fetch, once result populated , you can view and delete the event.
ste 6 - you can select the evnts and click export at the bottom to download the data in csv
