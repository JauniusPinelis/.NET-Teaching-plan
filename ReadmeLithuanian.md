
# Mokymo planas

## I Savaitė: Pradmenys, konsolinės ("Console") aplikacijos

### I Pamoka:

#### Tikslai

    1. Mūsų visų prisistatymai, kurso pristatymas, susipažinimas tarpusavyje, Lietuvos darbo rinkos pristatymas esant .NET Programuotoju.
    2. Kurso struktūra ir tikslai.
    3. Visual Studio 2019 IDE (Integruotos kūrimo aplinkos) instaliacija, susipažinimas su programavimo aplinka, naujų projektų sukūrimas.
    4. Kaip surasti ir ištaisyti programavimo klaidas? "Debugging" programavimo technika.

#### Namų darbai/projektas

    Pagrindinis darbas: 'Hello World' projekto sukūrimas.
    Papildomai: Vardo bei pavardės įvedimas ir išspausdinimas viename sakinyje.
    Papildomai: Gimimo datos įvedimas ir amžiaus išvedimas.

### II Pamoka:

#### Tikslai

    1. Susipažinimas su Objektiniu programavimu (OOP).
    2. C# programavimo kalbos įvadas: masyvai, sąrašai, ciklai, if sakiniai, operatoriai ir kiti sintaksės elementai.

#### Namų darbai/projektas

    Pagrindinis darbas: Konsolinis skaičiuotuvas.
    Papildomai: Skaičiuotuvo įkėlimas į GitHub.

### III Pamoka:

#### Tikslai

    1. Tęsiame toliau su C# programavimu: paveldėjimas ("Inheritance"), duomenų apgauba ("Encapsulation"), abstraktumas ("Abstraction").
    2. NuGet paketų tvarkyklės pristatymas.
    3. Automatinis informacijos surinkimas iš interneto naudojant "web scraping" techniką bei ScrapySharp biblioteką.

#### Namų darbai/projektas

    Pagrindinis darbas: Darbo skelbimų informacijos surinkimas naudojant "Web Scraping" techniką.
    Papildomai:

## II Savaitė: MVC + Razor, API technologijos

### I Pamoka

#### Tikslai

    1. MVC architektūros ir Razor variklio pristatymas.
    2. Projekto aplankalų struktūros pristatymas.
    3. Duomenų siuntimas ir gavimas iš kontrolerių ("Controllers").
    4. Web nuorodų maršrutizavimas projekte ("Routing").

#### Namų darbai/projektas

    Pagrindinis darbas: Registracijos formos applikacija.
    Papildomai: Siunčiamų reikšmių tikrinimas serverio dalyje ("Input Validation").

### II Pamoka

#### Tikslai

    1. Razor variklio limitai bei kam mums yra reikalingas Javascript programavimo kalba?
    2. Javascript kalbos naudojimas Razor aplikacijose.
    3. AJAX/jQuery bibliotekų pristatymas mūsų aplikacijose.

#### Namų darbai/projektas

    Pagrindinis darbas: Registracijos formos tobulinimas. Pavertimas vieno puslapio aplikacija ("Single Page Application").
    Papildomai:

### III Pamoka

#### Tikslai

    1. WebAPI technologija bei jos skirtumai lyginant su MVC.
    2. Rest API architektūra.
    3. Parametrų siuntimas ("FromBody" prieš "FromUrl").
    4. API testavimas ir naudojimasis pasitelkiant "HttpGet", "HttpPost", "HttpDelete" užklausomis bei Postman aplikacija.

#### Namų darbai/projektas

    Pagrindinis darbas: 'Minima' internetinės parduotuvės kūrimas su trimis produktais: duona, pienu bei tortu.
    Papildomai: Visi šie produktai turėtų pernaudoti tapatį kodą, kontrolerius bei saugyklą.
    Papildomai: Įdiegti "Swagger" dokumentacijos kalbą į API.

## III Savaitė: Duomenų bazės

### I Pamoka:

#### Tikslai

    1. Lokalios duomenų bazės sukūrimas, Microsoft Sql Server instaliacija.
    2. Duomenų bazės schemų, lentelių, pradinių duomenų sukūrimas.
    3. Darbas su duomenimis: "SELECT", "UPDATE", "INSERT", "DELETE" veiksmai.
    4. Duomenų bazės prijungimas prie .NET Core ("SqlConnection", "Dapper").

