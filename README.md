# DnnMehdiNikkhah
This web application is generated as part of my homework for  DnnCorporation. 
 I used MVC, Web API, EntityFramework codefirst migration, AutoMapper, DTO, Unity, Bootbox, Jquery in this project.
 I used Repository Pattern, Inversion Injection (Dependency Injection) pattern in this code.
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
### Prerequisites
The following application is requiered to run the application and debug and edit it.
1. IIS7
2. SqlServer 2008 or later.
3. Visual Studio 205 or later.
### Running
This Approach is for running the web application on your local visual studio in the debug mode.
1. download all files. Create a folder Name DnnMehdiNikkhah01 in C drive. copy all files in the created folder. unzip all files.
2. open the web.config with any text editor. the file is in the DnnMehdiNikkhah01/DnnMehdiNikkhah01/ path.
3. In the configuration tag, set the existing connectionString tags as follows or add a new one.
   
   < add name="DnnMehdiNikkhah" connectionString="Integrated Security=true;Persist Security Info=False;Initial Catalog=DnnMehdiNikkhah;Data Source=.\sqlexpress" providerName="System.Data.SqlClient" /> 
   
   
 the above connection string is for connecting in Windows Authentication mode. SET the DataSource by the name of your SQLServer Name:
 
     Data Source="myServerName\myInstanceName" ex. .\sqlexpress
     
  If you want to connect to in Mixed mode the connection string should be as follows:

    < add name="DnnMehdiNikkhah" connectionString="Persist Security Info=False;User ID=sa;Initial Catalog=DnnMehdiNikkhah;  Password="Your Paassword" Data Source=.\sqlexpress" providerName="System.Data.SqlClient" />
    
4. Now Open Visual Studio as Administrator. 
5. From File Menu select open existing project and select DnnMehdiNikkhah01.Sln in hte main folder of our project.
6. Build project in Debug mode.
7. Build Project in Release mode.
8. Run project in Debug mode.

   Enjoy it.
  
