
# Teaching plan

## Week 1: Basics, Console projects

### Lesson 1

#### Aim

    1. Introduce myself, the course, get to know each other, our backgrounds and experiences, explain
    the Lithuanian market for .NET developers.
    2. Explain the structure of the course.
    3. Install Visual Studio 2019, get familiar with the development environment, create a new project.
    4. Get familiar with debugging technique.

#### Homework/Project

    Main: Hello World in Visual Studio.
    Extra: Enter your name or surname in Console window and print out a full sentence.
    Extra: Enter your date of birth and produce age.

### Lesson 2

#### Aim

    1. Get familiar with Object-oriented programming (OOP).
    2. Get familiar with basic programming concepts in .NET: arrays, lists, loops, if statements, operators and etc.

#### Homework/Project

    Main: Console Calculator.
    Extra: Upload it to GitHub.

### Lesson 3

#### Aim

    1. Continue learning C# programming, inheritance, encapsulation, abstraction and etc.
    2. Introduce NuGet packages library.
    3. Introduce web scraping via ScrapySharp NuGet package.

#### Homework/Project

    Main: Job advertisement scraper.
    Extra:

## Week 2: MVC + Razor, API technologies.

### Lesson 1

#### Aim

    1. Introduce MVC design pattern and Razor.
    2. Explain Project folder structure.
    3. Introduce sending data to the controllers.
    4. Explain Routing concept in MVC.

#### Homework/Project

    Main: Registration form application.
    Extra: Back-end validation and attributes.

### Lesson 2

#### Aim

    1. Introduce Razor engine limitations and explain why JavaScript is needed.
    2. Enriching Razor with JavaScript.
    3. Introduce AJAX/jQuery in Razor applications.

#### Homework/Project

    Main: Registration form upgrade. Make it a Single-page application (SPA).
    Extra:

### Lesson 3

#### Aim

    1. Introduce WebAPI and differences from MVC.
    2. Explain REST API software architecture.
    3. Sending parameters (FromBody vs FromUrl).
    4. Test it via HttpGet, HttpPost, HttpDelete, using Postman.

#### Homework/Project

    Main: 'Minima' shop Warehouse RESTful API system for three items: bread, milk and cake.
    Extra: 3 items should reuse the same code, generic controllers, repository.
    Extra: Add Swagger to API.

## Week 3: Databases

### Lesson 1

#### Aim

    1. Create a database on your local machine, setup MS SQL.
    2. Create schemas, tables, test data.
    3. SQL statements: SELECT, UPDATE, INSERT, DELETE. 
    4. SqlConnecion with .NET Core.

#### Homework/Project

    Main: Introduce customer object in 'Minima' application.
    Upgrade existing application to be able to filter by the customer.
    Extra: Upgrade the database with millions of records and observe the performance. 

### Lesson 2

#### Aim

    1. Introduce Entity Framework Core, its benefits over plain SQL.
    2. Get familiar with DbSets, Linq.

#### Homework/Project

    Main: Upgrade 'Minima' to use EF Core and Linq instead of SqlConnection.
    Extra: Research IEnumerable vs IQueryable and apply proper usage.

### Lesson 3

#### Aim

    1. Introduce Foreign Keys, Indexes.
    2. Explain Stored procedures, functions.
    3. Explain SQL clauses: Joins, Group By, Aliases.
    4. The issues with Big Data and efficiency.

#### Homework/Project

    Main: Design patterns and Dependency Injection (DI).
    Implementing Dependency Injection, applying Service, Repository patterns.
    Extra:

## Week 4: Code-reusability, Architecture and Design patterns

### Lesson 1

#### Aim

    1. Understand Domain Driven design (DDD) and apply it's architecture.
    2. Introduce an interface and its power through Dependency Injection (DI).
    3. Repository and Service coding patterns.

#### Homework/Project

    Main: Upgrade existing 'Minima' project to employ Customer and Product service, inject them as services.
    Refactor database access to use Repositories (Generic repositories + Unit of work).
    Extra:

### Lesson 2