#### Namų darbai/projektas

    Pagrindinis darbas: Kliento objekto pridėjimas į Minima aplikaciją.
    Papildomai: Produktų filtravimas pagal kliento objektą.
    Papildomai: Didelio kiekio duomenų įkėlimas į duomenų bazę ir greičio pokyčio stebėjimas.

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

#### Namų darbai/projektas

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

    Išmoktų tehcnikų panadaudojimas 'Minima' projekte

## Savaitė  5 Automatizuotas testavimas, programavimas pagrįstas testais

### Pamoka  1

#### Tikslai

    1. Programavimas pagrįstas testais (Test-driven development)
    2. Susipažinimas su Unit testais
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

## Savaitė 6 Darbas komandoje

### Pamoka  1

#### Tikslai

    1. Darbas su Git versijavimo sistema.
    2. Scrum/Sprints projektu valdymo metodologijos.
    3. Pasiskirstymas komandomis ir darbas realaus pasaulio scenarijumi.

#### Projektas

    Savaitės projektas: Banko aplikacija (Revolut klonas). Būkite kurybingi.
    Suggestions: Registracija/ prisijungimas (ignoruokite saugumo standartus kolkas)
    Saskaitos papildimas vienu paspaudimu, pinigu siuntimas kitoms saskaitoms. 
    Valiutų konvertavimas.
    Extra: Investavimas, Pinigu prašymai (Request money). Sukurkite ką norite, dirbkite kartu.

#### Pamoka 2-3

    Revolut klono projekto tęsinys.

## Savaitė 7 Dizaino/ išorinės pusės sprendimai .net Core aplikacijomis

### Pamoka 1

#### Tikslai

    1. Bibliotekos skirtos išorinės pusės igyvendinimui
    2. Angular CLI + Typescript ekosistema
    3. HttpClient technologija Angular.

#### Projektas

    Sukurti paprasta Angular http klienta, kuris iškviestų Api sistemą.

### Pamoka 2

#### Tikslai

    1. Gylinimasis į Angular ir Typescript.
    2. Components ir servisai Angular sistemoje.
    3. Angular HttpGet, HttpPost, Delete requests

#### Projektas

    Naujų technikų įgyvendinimas Angular projekte.

### Pamoka 3

#### Tikslai

    1. Tolimesnis Gylinimasis į Angular, Typescript
    2. Kartojimas/klausimai iš praeitų temų.

#### Projektas

    Pilna Angular integracija su .net Core sistema

## Savaitė  8 Cloud kompiuterija .NET ekosistemoje, Azure technologijos

### Pamoka 1

#### Tikslai

    1. Automatizuotas testų paleidimas ir programų ikėlimas į internetą.
    2. Azure technologijų spektras.

### Namų darbai/projektas

    Projektų statymas ir paleidimas su Azure

### Pamoka 2

#### Tikslai

    1. Nemokamo hostingo provideriai.
    2. Azure sistemų talpinimas
    3. Duomenų bazių talpinimas internete

#### Projektas

    .NET projekto patalpinimas į internetą.

### Pamoka 3

#### Tikslai

    1. Gylinimasis į Azure: Artifactai, Mokėjimo planai, certifikatai, duomenų bazės.

### Namų darbai/projektas

    Bus pridėta

## Savaitė 9 Darbas su sudėtingu kodu senesnėmis technologijomis

### Pamoka 1

#### Tikslai

    1. Darbas su kitų žmonių parašytu kodu.
    2. Darbas su masyviais projektais.

#### Projektas

    Pasirinkto projekto iš Open-Source (github) pristatymas. 
    Architekturos paaiškinimas, naudojamų technologijų analizė

### Pamoka 2

#### Tikslai

    1. Darbas su monolotiniu (spagetti) kodu, 
    2. Kodo tvarkimo metodika.

#### Projektas

    Darbo intervių namų užduoties pavyzdžio atlikimas

### Pamoka 3

#### Tikslai

    1. .NET Framework ir kitų senesnių technologijų naudojimas rinkoje.
    2. .NET Framework projekto paleidimas su Owin pagalbą.
    3. Odata technologija

#### Projektas

    Odata projektas .NET Framework ekosistemoje
