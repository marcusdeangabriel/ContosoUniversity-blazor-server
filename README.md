# Contoso University Blazor Server, no WebAssembly (WASM).

Contoso University is a sample application that demonstrates how to
use the Entity Framework Core in an ASP.NET Core Blazor server web
application, no WebAssembly (WASM).  See the
[Blazor Contoso University project source code](https://github.com/marcusdeangabriel/ContosoUniversity-blazor-server)
at GitHub.

The Blazor Contoso University application is a sample derived from the
Razor Pages Contoso University
[tutorials](https://docs.microsoft.com/aspnet/core/data/ef-rp/intro)
You can download the completed
[Razor Pages Contoso University project source code](https://github.com/dotnet/AspNetCore.Docs/tree/main/aspnetcore/data/ef-rp/intro/samples/cu)
at GitHub.  It is highly recommeneded that one works through the
Razor Pages Contoso University
[tutorials](https://docs.microsoft.com/aspnet/core/data/ef-rp/intro)
first before reading the code in this sample.


Read the
[ASP.NET Core Blazor Server with Entity Framework Core](https://learn.microsoft.com/en-us/aspnet/core/blazor/blazor-server-ef-core?view=aspnetcore-7.0)
for an introducttion to a more complex example than the one here.  See
the
[Blazor Server EF Core sample project source code](https://github.com/dotnet/blazor-samples/tree/main/7.0/BlazorServerEFCoreSample)
at GitHub.

## To Run

Open the solution in Visual Studio 2022, open the Package Manager, and
run

    PM> Drop-Database

and then

    PM> Update-Database

When ready, press F5 and read the home page information.
