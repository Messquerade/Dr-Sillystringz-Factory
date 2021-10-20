# Dr. Sillystringz's Factory

A website that tracks the engineers and machines at Dr. Sillystringz's factory.

### By Anna Clarke

## Technologies Used

* _C#_
* _ASP.NET Core MVC_
* _.NET 5_
* _NuGet_
* _Microsoft.EntityFrameworkCore_
* _Dotnet EntityFramework Tool_
* _Microsoft.EntityFrameworkCore.Design_


## Description
This web application will allow the user to see, create, edit, and delete the engineers and machines at Dr. Sillystringz's factory. The user will be able to add engineers that are licensed to repair a specific machine to that machine. Visa Versa, they will be able to add machines that a specific engineer is licensed to repair to that engineer. By clicking on an engineer or machine the user can view all the connected machines or engineers.


### Technology Requirements

* [.NET 5](https://dotnet.microsoft.com/download/dotnet/5.0)
* A text editor like [VS Code](https://code.visualstudio.com/)

## Setup/Installation Requirements

* Clone this repository to your desktop
* Open in text editor
* Create appsettings.json in factoy/Factory/ directory
* Copy this code into appsettings.json, replacing YOUR_PASSWORD with your MySQL password:
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=anna_clarke;uid=root;pwd=YOUR_PASSWORD;"
  }
}
```
* open new terminal and run SQL 

        $ mysql -uroot -p{your_password})
* open MySQL Workbench
* In terminal, navigate into factory/Factory/ and enter this command, to install necessary packages  

        $ dotnet restore
* enter this command to build the program

       $ dotnet build
* enter this command to build your database

        $ dotnet ef database update
* check MySql Workbench to make sure the correct database has built
* enter this command to view this application in your browser 

        $ dotnet run

  

## Known Bugs

* _NA_

## License

_[MIT](https://opensource.org/licenses/MIT)_  

Copyright (c) 2021 Anna Clarke

## Contact Information

Anna Clarke: <anclarkie@gmail.com>