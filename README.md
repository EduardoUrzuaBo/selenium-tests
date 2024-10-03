# selenium-tests
Test for c# 
dotnet add package Selenium.WebDriver --version 4.25.0   

the similar command for all dependencies

dotnet add package PackageReference --version <package version>
  <ItemGroup>
    <PackageReference Include="Microsoft.NET.Test.Sdk" Version="17.11.1" />
    <PackageReference Include="NUnit" Version="4.2.2" />
    <PackageReference Include="NUnit3TestAdapter" Version="4.6.0" />
    <PackageReference Include="Selenium.Support" Version="4.25.0" />
    <PackageReference Include="Selenium.WebDriver" Version="4.25.0" />
  </ItemGroup>



Build the dot net 
dotnet build 

Run command to run the test 
 dotnet test .\bin\Debug\net8.0\selenium_tests.dll --filter TestCategory="Selenium"