#### Aim

    1. Dividing models into Entities and Data Transfer Objects (DTOs).
    2. Configure and employ AutoMapper.
    3. Exception handling.

#### Homework/Project

    Main: Employ the principles above to the current project.
    Extra:

### Lesson 3

#### Aim

    1. Introduction to Asynchronous Programming: Async/Await.
    2. Extension methods, Helper classes. When to use static classes.
    3. Shared project, common packages patterns.

#### Homework/Project

    Main: Employ the principles above to the current project.
    Extra:

## Week 5: Automated testing, Test-driven development (TDD)

### Lesson 1

#### Aim

    1. Introduction to Test-driven development (TDD).
    2. Understanding Unit tests.
    3. XUnit testing framework, Facts/Theories.
    4. Architecture for testing frameworks.

#### Homework/Project

    Main: Adding unit tests for existing projects.
    Extra:

### Lesson 2

#### Aim

    1. Integration testing.
    2. Mocking services with Moq.
    3. Replacing Database with InMemory Database for testing.

#### Homework/Project

    Main: Adding Integration tests to current projects.
    Extra:

### Lesson 3

#### Aim

    1. This is a revision session with those who need more help.
    2. The experienced ones will work on Gilded Rose Refactoring Kata.

#### Homework/Project

    Extra: GildedRose refactoring Kata
    https://github.com/emilybache/GildedRose-Refactoring-Kata

## Week 6: Working in teams, team project.

### Lesson 1

#### Aim

    1. Understanding Git, branching, merge-request, conflicts.
    2. Scrum, sprint methodologies.
    3. Divide into teams and work together to simulate real-life scenarios.

#### Homework/Project

    Major project: a Bank application. Be creative!
    Suggestions: be able to register and login (ignore security for now),
    Top up with the single click. Be able to send money to other account.
    Extra ideas: investing, be able to request money. Be creative!

#### Lesson 2-3

    Continue working on the Bank Project.

## Week 7: Front-end, SPA

### Lesson 1

#### Aim

    1. Introduction to SPA JavaScript frameworks.
    2. Introduction to Angular CLI + Typescript.
    3. HttpClient in Angular.

#### Homework/Project

    Main: Create a basic Angular client to consume .NET Core API.
    Extra: 

### Lesson 2

#### Aim

    1. Dive further into Angular, Typescript.
    2. Components, Services.
    3. Angular HttpGet, HttpPost, Delete requests.

#### Homework/Project

    Main: Moving existing functionality into Angular client.
    Extra:

### Lesson 3

#### Aim

    1. Further dive into Angular, Typescript.
    2. Revision on the previous modules.

#### Homework/Project

    Main: Full Angular spa integration with .NET Core.
    Extra:

## Week 8: Pipelines, Azure DevOps, Hosting

### Lesson 1

#### Aim

    1. What is a pipeline.
    2. CI/CD.
    3. Introduction to Azure.

### Homework/Project

    Main: Setup a first pipeline in GitHub, which checks builds and runs tests.
    Extra:

### Lesson 2

#### Aim

    1. Free hosting solutions.
    2. Azure hosting.
    3. Database hosting.

#### Homework/Project

    Main: Host a .NET project publicly.

### Lesson 3

#### Aim

    1. Azure advanced: artifacts, blob storage, pricing, databases.

### Homework/Project

    Main: To be added

## Week 9: Working with legacy and complex code, .NET Framework

### Lesson 1

#### Aim

    1. Learn to analyse complex production code written by others.

#### Homework/Project

    Main: Pick a open source .NET project from GitHub.
    and present its code. What architecture, pattern it uses?
    https://github.com/quozd/awesome-dotnet
    Extra:

### Lesson 2

#### Aim

    1. Working with monoliths, spaghetti code.
    2. Advanced refactoring.

#### Homework/Project

    Main: An example interview coding task.
    Extra:

### Lesson 3

#### Aim

    1. .NET Framework and other technologies that are still being used in the industry.
    2. Project setup with .NET Framework and OWin.
    3. OData Web API.

#### Homework/Project

    Main: Setup Odata API on .NET Framework.
    Extra:
