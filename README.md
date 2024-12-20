# Hair Salon

#### _A website designed for a hair salon manager._

#### By _**India Lyon-Myrick**_

## Technologies Used

* _C#_
* _.NET_
* _MySQL_
* _Git_

## Description

_A website for managing a fictional hair salon. The website features a landing page leading to a list of the salon's hair stylists. After adding a stylist, the user can view listings for stylists and their clients. Both stylists and clients have individual listing pages with functionality to view an individual stylists or client, edit, or delete them._

## Setup/Installation Requirements

* _You will need [.NET](https://dotnet.microsoft.com/en-us/download/dotnet/6.0), [MySQL](https://downloads.mysql.com/archives/get/p/25/file/mysql-installer-web-community-8.0.19.0.msi), and [Git](https://git-scm.com/downloads/) in order to run the program._

_1: Clone the repository to a folder of choice on your machine (by either using the "Code" button on the GitHub page, or in a terminal application using `git clone https://github.com/igl-myrick/HairSalon.Solution`)._

_2: Using a terminal application such as Git Bash or Windows Command Prompt, navigate to the top level of the program folder, then into the `HairSalon` folder._

_3: You will need to create an `appsettings.json` file within the `HairSalon` folder, including the following code:_

```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=india_lyon-myrick;uid=[YOUR-USER-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```

_Insert your own MySQL username in place of `[YOUR-USER-HERE]` and MySQL password in place of `[YOUR-PASSWORD-HERE]`._

_4: In MySQL Workbench, open the Administration tab and select "Data Import". Select the "Import from Self-Contained File" option and navigate to the .sql database file in the `HairSalon.Solution` folder in the file select screen. Click on the "New" button in the "Default Schema to be Imported To" section. Enter the name of the database file. Finally, click "Start Import" to import the database into MySQL Workbench._

_5: Next, run `dotnet build` in the command line to build the program._

_6: Once the program is built, run `dotnet run` to start the program._

_7: When the program is running, navigate to `https://localhost:5001` to view and use the website._

## Known Bugs

* _None at the moment_

## License

MIT:

Copyright (c) _11/27/2024_ _India Lyon-Myrick_

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.