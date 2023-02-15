# SAP-SPA-Error
Error to replicate the issue with Optional fields with Process Automation

Import the Mtar file in SAp Process Automation Lobby. This will give the complete Project Artifacts
Modify the project settings, Agent Settings as per your Agent set up
Release & Deploy - 
Run the Process, by trigerring the Start Form using the link
Enter First name, And Age - as these are mandatory values
Leave the optional fields

Once you submit, this will start the process. Go to Process Monitor - Check the status of your process
it will fail since the Automation Artifact is expecting the optional fields as well

![image](https://user-images.githubusercontent.com/5169927/218984089-9a1b5671-ee58-455a-9cc1-3fb01e2260a9.png)

