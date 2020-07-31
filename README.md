# _Hair Salon_

#### _Application to track Hair Salon Clients, 7/31/2020_

#### By _**Joseph Pearce**_

## Description

This application will allow a Hair Salon Owner the ability to add a list of stylists working at the salon, and for each stylist, add their respective clients. Once added the stylists and clients can be edited and deleted.  

## Specs

| Spec                                                                              | Input                                                          | Output                                      |
| :-------------------------------------------------------------------------------- | :------------------------------------------------------------- | :------------------------------------------ |
| 1. Program will create a Stylist object with name | "Helen" | "Helen"  |
| 2. Program will assign a unique id to each stylist | "Helen" | Id: 1  |
| 3. Program will allow users to add client object to the Stylist List | "Ms Jones" | "Ms Jones" |
| 4. Program will allow users to edit stylist object in the Stylist List | "Ms Jones" |          |
| 5. Program will allow users to delete stylist object in the Stylist List | "Ms Jones" |  |
| 6. Program will allow users to edit client object in the Client List | "Ms Jones" |          |
| 7. Program will allow users to delete client object in the Client List | "Ms Jones" |  |
| 8. Program will provide navigation links to add, view, edit and delete Stylists |  |  |
| 9. Program will provide navigation links to add, view, edit and delete Clients |  |  |



## Setup/Installation Requirements

- _Clone or download this repository located at https://github.com/pearcy/HairSalon.Solution.git
- _Open the downloaded directory in a text editor of your choice. (VSCode, Atom, etc.)
- _Run \$ dotnet restore to download all dev dependencies_ Ensure that dotnet restore is targeting the directory containing the .csproj file

Importing the database schema
- _Use MySQL Workbench to create the database for the project by importing the "Joseph_Pearce.sql" file (it's included in the repo).
- _In the Navigator > Administration window, select Data Import/Restore.
- _In Import Options select Import from Self-Contained File.
- _Save the "Joseph_Pearce.sql" file to your local machine.
- _Navigate to the "Joseph_Pearce.sql" file.
- _Under Default Schema to be Imported To, select the New button.
- _ Enter the name of your database.
- _In this case joseph_pearce.
- _Click Ok.
- _Click Start Import.
- _Reopen the Navigator > Schemas tab. Right click and select Refresh All. Our new test database will appear

- _Run \$ dotnet build to create project_
- _Run \$ dotnet run in the command line to start the program


## Known Bugs

_No known bugs_

## Support and contact details

_Please contact us with any known bugs or support issues._

## Technologies Used

- _C#_
- _.NET Core 2.2_
- VS Code
- MySQL Database
- MySQL Workbench
- Entity Framework
- _Git_

### License

*Copyright (c) 2020 **_Joseph Pearce_**