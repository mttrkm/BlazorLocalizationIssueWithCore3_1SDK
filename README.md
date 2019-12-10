# BlazorLocalizationIssueWithCore3_1SDK
This project is minimum localization sample. It is usable to reproduce Blazor server localization issue in Visual Studio 16.4 + .NET Core 3.1 SDK.

Localization works with Visual Studio 16.3.10 + .NET Core 3.0 SDK.  
But that does not work in upgrading Visual Studio 16.4 + .NET Core 3.1 SDK.
 

This project was created in the following way.
1. Create new blazor server project in Visual Studio 2019.
1. Add some code in Startup.cs
1. Add some code in _Host.cshtml
1. Add some code in Index.razor
1. Add a file of SharedResource.cs
1. Add a file of SharedResource.en.resx
