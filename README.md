### _This project is not in a complete or portfolio ready state, and should not be considered representiational of professional work._

# Eau Claire's Salon

### Epicodus Independent Code Review - Database Basics

### By Collin Chapman

## Technologies Used

* Git
* C#
* .NET 5.0
* ASP.NET Core
* Entity Framework Core
* Razor View Engine
* MVC
* RESTful Routing, CRUD & HTTP
* REPL
* MySQL MySQL Workbench
* Bootstrap

## Description

This is a C# MVC web application built for Claire to help her manage her employees (stylists) and their clients.


## Setup/Installation Requirements

* _Requires Visual Studio Code Installation_
* _Requires Terminal Installation_
* _Open the terminal on your local machine_
* _Navigate to the directory inside of which you wish to house this project_
* _Clone this project with the following command  `$ git clone <https://github.com/colchapm/TopRestaurants.Solutions.git>`_
* _Next you will need to download and install .NET Core through this link if you don't already have it: https://dotnet.microsoft.com/download_
* _After downloading and installing .NET Core, return to your terminal and navigate to the root directory by entering "cd TopRestaurants.Solutions"_
* _Then navigate to the desired subdirectory of the repository with the command `$ cd TopRestaurants`_
* _Retrieve and install packages listed in the .csproj files with the command `$ dotnet restore`_
* _In your terminal, log into MySQL by executing the command `$ mysql -u[YOUR-USERNAME] -p[YOUR-PASSWORD]`_


* add instruction here for the user to recreate database and tables


* Navigate to the `TopRestaurants` directory and create an **appsettings.json** file and input the following script:

{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-PROJECT-NAME];uid=root;pwd=[YOUR-PASSWORD];"
  }
}



* _Compile and run the application with the command `$ dotnet run`_

## User Stories 

| Functionalities | 
|:---: |
| As the salon owner, Claire needs to be able to see a list of all sylists | 
| As the salon owner, Claire needs to be able to select a stylist, see their details, and see a list of all clients that belong to that sylist | 
| As the salon owner, Claire needs to be able to add new sylists to the system when they are hired | 
| As the salon owner, Claire needs to be able to add new clients to a specific sylist. She should not be able to add a client if no stylists have been added | 


## Known Bugs


## Link

This project is not hosted on GitHub Pages

## License

Copyright (c) 2021 Collin Chapman

This software is licensed under the MIT license

## Contact Information

cchap14@gmail.com