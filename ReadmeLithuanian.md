
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

#### Project

Main: Konsolinis skaičiuotuvas
Extra: Įkėlimas į Github.

### Pamoka  3

#### Tikslai

    1. DAugiau c# programavimo, paveldėjimas.
    2. Instaliuojamos bibliotekos (Nuget)
    3. Informacijos išgavimas (web scraping) su ScrapySharp biblioteka.

#### Project

 Darbo skelbimo informacijos automatinė analizė (Web scraper)

## Savaitė  2 MVC + Razor / Api technologijos

### Pamoka  1

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

### Pamoka  3

#### Tikslai

    1. WebApi technologija (vs MVC)
    2. Rest Api principai
    3. Duomeny siuntimas ir gavimas į/iš Api (FromBody vs FromUrl)
    4. Api naudojimas ir testavimas HttpGet, HttpPost, HttpDelete, su Postman applikacija

#### Projektas

    Main 'Minima' online parduotuvės aplikacijos programavimas su 3 produktais: duona,
    pienas, tortas.
    Extra: Visiems produktams naudoti bendrą koda: generic repository, 
    unitOfWork, services.
    Extra: Įdėti Swagger dokumentacijos įrankį į Api

## Savaitė 3 Duomenų bazės

### Pamoka 1

#### Tikslai

    1. Localios duomenų bazės sukurimas, Instaliavimas Microsoft Sql Server
    2. Schemų, lentele, duomenų sukurimas
    3. Duomenų išrinkimas
    4. Duomenų bazės prijugimas prie .net core (SqlConnection, Dapper)

#### Projektas

    Main: Kliento ikėlimas į Minima aplikaciją
    Filtruoti visus produktus pagal klientą.
    Extra: Įdėti didelius duomenų kiekius į duomenų bazę ir stebėtis pokyčius.

### Pamoka 2

#### Tikslai

    1. Entity Framework Core technologijos idėjimas, jos pranašumai pries SQL
    2. DbSets ir LINQ operacijos

#### Projektas

    Pakeisti Minima iš SQL į EF Core ir LINQ
    Extra: Ištyrinėti 'IEnumerable vs iqueryable' 
    ir patikrinti ar jūsų programa naudoja tai teisingai

### Pamoka  3

#### Tikslai

    1. Susipažinti su Sql Foreign keys, Indexes.
    2. Išmokti Stored procedures, functions  naudojimą
    3. Lentų sujungimai ir grupavimai (Joins, Group bys)
    4. Užklausų optimizacija (kaip rašyti Sql,The issues with big data and efficiency).

#### Project

Mokymasis savarankiškai: Design patterns and dependency injection.
Implementing dependency injection, Applying Service/ Repository patterns.

## Savaitė 4 Architektūra, kodo perpanaudojimas, švarus programavimas

### Pamoka 1

#### Tikslai

    1. Domain Driven Dizainas
    2. Interfaces ir jų naudojimas
    3. Repositorijos/Servisų programavimo stiliai.

#### Projektas

    Sukurti Klientų, produktų servisus ir idiegti juos į aplikaciją Minima.
    Pakeisti Duomenų bazės prieeigą naudojant Repositories. (Generic repositories 
    + Unit of work)

### Pamoka 2

#### Tikslai

    1. Entities vs Data Transfer Objects.
    2. Automapper įrankio naudojimas
    3. Darba su klaidomis programos metu (Exception handling)

#### Projektas

    Panaudoti išmoktus dalykus savoje applikacijoje

### Pamoka  3

#### Tikslai

    1. Asyncroninio programavimo pagrindai ir panaudojimai. Async/Await
    2. Extension metodai, Pagalbinės klasės. Kada naudoti statines klases.
    3. Kodo perpanaudojimas projektuose, savų bibliotekų kurimas 
    (Shared class library, nuget feed)

#### Projektas

    Employ the principles above to the current project.

## Savaitė  5 Automatizuotas testavimas, programavimas pagrįstas testais

### Pamoka  1

#### Tikslai

    1. Programavimas pagrįstas testais (Test-driven development)
    2. susipažinimas su Unit testais
    3. XUnit testavimo spendimai, XUnit Faktai, Teorijos
    4. Testavimo projektų/folderių išdėstymas.

#### Projektas

   1. Automatinių testų sukūrimas Minima projektui.

### Pamoka 2

#### Tikslai

    1. Integraciniai testai
    2. Servisų paruošimas testavimui su Moq
    3. Duomenų bazės pakeitimas su Atminties baze testavimui.

#### Projektas

    Integracinių testų pridėjimas Minima projektui.

### Pamoka  3

#### Tikslai

    1. Paskaita skirta klausti, prisivyti.
    2. Patyrę galės daryti užduotį GildedRose.

#### Projektas

    GildedRose refactoring Kata
    https://github.com/emilybache/GildedRose-Refactoring-Kata

## Savaitė  6 Working in a team, team project

### Pamoka  1

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

## Savaitė  7 Front-end/SPA

### Pamoka  1

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

### Pamoka  3

#### Tikslai

    1. Further dive into Angular, Typescript
    2. Revision on previous modules

#### Projektas

    Full Angular spa intergation with .net core

## Savaitė  8 Pipelines, Azure devops, Hosting

### Pamoka  1

#### Tikslai

    1. What is a pipeline.
    2. CI/CD
    3. Introduction to azure.

### Project

    Setuping first pipeline in github which checks builds and runs tests.

### Pamoka 2

#### Tikslai

    1. Free hosting solutions
    2. Azure hosting
    3. Database hosting

#### Projektas

    Host a .NET project publicly

### Pamoka  3

#### Tikslai

    1. Azure advanced: artifacts, blob storage, pricing, databases

### Project

    To be added

## Savaitė  9 Working with legacy and complex code, .NET framework

### Pamoka  1

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

### Pamoka  3

#### Tikslai

    1. .NET framework and other technologies still used in industry.
    2. Project setup ith .net framework and OWin
    3. OData web api

#### Projektas

    Setup Odata Api on .net framework.


