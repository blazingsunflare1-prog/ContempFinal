# Rest API ASP.NET Core .NET 8
============================
This project by Rohit Vijai and Jack Baker. serves as a backend server for storing data and data management for a dev team's personal information.





General
============================
Applications of any kind are able to send HTTP requests to this API to interact with data stored in the database. This API is documented and testable through a built in Swagger UI accessed directly in the browser when the project is active.



Tables
============================
The API manages these separate database tables and their entitys:
Team Members - Full name, birthdate, college program, year in program, email



Hobbies - Hobby name, category, description, skill level, equipment required (yes/no)



Breakfast Foods - Food name, cuisine type, calories, vegetarian status, preparation time

Movies - Title, genre, release year, director, rating



Testing Capabilities
============================
This project includes a separate rest project called TeamProjectAPI.Tests with 32 automated tests (8 per controller). The tests cover every CRUD operation using an in-memory database.



Version Details
============================
The codebase is version controlled using Git and hosted on GitHub at github.com/Vijairt/ContempFinal. The project was built using ASP.NET Core .NET 8, Entity Framework Core 8, SQL Server LocalDB, NSwag for Swagger UI, and xUnit for unit testing.
