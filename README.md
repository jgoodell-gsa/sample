# REPO NAME 

## Description: 
A description of your project follows. A good description is clear, short, and to the point. Describe the importance of your project, and what it does.

## Table of contents
Table of Contents: Optionally, include a table of contents in order to allow other people to quickly navigate especially long or detailed READMEs.
1. section 1
2. section 2
3. section 3 ect.

## Installation
Installation: Installation is the next section in an effective README. Tell other users how to install your project locally. Optionally, include a gif to make the process even more clear for other people.



## Default config setup

The repository contains a web config that points to external config files. These external config files not controlled by version control will need to be created and configured prior to running the application. The files required and the default configuration can be found below. For those on the development team, additional details can be found in the documentation on the google drive in the GIT team drive.

* **Current config files that will need to be added.**
  * DB.config    **Name might be altered**
  * AppSettings.config  **Name might be altered**
 
* **Default settings for these files will follow this line**
 
   * **DB.config file should contain the following lines.** 
    ~~~ xml
    <connectionStrings>
      <add name="GCIMS" connectionString="server=server ip; port=port number; user id=username; password=password;persist security info=True;database=databasename; pooling=true;" />
    </connectionStrings>
    ~~~

   * **AppSettings.config should contain the following lines.**
  ~~~ xml
  <appSettings>
    <add key="DEBUGMODE" value="false" />
    <add key="VERSION" value="V1" />
    <add key="SMTPSERVER" value="smtp mail server" />
    <add key="DEFAULTSUBJECT" value="Automated CIW Process" />
    <add key="SUMMARYEMAIL" value="email address" />
    <add key="DEFAULTEMAIL" value="email address" />
    <add key="ONBOARDINGLOCATION" value="onboarding folder path" />
    <add key="EMAILTEMPLATESLOCATION" value="email template folder path" />
    <add key="CIWPRODUCTIONFILELOCATION" value="folder path for production files" />
    <add key="CIWDEBUGFILELOCATION" value="folder path for debug files" />
    <add key="FASEMAIL" value="email address" />
    <add key="CHILDCAREEMAIL" value="email address" />
    <add key="TEMPFOLDER" value="folder path for temp csv files" />
    <add key="Salt" value="salt" />
    <add key="EPass" value="epass" />
    <add key="ClientSettingsProvider.ServiceUri" value="" />
  </appSettings>
  ~~~
  
  
  ***
  
  Part 2
