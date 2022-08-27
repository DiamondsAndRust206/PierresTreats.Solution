# Pierre's Treats

#### By Ryan Gibson

#### This is a web app that creates treats and flavors which you can assign one to the other.

## Technologies Used

* C#
* HTML
* CSS
* MySQL Workbench
* ASP.NET
* Entity Framework
* REPL
* Razor

## Description

 This webpage was programmed using C#, ASP.NET & Entity. It is a bakery management site that allows the user to add treats and flavors. This is done using the SQL Workbench for the database, and using three tables to utilize a many-to-many relationship. The user can add multiple flavors to treats that they want, they can also add many treats to flavors. The user can click on each treat or flavor to see details, edit the information, create a new one, or delete an exsiting one.

## Setup/Installation

* At https://github.com/DiamondsAndRust206/PierresTreats.Solution.git copy the git repository URL from the green "code" button.
* Open a shell program & navigate to your desktop
* Clone the repository using the copied URL and the "git clone" command
* In the shell program, navigate to the root directory of the newly created file called "PierresTreats.Solution"
* From the root directory, navigate to the directory named "PierresTreats" and type "dotnet restore".
* Type "dotnet build" : this will help you to have all the technologies you need to run you test.
* In the Factory directory create a file named "appsettings.json"
* Add the following code to the newly created .json file
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=pierres_treats;uid=root;pwd=[YOUR-PASSWORD];"
  }
}
```
* Before commit and pushing to your remote repo make sure to add the "appsettings.json" file to your .gitignore file because it contains sensitive information.
* Open Your MySql workbench and navigate to Administrator
* Select DataImport /Restore
* Navigate to the Project Directory
* Imoprt the file name ryan_gibson.sql
* In the Factory directory type "dotnet run" to start the program
* Open a web browser and plug "http://localhost:5000/" into the URL bar

## Known Bugs

* No known issues

## License

[MIT](LICENSE)

Copyright (c) 2022 Timothy R Gibson