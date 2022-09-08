# CMPG-323-Project-2

<h1>CMPG-323 Project2</h1>

<h2>Main Project Implementations & Processes</h2>
•	Create a local SQL database through SSMS
•	Create a new .NET Core Web API project
•	Scaffolded DBContext (ApplicationDbContext) into the project
•	Completed the dependency injection for the scaffolded DBContext to the Startup.cs
•	Created the following methods to all the main tables (Categories, Devices, Zones)
o	GET
o	POST
o	PATCH
o	DELETE

<h2>Project security implementations</h2>
•	Authentication has been set up, user can access the categories table and admin the devices and zone tables

<h2>GetHub Implementations</h2>
•	Created a 2nd repository (CMPG-323-Project-2-33361908)
•	Created a ReadME.md file for documentation
•	Source Control has been committed
•	After each major success in the project progress, a pr has been created to GetHub to keep the master repository up-to-date with the lates version.

<h2>Azure Implementations</h2>
•	Create a secure F1 SQL database that was linked to SSMS with secure authentication (username / password)
•	Connected the Azure SQL database to SSMS and create the table using the crip provided
•	Create and API to host the API with firewall security
•	Published application to the Azure API hosting


<h2>How to Use the API</h2>
Connect to the application hosted at: https://grwebapi-masterproject.azurewebsites.net/swagger/index.html 
Create a new user with the (POST api/Authenticate/register “for Users” OR POST api/Authenticate/register-admin “for Admin)
Log into the API with (POST api/Authenticate/login)
Once access has been granted the user / admin can access the tables to GET / POST / PUL or DELETE the database entries for the following tables:
•	Categories – User access
•	Devices – Admin access
•	Zones – Admin access

<h2>Reference List:</h2>

•	Tutorial: Create a web API with ASP.NET Core | Microsoft Docs: https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-6.0&tabs=visual-studio
•	Create a web API with ASP.NET Core controllers - Learn | Microsoft Docs: https://docs.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/
•	ASP.NET Core web API documentation with Swagger / OpenAPI | Microsoft Docs: https://docs.microsoft.com/en-us/aspnet/core/tutorials/web-api-help-pages-using-swagger?view=aspnetcore-3.1
•	Create microservices with .NET and ASP.NET Core - Learn | Microsoft Docs: https://docs.microsoft.com/en-us/training/paths/create-microservices-with-dotnet/
•	Entity Framework Core 3.1 - Getting Started: https://procodeguide.com/programming/entity-framework-core-in-asp-net-core/
•	Join two entities in .NET Core, using lambda and Entity Framework Core: https://jd-bots.com/2022/01/24/join-two-entities-in-net-core-using-lambda-and-entity-framework-core/
•	Publish an ASP.NET Core web API to Azure API Management with Visual Studio | Microsoft Docs: https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-api-management-using-vs?view=aspnetcore-6.0
•	Interesting read: Automating ASP.NET Core Web API Creation That Communicates with Your Database in 60 Seconds or Less: https://thejpanda.com/2020/08/10/python-automating-asp-net-core-web-api-creation-that-communicates-with-your-database-in-60-seconds-or-less/
•	Introduction to JSON Web Tokens: https://jwt.io/introduction/
•	Install SQL Server & SSMS: https://www.tutorialsteacher.com/sqlserver/install-sql-server
•	
