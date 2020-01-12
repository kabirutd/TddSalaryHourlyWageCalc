# TDD Salary, Hourly Wage Calculator
Demonstrates my understanding of **Test Driven Development** through the creation of an app, which calculates Salary and Hourly wages


## Red, Green, Refactor

These are steps that we repeat for each unit test case

### Red

[![Screenshot](https://github.com/codeman061988/TddSalaryHourlyWageCalc/blob/master/docs/RedScreenshot.PNG "Screenshot")](https://github.com/codeman061988/TddSalaryHourlyWageCalc/blob/master/docs/RedScreenshot.PNG "Screenshot")

Add a failing test first. This makes us confident that our test is going to fail when we expect it to. There is no point in having a test that cannot catch bugs and always passes.

Here we add an initial TestClass to a new solution in Visual Studio

Following the 3 steps of unit testing:

We **arrange** our code by instantiating a new instance of the class which does not exist but we anticipate to perform our business functionality.

We **act** by initializing a new variable of type decimal to hold our annualSalary value, which we declare from an anicipated method called GetAnnualSalary, which takes a decimal as a parameter.

We **assert** that the outcome of GetAnnualSalary will be equal to 104000

### Green
Update the failing code in our application so that the test passes. 

### Refactor
Beutify our code. Remove duplicates, improve the design, make the code easier to read, adhere to coding standards, and the re-run the unit test to make sure it still passes after all of our changes.