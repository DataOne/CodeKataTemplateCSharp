# C# Solution Template for running Code Katas
This template can be used to run Code Katas based on C#. The suggestion is, to clone this one for every session separately and to track the different solution (if there is more than one solution) whith different branches. 

## Prerequisites 
* dotnet 5

## Run Unit Tests 
* `cd UnitTests`
* `dotnet test /p:CollectCoverage=true /p:CoverletOutputFormat=cobertura`
* If you want to have a coverage report run `dotnet ~/.nuget/packages/reportgenerator/5.0.2/tools/net5.0/ReportGenerator.dll "-reports:coverage.cobertura.xml" "-targetdir:coveragereport" -reporttypes:Html` and open the generated `index.html` inside the `coveragereport` directory. 