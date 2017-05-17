# DnnMehdiNikkhah
This web application is generated as part of my homework for  DnnCorporation. 
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
### Prerequisites
The following application is requiered to run the application and debug and edit it.
1. IIS7
2. SqlServer 2008 or later.
3. Visual Studio 205 or later.
### Running
This Approach is for running the web application on your local visual studio in the debug mode.
1. download and unzip the projects file (DnnMehdiNikkhah01.zip)
2. Set the connection string:
 a. open the web.config in DnnMehdiNikkhah01/DnnMehdiNikkhah01/ path.
 b. in the configuration tag set the existing connectionString tags as follows or add a new one.
  <connectionStrings>
    <add name="DnnMehdiNikkhah" connectionString="Integrated Security=true;Persist Security Info=False;Initial Catalog=DnnMehdiNikkhah;Data Source=.\sqlexpress" providerName="System.Data.SqlClient" />
  </connectionStrings>
 c. the above connection string is for connecting in Windows Authentication mode. SET the DataSource by the name of your SQLServer Name:
     Data Source="myServerName\myInstanceName" ex. .\sqlexpress
 d. If you want to connect to in Mixed mode the connection string should be as follows:

    <add name="DnnMehdiNikkhah" connectionString="Persist Security Info=False;User ID=sa;Initial Catalog=DnnMehdiNikkhah;  Password="Your Paassword" Data Source=.\sqlexpress" providerName="System.Data.SqlClient" />
  
