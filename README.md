## dotnet core application
A basic dotnet core application setup

### Commands
```ps1
dotnet new sln --name dotnet # create solution
dotnet new webapi -lang "C#" -o WebApi # create webapi project
dotnet new classlib -lang "C#" -o Application # create project for class files

dotnet sln .\dotnet.sln add .\WebApi\WebApi.csproj # add project to solution
```