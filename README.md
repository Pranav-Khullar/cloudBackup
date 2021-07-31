# cloudBackup
1. Google cloud api has been used for backing up files to google cloud.
2. My drive class has been created which contains the functions for google 
drive.
3. These functions request for authentication token using oauth2 method to 
access the rights for accessing the drive.
4. The function for checking the drive content (list_files) from google drive
api documentation.
5. A function (upload_files) is created for uploading files to the cloud. This 
function first compares the contents of the folder to be backed up and the 
content of cloud. If new files are present this file is uploaded.
6. Logging module is used to create a file which stores the logs.
7. Schedule module is used to schedule the code to run after a fixed time.
