# developer-interview-exercise-dotnet472
Developer interview exercise solution in .NET 472

Solution in this repository is created using the existing solution in .NET 461 (https://github.com/chaurasia-amarjeet/developer-interview-exercise-dotnet461)

We have upgraded the existing project to .NET 472 and then replace console logging with Serilog with file sink.

To upgrade project from .NET 461 to .NET 472 follow below steps.

1. Right click on project. Click on Properties. Under Application tab change the Target framework to .NET 472. Repeat this for each project in solution.

2. Run the below command in package manager console to target packages to new target framework.
   Update-Package -Reinstall -IgnoreDependencies
   
For integrating Serilog with your application you can refer https://github.com/serilog/serilog/wiki
