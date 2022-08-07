# Pierre's Bakery - Order Tracker

#### By: Nick Tse

#### This project demonstrates use of the model-view-controller methodology, and basic database usage with MySQL

## Technologies Used

* C#
* MSTest
* .NET 5 SDK
* ASP.NET Core
* Razor
* HTML
* MySQL
* Entity


## Description 

The project is a simple web application that allows the owner of an imaginary hair salon to keep track of their stylists (employees) and their associated clients. The homepage of the app at the root path (localhost:5000/) is a splash page welcoming the user and providing them with a link to a see stylists or clients, following which they may add, edit, or delete stylists and/or clients

## Setup/Installation Requirements

* _Clone repository from GitHub_
* _Open your terminal and run the command $ git clone https://github.com/n-tse/hairSalon_
* _Using the command $ cd HairSalon, navigate to the HairSalon directory_
* _Run the command $ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0_
* _Run the command $ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2_
* _Within the HairSalon project directory, create a file called appsettings.json_
* _Add the following code to the new appsettings.json file: 
  {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=nick_tse;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
    }
  }_
* _Run the command $ dotnet build_
* _Run the command $ dotnet run_
* _In your web browser, type "http://localhost:5000"_
* _The browser should now display the web application for the user to interact with_"

## Known Bugs

* User may attempt to add client prior to adding a stylist the client belongs to, at which point the app will crash

## License

_MIT_

Copyright (c) _2022_ _Nick Tse_