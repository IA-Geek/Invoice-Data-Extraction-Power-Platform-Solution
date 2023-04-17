# Invoice Data Extraction Solution using Power Platform 
An unmanage solution built using Power Platform components that will extract data from Invoice PDF Document coming from a new email received with a specific subject line condition. The extracted data will be saved in an Excel worksheet and a SharePoint List.

**Solution Component**
1. AI Builder - AI Model trained to extract PDF from an Invoice document.
2. Power Automate Cloud Flow - Automated cloud flow that will be triggered once a new email was received which contains specific phrase in Subject Line.
3. Power Automate Cloud Flow - Triggered once a new file was added to the SharePoint Library then extract the invoice data and save them to an excel spreadsheet
4. Power Automate Cloud Flow - Triggered once a new file was added to the SharePoint Library then extract the invoice data and save them to an excel spreadsheet and SharePoint List
5. Power Automate Cloud Flow - Scheduled flow that will move Excel rows to SharePoint List
6. Power Automate Cloud Flow - Triggered once a new email arrived with configured condition then will export the email and save it to a SharePoint folder

#Power-Platform-Projects
