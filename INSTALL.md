# TaskerMAN and TaskerCLI Installation Instructions 

## TaskerMAN

Installing TaskerMAN is a fairly simple process. First you need to clone the git respository into a directory which is accessible by your webserver. This can be done using the following command:

`git clone https://github.com/aber-cs22120-group-15/TaskerMAN.git`

Then you need to copy `config/config.php.tmp` to `config/config.php` and edit in your MySQL connection details. 

Once this is done, you can open a web browser and browse to the path in which you placed the code. This will then cause the installer to display where you can create a first administrative user. Once that is done, the application is installed!


## TaskerCLI

Prerequisites include the Java 8 Runtime Environment to be installed before running TaskerCLI. Once installed the TaskerCLI.jar can be downloaded from the TaskerCLI repository located at:

`https://github.com/aber-cs22120-group-15/TaskerCLI`

Once downloaded, double-click on the file, or right-click, open-with and select Java from the list.

To change the URL for where the server is accessed the source must be edited. The URL can be found in the following class:

`uk.ac.aber.cs221.group15.service.Service`

Simply change the value for the field named URL_BASE to the desired url.
