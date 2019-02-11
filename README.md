# donm.dickblick

ReadMe / Setup Instructions / Dependencies for Don Mares Interview Project for Dick Blick

Visual Studio 2017 15.8 with .NET Core 2.1 (SDK) and .NET Framework 4.7.2 was used to create this application

-.NET core cross platform development is required.  

1 - all of the extra credit was done with the exception of b - adding/removing multiple buyers.  Capability is there, just ran out of time to build into the UI.  
2 - db was done with SQL Express and backup is at DonM.DickBlick\DonM.DickBlick.Web\App_Data\DonM.DickBlick.bak
3 - alternatively, can recreate the database using database projects
3a - open solution in visual studio
3b - navigate to DonM.DickBlick.Database
3c - double click / execute DonM.DickBlick.Database.publish.xml and publish database
3d - Edit Connectioon String for correct Data Source.  Username/password should not be changed
4 - update appsettings.json in DonM.DickBlick.Web for correct data source
5 - execute and test project
