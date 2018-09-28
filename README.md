# ownCloud Server Quickstart Guide
The ownCloud product is free, open-source software that lets you share and synchronize files among your mobile devices and desktop computers in a secure and private manner. You can also share files with others using a common interface.
This quickstart guide helps administrators install and configure the ownCloud server and helps users connect to the ownCloud server. 
## For Administrators

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
5. Perform the [post-installation steps.](https://doc.owncloud.org/server/latest/admin_manual/installation/installation_wizard.html#post-installation-steps)
### Configuring the ownCloud server
For detailed instructions on configuring the ownCloud server, refer to the Configuration section of the [ownCloud Server Administration Manual](https://doc.ownCloud.org/server/latest/admin_manual/configuration/)
Use the following steps to configure the ownCloud server:
1. Configure the database, using one of the following methods:
- [Manually](https://doc.owncloud.org/server/latest/admin_manual/configuration/database/linux_database_configuration.html)
- Using the [automatic configuration feature](https://doc.owncloud.org/server/latest/admin_manual/configuration/server/automatic_configuration.html)
2. [Enable file sharing and file management.](https://doc.owncloud.org/server/latest/admin_manual/configuration/files/)
3.	Configure [php.ini](https://doc.owncloud.org/server/latest/admin_manual/installation/configuration_notes_and_tips.html#php-ini)  and [PHP-FPM.](https://doc.owncloud.org/server/latest/admin_manual/installation/configuration_notes_and_tips.html#php-fpm) 
4. [Install and manage apps.](https://doc.owncloud.org/server/latest/admin_manual/installation/apps_management_installation.html)
Optionally, you can configure many other features on the server to add security, increase efficiency, and facilitate use. Refer to the Server Configuration section of the [ownCloud Server Administration Manual.] (https://doc.owncloud.org/server/latest/admin_manual/configuration/server/)
