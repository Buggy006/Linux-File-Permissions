# Linux-File-Permissions
System Administrator - Tasks

#### There are new requirements to automate a backup process that was performed manually by the xFusionCorp Industries system admins team earlier. To automate this task, the team has developed a new bash script xfusioncorp.sh. They have already copied the script on all required servers, however they did not make it executable on one the app server i.e App Server 3 in Stratos Datacenter.

#### Please give executable permissions to /tmp/xfusioncorp.sh script on App Server 3. Also make sure every user can execute it.

`ssh banner@stapp03`



` sudo su - `


`ls-ltr /tmp/xfusioncorp.sh`   to check the file permissions


`chmod o+rx /tmp/xfusioncorp`    to change the file permissions to others as read and execute



### Exit from root user.



`sh /tmp/xfusioncorp.sh`        validate the task.
