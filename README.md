# ![beavernet](beaverNet.InMemoryWebApp/wwwroot/img/beaverNetLogo39px.png) beaverNet

# In-Memory Identity web application
This is an implementation of ASP.NET Core 3.1 web application with MVC architecture using Entity Framework Core in memory database for default user identity.
**No database** engine needed! The app flush data once it stops execution.

## Run this app
Command Line instructions 
1. Clone this repository:
````
git clone https://github.com/JulioMelchorPinto/beaverNet.InMemoryWebApp.git
````
2. Enter directory
````
cd beaverNet.InMemoryWebApp/
````
3. Run with dotnet command
````
dotnet run --project beaverNet.InMemoryWebApp/beaverNet.InMemoryWebApp.csproj --launch-profile beaverNet.InMemoryWebApp
````
