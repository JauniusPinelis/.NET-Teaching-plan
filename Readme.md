
# Teaching plan

## Week 1 Basics/Console projects

### Lesson 1

#### Aim

    1. Introduce myself, the course, get to know each one's background and explain
    the Lithuanian market for .net developers.
    2. Explain the structure of the course
    3. Install Visual studio, Get familiar with development environment, create new project.
    4. Get familiar with debugging technique.

#### Homework/Project

    Main: hello world in visual studio.
    Extra: Enter your name/ surename in console and print out full sentence.
    Extra: Enter your date of birth and produce age.

### Lesson 2

#### Aim

    1. Get Familiar with Object programming
    2. Get familiar with basic programming concepts in .net: arrays, loops, 
    if statements, lists and etc

#### Homework/Project

Main: Console Calculator
Extra: Upload it to github.

### Lesson 3

#### Aim

    1. Continue learning c# programming, inheritance.
    2. Introduce nuget packages library
    3. Introduce scraping via ScrapySharp nuget package

#### Homework/Project

 Job advertisement scraper.

## Week 2 MVC + Razor / Api technologies

### Lesson 1

#### Aim

    1. MVC + Razor introduced
    2. Project folder structure explained
    3. Sending data to controllers
    4. Routing in mvc

#### Project

    Main : Registration form application
    Extra: Back-end validation and attributes

### Lesson 2

#### Aim

    1. Introduce limitation of razors and why Javascript is needed
    2. Enriching Razor with Javascript
    3. Introduce Ajax/Jquery in razor applications.

#### Project

    Registration form upgrade -> make it Single page Application

### Lesson 3

#### Aim

    1. Introduce WebApi  (vs MVC)
    2. Understand Rest Api
    3. Sending parameters (FromBody vs FromUrl)
    4. Test it via HttpGet, HttpPost, HttpDelete, Using Postman

#### Project

    Main: 'Minima' shop Warehouse Restfull Api system for 3 items: bread, milk and cake.
    Extra: 3 items should reuse the same code, generic controllers, repository.
    Extra: Add Swagger to Api

### Lesson 3

#### Aim

    1. Create database on you local machine, setup mssql
    2. Create schemas/tables/data
    3. Selecting data
    4. SqlConnecion with .net core

#### Project

   Main: Introduce Customer object in 'Minima' application
   Upgrade existing application to be able to filter by customer.
   Extra: Upgrade the database with millions of records and observe the performance. 

### Lesson 2

#### Aim

    1. Entity Framework Core introduced, its benefits over plain sql.
    2. Get familiar with DbSets, Linq

#### Project

    Upgrade 'Minima' to use EF core and LinQ instead of SqlConnection
    Extra: Research IEnumerable vs iqueryable and apply proper usage.

### Lesson 3

#### Aim

    1. Introduce Foreign keys, Indexes.
    2. Learn Stored procedures, functions 
    3. Joins, Group bys
    4. The issues with big data and efficiency.

Design patterns and dependency injection.
Implementing dependency injection, Applying Service/ Repository patterns.

## Week 4 Code-reusability Architecture and design patterns

### Lesson 1

#### Aim

    1. Understand Domain Driven design and apply its architecture
    2. Introduction to interface and its power through Dependency injection
    3. Repository and Service coding patterns

#### Project

    Upgrade existing 'Minima' project to employ Customer and Product service, 
    inject them as services.
    Refactor database accesss to use Repositories (Generic repositories + Unit of work)

### Lesson 2

#### Aim

    1. Dividing models into Entities and Data Transfer Objects.
    2. Configure and employ automapper.
    3. EXception handling

#### Project

    Employ the principles above to the current project.

### Lesson 3

#### Aim

    1. Intro to asyncronous programming: Async/Await
    2. Extension methods, Helper classes. When to use static classes
    3. Shared project/ common packages patterns

#### Project

    Employ the principles above to the current project.

## Week 5 Automated testing, test driven development

### Lesson 1

#### Aim

    1. Introducing Test-driven development
    2. Understanding Unit tests
    3. XUnit testing framework, Facts/Theories
    4. Architecture for testing frameworks

#### Project

   1. Adding unit tests for existing projects

### Lesson 2

#### Aim

    1. Integration testing
    2. Mocking services with Moq.
    3. Replacing Database with InMemory Database for testing

#### Project

    Adding Integration tests to current projects.

### Lesson 3

#### Aim

    1. This is a revision session with those who needs more help.
    2. The experiences ones will work on Gilded Rose refactoring kata

#### Project

    GildedRose refactoring Kata
    https://github.com/emilybache/GildedRose-Refactoring-Kata

## Week 6 Working in a team, team project

### Lesson 1

#### Aim

    1. Understand Git, branching, merge-request, conflicts.
    2. Scrum/sprints methodologies.
    3. Divide into teams and work together as in real-life scenarios.

#### Project

    Major project: a bank application. Be creative.
    Suggestions: be able to register and login (ignore security for now),
    Top up with single click. Be able to to send money to other account.
    Extra ideas: investing, be able to request money. Be creative!

#### Lesson 2-3

    Bank Project continued.

## Week 7 Front-end/SPA

### Lesson 1

#### Aim

    1. Introduce to SPA js frameworks.
    2. Introduce Angular CLI + Typescript
    3. HttpClient in Angular.

#### Project

    Create a basic angular client to consume .net core Api.

### Lesson 2

#### Aim

    1. Further dive into Angular, Typescript
    2. Components, Services
    3. Angular HttpGet, HttpPost, Delete requests

#### Project

    Moving existing functionality into Angular client.

### Lesson 3

#### Aim

    1. Further dive into Angular, Typescript
    2. Revision on previous modules

#### Project

    Full Angular spa intergation with .net core

## Week 8 Pipelines, Azure devops, Hosting

### Lesson 1

#### Aim

    1. What is a pipeline.
    2. CI/CD
    3. Introduction to azure.

### Project

    Setuping first pipeline in github which checks builds and runs tests.

### Lesson 2

#### Aim

    1. Free hosting solutions
    2. Azure hosting
    3. Database hosting

#### Project

    Host a .NET project publicly

### Lesson 3

#### Aim

    1. Azure advanced: artifacts, blob storage, pricing, databases

### Project

    To be added

#### Week 9 Working with legacy and complex code, .NET framework

### Aim

    1. Learn to analyse complex production code written by others.

### Project

    Pick a project from .net solution open source (github)
    and present its code. What architecture, pattern it uses?
