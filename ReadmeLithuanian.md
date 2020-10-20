
# Mokymo planas

## Savaitė 1 Pradiniai/ konsoles projektai

### Pamoka 1

#### Tikslai

    1. Prisistatymas savęs , kurso, susipažinimas, .NET Programuotojo rinkos pristatymas
    2. Kurso struktura ir tikslai
    3. Visual studio irankio idiegimas, programavimo aplinkos configuracija, 
    naujų projektų kurimas.
    4. Ką daryti, kai užstringi programavimas.

#### Namų darbai projektas

    Pagrindinis: 'Hello world' projektas
    Extra: Vardo pavardės ivedimas ir išspausdimas.
    Extra: Gimimo datos įvedimas ir amžiau spausdinimas.

### Pamoka 2

#### Tikslai

    1. Objektinis programavimas
    2. C# programavimai: arrays, loops, if statements, lists and etc

#### Homework/Project

Main: Konsolinis skaičiuotuvas
Extra: Įkėlimas į Github.

### Lesson 3

#### Tikslai

    1. DAugiau c# programavimo, paveldėjimas.
    2. Instaliuojamos bibliotekos (Nuget)
    3. Informacijos išgavimas (web scraping) su ScrapySharp biblioteka.

#### Homework/Project

 Darbo skelbimo informacijos automatinė analizė (Web scraper)

## Week 2 MVC + Razor / Api technologijos

### Lesson 1

#### Tikslai

    1. MVC + Razor technologijos
    2. Projektų folderių/failu struktura
    3. duomenų siuntimas/gavimas iš kontrolerių.
    4. Web linkų maršrutizavimas projekte (routing)

#### Projektas

    Main : Registracijos formos applikacija.
    Extra: Siunčiamų reikšmių tikrinimas (Input validation)

### Pamoka 2

#### Tikslai

    1. Razor problemos ir kam reikalingas Javascriptas
    2. Javascripto naudojimas Razor applikacijose
    3. Ajax/Jquery bibliotekos mūsų aplikacijose

#### Projektas

    Registracijos formos tobulinimas -> paverčiant tai SPA su javascriptu

### Lesson 3

#### Tikslai

    1. Introduce WebApi  (vs MVC)
    2. Understand Rest Api
    3. Sending parameters (FromBody vs FromUrl)
    4. Test it via HttpGet, HttpPost, HttpDelete, Using Postman

#### Projektas

    Main: 'Minima' shop Warehouse Restfull Api system for 3 items: bread, milk and cake.
    Extra: 3 items should reuse the same code, generic controllers, repository.
    Extra: Add Swagger to Api

## Week 3 Databases

### Lesson 1

#### Tikslai

    1. Create database on you local machine, setup mssql
    2. Create schemas/tables/data
    3. Selecting data
    4. SqlConnecion with .net core

#### Projektas

    Main: Introduce Customer object in 'Minima' application
    Upgrade existing application to be able to filter by customer.
    Extra: Upgrade the database with millions of records and observe the performance. 

### Pamoka 2

#### Tikslai

    1. Entity Framework Core introduced, its benefits over plain sql.
    2. Get familiar with DbSets, Linq

#### Projektas

    Upgrade 'Minima' to use EF core and LinQ instead of SqlConnection
    Extra: Research IEnumerable vs iqueryable and apply proper usage.

### Lesson 3

#### Tikslai

    1. Introduce Foreign keys, Indexes.
    2. Learn Stored procedures, functions 
    3. Joins, Group bys
    4. The issues with big data and efficiency.

Design patterns and dependency injection.
Implementing dependency injection, Applying Service/ Repository patterns.

## Week 4 Code-reusability Architecture and design patterns

### Lesson 1

#### Tikslai

    1. Understand Domain Driven design and apply its architecture
    2. Introduction to interface and its power through Dependency injection
    3. Repository and Service coding patterns

#### Projektas

    Upgrade existing 'Minima' project to employ Customer and Product service, 
    inject them as services.
    Refactor database accesss to use Repositories (Generic repositories + Unit of work)

### Pamoka 2

#### Tikslai

    1. Dividing models into Entities and Data Transfer Objects.
    2. Configure and employ automapper.
    3. EXception handling

#### Projektas

    Employ the principles above to the current project.

### Lesson 3

#### Tikslai

    1. Intro to asyncronous programming: Async/Await
    2. Extension methods, Helper classes. When to use static classes
    3. Shared project/ common packages patterns

#### Projektas

    Employ the principles above to the current project.

## Week 5 Automated testing, test driven development

### Lesson 1

#### Tikslai

    1. Introducing Test-driven development
    2. Understanding Unit tests
    3. XUnit testing framework, Facts/Theories
    4. Architecture for testing frameworks

#### Projektas

   1. Adding unit tests for existing projects

### Pamoka 2

#### Tikslai

    1. Integration testing
    2. Mocking services with Moq.
    3. Replacing Database with InMemory Database for testing

#### Projektas

    Adding Integration tests to current projects.

### Lesson 3

#### Tikslai

    1. This is a revision session with those who needs more help.
    2. The experiences ones will work on Gilded Rose refactoring kata

#### Projektas

    GildedRose refactoring Kata
    https://github.com/emilybache/GildedRose-Refactoring-Kata

## Week 6 Working in a team, team project

### Lesson 1

#### Tikslai

    1. Understand Git, branching, merge-request, conflicts.
    2. Scrum/sprints methodologies.
    3. Divide into teams and work together as in real-life scenarios.

#### Projektas

    Major project: a bank application. Be creative.
    Suggestions: be able to register and login (ignore security for now),
    Top up with single click. Be able to to send money to other account.
    Extra ideas: investing, be able to request money. Be creative!

#### Pamoka 2-3

    Bank Project continued.

## Week 7 Front-end/SPA

### Lesson 1

#### Tikslai

    1. Introduce to SPA js frameworks.
    2. Introduce Angular CLI + Typescript
    3. HttpClient in Angular.

#### Projektas

    Create a basic angular client to consume .net core Api.

### Pamoka 2

#### Tikslai

    1. Further dive into Angular, Typescript
    2. Components, Services
    3. Angular HttpGet, HttpPost, Delete requests

#### Projektas

    Moving existing functionality into Angular client.

### Lesson 3

#### Tikslai

    1. Further dive into Angular, Typescript
    2. Revision on previous modules

#### Projektas

    Full Angular spa intergation with .net core

## Week 8 Pipelines, Azure devops, Hosting

### Lesson 1

#### Tikslai

    1. What is a pipeline.
    2. CI/CD
    3. Introduction to azure.

#### Project

    Setuping first pipeline in github which checks builds and runs tests.

### Pamoka 2

#### Tikslai

    1. Free hosting solutions
    2. Azure hosting
    3. Database hosting

#### Projektas

    Host a .NET project publicly

### Lesson 3

#### Tikslai

    1. Azure advanced: artifacts, blob storage, pricing, databases

### Project

    To be added

## Week 9 Working with legacy and complex code, .NET framework

### Lesson 1

#### Tikslai

    1. Learn to analyse complex production code written by others.

#### Projektas

    Pick a project from .net solution open source (github)
    and present its code. What architecture, pattern it uses?

### Pamoka 2

#### Tikslai

    1. Working with monoliths, spagetti code.
    2. Advanced refactoring.

#### Projektas

    An example interview coding task

### Lesson 3

#### Tikslai

    1. .NET framework and other technologies still used in industry.
    2. Project setup ith .net framework and OWin
    3. OData web api

#### Projektas

    Setup Odata Api on .net framework.


