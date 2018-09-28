# ownCloud Server Quickstart Guide
The ownCloud product is free, open-source software that lets you share and synchronize files among your mobile devices and desktop computers in a secure and private manner. You can also share files with others using a common interface.
This quickstart guide helps administrators install and configure the ownCloud server and helps users connect to the ownCloud server. 
## For administrators

### Installing the ownCloud server
For detailed instructions on installing the ownCloud server, refer to the Installation section of the [ownCloud Server Administration Manual](https://doc.ownCloud.org/server/latest/admin_manual/installation/). 
Use the following steps to install the ownCloud server:
1. Check that you meet the [system requirements](https://doc.owncloud.org/server/latest/admin_manual/installation/system_requirements.html).
2. Understand the [deployment recommendations](https://doc.owncloud.org/server/latest/admin_manual/installation/deployment_recommendations.html), some of which depend on the number of users for your environment.
3. 	Install the ownCloud server. You can install the ownCloud server using one of the following methods:
    - [Installing manually on Linux](https://doc.owncloud.org/server/latest/admin_manual/installation/source_installation.html)
    - [Installing using Linux Package Manager](https://doc.owncloud.org/server/latest/admin_manual/installation/linux_installation.html)
    - [Installing using Docker](https://doc.owncloud.org/server/latest/admin_manual/installation/docker/)
    - [Installing using the command line interface](https://doc.owncloud.org/server/latest/admin_manual/installation/command_line_installation.html) 
4. Specify the ownCloud data directory and database using the [installation wizard](https://doc.owncloud.org/server/latest/admin_manual/installation/installation_wizard.html#quick-start).
5. Perform the [post-installation steps.](https://doc.owncloud.org/server/latest/admin_manual/installation/installation_wizard.html#post-installation-steps).
### Configuring the ownCloud server
For detailed instructions on configuring the ownCloud server, refer to the Configuration section of the [ownCloud Server Administration Manual](https://doc.ownCloud.org/server/latest/admin_manual/configuration/)
Use the following steps to configure the ownCloud server:
1. Configure the database, using one of the following methods:
    - [Manually](https://doc.owncloud.org/server/latest/admin_manual/configuration/database/linux_database_configuration.html)
    - Using the [automatic configuration feature](https://doc.owncloud.org/server/latest/admin_manual/configuration/server/automatic_configuration.html)
2. [Enable file sharing and file management.](https://doc.owncloud.org/server/latest/admin_manual/configuration/files/)
3.	Configure [php.ini](https://doc.owncloud.org/server/latest/admin_manual/installation/configuration_notes_and_tips.html#php-ini)  and [PHP-FPM.](https://doc.owncloud.org/server/latest/admin_manual/installation/configuration_notes_and_tips.html#php-fpm) 
4. [Install and manage apps.](https://doc.owncloud.org/server/latest/admin_manual/installation/apps_management_installation.html)

Optionally, you can configure many other features on the server to add security, increase efficiency, and facilitate use. Refer to the Server Configuration section of the [ownCloud Server Administration Manual](https://doc.owncloud.org/server/latest/admin_manual/configuration/server/)
### Enabling users to connect to the ownCloud server using the server’s IP address and port 8080
To enable users to connect to the ownCloud server using the server’s IP address and port 8080, perform the following steps:
1. Access the __LDAP user and group backend application__ from the __Apps__ page in ownCloud.
2. Click the __Server__ tab.
3.	If the __Server__ tab already has values assigned to the fields, click __Delete Configuration__ to remove the active configuration. 
4.	In the __Host__ field, enter the server IP address.
5.	In the __Port__ field, enter the port number on which to connect the LDAP server. If the field is greyed out, click __Detect Port__. The application will look for a standard port and enable you to enter the port number manually.  
6.	If the server requires authentication, you can either enter the User DN and optionally the password in the __User DN__ and __Password__ fields. 
7.	In the __Base DN__ field, enter the base DN if ownCloud does not detect it using the values in the __User DN__ and __Host__ fields.  
8.	Click __Continue__ to provide other configuration details.  When you are finished, click __Test Configuration__. The ownCloud settings binds the settings to the server. 
    -	If the configuration settings are valid, you receive a success message. Click __Save__ to save the settings. 
    -	If the settings are not valid, you receive an error message and logs to help determine the settings you need to change.  
For more information, refer to the User Authentication with LDAP procedure in the [ownCloud Server Administration Manual](https://doc.owncloud.org/server/latest/admin_manual/configuration/server/). 
### Adding a user account
To create a user account, access the __User management__ page of the ownCloud Web UI. Refer to the Creating a new user section of the [ownCloud Server Administration Manual.](https://doc.ownCloud.org/server/latest/admin_manual/configuration/user/user_configuration.html#creating-a-new-user)
## For users
### Connecting to the ownCloud server from the desktop
Once you have installed the ownCloud server and client software, you can connect to the server using the following steps: 
1.	Click the ownCloud __Desktop Client__ icon.  
2.	From the ownCloud __connection__ screen, enter the ownCloud server URL.
3.	Enter login credentials.
4.	From the __Enter the Local Folder Option__ screen, specify whether you want to synchronize all files or some files on the ownCloud server.
5.	Click __Connect__.
The ownCloud server connects and opens your ownCloud Web GUI.
For more information on using the desktop client, see the [ownCloud Desktop Client Manual.](https://doc.owncloud.org/desktop/latest/)
### Connecting to the ownCloud server from an Android device
Once you have installed the ownCloud server and app, you can connect to the ownCloud server from an Android device, using the following steps:
1.	Open the ownCloud app.
2.	Enter the ownCloud server URL and login credentials. 
3.	Click __connect__. 
4.	If your server has a self-signed SSL certificate, a warning message explains that the certificate is not trusted. Click __Yes__ to accept the certificate.
The ownCloud server connects and opens to your __All Files__ page.
For more information about accessing the ownCloud server from an Android device, refer to the [ownCloud Android App Manual.](https://doc.owncloud.org/android/)
### Connecting to the ownCloud server from an IOS device
Once you have installed the ownCloud server and app, you can connect to the ownCloud server from an IOS device, using the following steps:
1.	Open the ownCloud app.
2.	Enter the ownCloud server URL and login credentials. 
3.	Click __connect__. 
The ownCloud server connects and opens to  __your Files__ page.
For more information about accessing the ownCloud server from IOS, refer to the [ownCloud iOS App Manual.](https://doc.owncloud.org/ios/) 

