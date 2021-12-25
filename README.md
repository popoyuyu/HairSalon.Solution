# _Eau Claire's Salon_

#### By _**Jeff Lai**_

#### _This web application uses C#, MySQL database and Entity to store list of stylists and their clients_

## Technologies Used

* _C#_
* _.NET 5.0_
* _MySQL Workbench_
* _Entity_

## Description

_This application lets the user create stylists and add clients to those stylists._

## Setup/Installation Requirements

* _Clone this repository or download zip file from "https://github.com/popoyuyu/HairSalon.Solution.git"._
* _In HairSalon run $ dotnet restore in terminal to get required dependencies._
* _Open file in code editor of your choice._
* _Add file "appsettings.json" to HairSalon directory._
* _In appsettings.json enter: 
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=jeff_lai;uid=[YOUR-UID];pwd=[YOUR-PASSWORD-HERE];"
  }
}_
* _Enter your own MySQL database user ID and password_
* _In your MySQL Workbench navigate to Administration under Management Tab_
* _Select Data Import/Restore option_
* _Select Import from Self-Contained File then navigate to root directory for this file_
* _Select jeff_lai.sql from this directory_
* _Start the import_
* _Back in your terminal run $ dotnet watch build in HairSalon to watch for live changes_


## Known Bugs

* _No known bugs_

## License

_Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:_

_The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software._

_THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE._


Copyright (c) _December 24th 2021_ _Jeff Lai_