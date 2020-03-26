# Custom authentication local installation  

Following steps need to be followed

* Download the files from the github location https://github.com/executive-office-of-education/EOEDemos.git
* Make sure the report server is stopped.
* Copy the files from EOEDemos\pbirs\reportserverfiles\dll to the following locations
    <PBIRS Installation>/ReportServer/bin
    <PBIRS Installation>/PowerBI
    <PBIRS Installation>/Portal
* Copy the files logon.aspx and the config files from EOEDemos\pbirs\reportserverfiles to the report location <PBIRS Installation>/ReportServer
* Restart the report server

# Custom authentication Usage

* Open browser
* http://<reportlocation>/logon.aspx
* First register testuser with 'test' as password. For now all the users should have the password as 'test'
* Enter user name and password and click on logon 
* Now you are ready to the use the report server