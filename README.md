# Class-Library-Projects
1.dotnet new sln
2.dotnet new classlib -o StringLibrary
3.dotnet sln add StringLibrary/StringLibrary.csproj
4.dotnet build
5.dotnet new console -o ShowCase
6.dotnet sln add ShowCase/ShowCase.csproj
7.dotnet add ShowCase/ShowCase.csproj reference StringLibrary/StringLibrary.csproj
8.dotnet run --project ShowCase/ShowCase.csproj
