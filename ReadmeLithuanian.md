
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

### II Pamoka:

#### Tikslai

    1. Entity Framework Core technologijos pristatymas, jos pranašumai prieš paprastą SQL.
    2. Susipažinimas su DbSets ir su LINQ operacijomis.

#### Namų darbai/projektas

    Pagrindinis darbas: Pagerinti "Minima" aplikaciją, kad būtų naudojamas EF Core ir Linq vietoje SqlConnection.
    Papildomai: Susipažinti su "IEnumerable" ir "IQueryable" skirtumais bei patikrinti ar 
    jūsų projektas juos naudoja teisingai.

### III Pamoka:

#### Tikslai

    1. Susipažinimas su SQL Foreign keys, Indexes.
    2. "Stored" procedūrų, funkcijų naudojimo pristatymas.
    3. Lentų sujungimas bei grupavimas ("Joins", "Group by", "Aliases").
    4. Problemos, atsirandančios dirbant su didžiaisiais duomenimis ("Big Data") ir užklausų optimizacija.

#### Namų darbai/projektas

    Pagrindinis darbas: Darbas su Design patterns ir Dependency Injection (DI).
    Papildomai:

## IV Savaitė: Architektūra, kodo pernaudojimas, Design patterns

### I Pamoka

#### Tikslai

    1. Susipažinti su Domain Driven Design (DDD) architektūra bei jo praktiniu pritaikymu.
    2. Interface ir jo taikymo per Dependency Injection (DI) pristatymas.
    3. Repository ir Service Design pattern pristatymas.

#### Namų darbai/projektas

    Pagrindinis darbas: Patobulinti "Minima" aplikaciją taip, kad būtų naudojami kliento ("Customer") ir produkto ("Product") objektai, naudoti šiuos objektus kaip servisus.
    Duomenų bazės prieiga turėtų pradėti naudoti Repositoriy Design pattern.
    Papildomai:

### II Pamoka

#### Tikslai

    1. Išsiaiškinsime skirtumus tarp Entity ir Data Transfer Objects ("DTOs").
    2. Automapper įrankio konfigūracija bei panaudojimas.
    3. Darbas su klaidomis, atsirandančiomis programos metu ("Exception handling").

#### Namų darbai/projektas

    Pagrindinis darbas: Panaudoti šiuos dalykus savoje aplikacijoje.
    Papildomai:

### III Pamoka

#### Tikslai

    1. Asinchroninis programavimas: Async/Await.
    2. Plėtimo metodai ("Extension methods"), Pagalbinės klasės ("Helper classes"). Kada reikia naudoti statines klases.
    3. Kodo pernaudojimas projektuose, savų bibliotekų kūrimas.

#### Namų darbai/projektas

    Pagrindinis darbas: Išmoktų technikų panaudojimas "Minima" projekte.
    Papildomai:

## V Savaitė: Automatizuotas testavimas, Test-driven development (TDD)

### I Pamoka

#### Tikslai

    1. Susipažinimas su Test-driven development (TDD).
    2. Susipažinimas su "Unit" testais.
    3. XUnit testavimo biblioteka, "Facts", "Theories".
    4. Testavimo architektūra: projektų, aplankalų, testų išdėstymas.

#### Namų darbai/projektas

    Pagrindinis darbas: Pridėti automatinius testus į "Minima" projektą.
    Papildomai:

### II Pamoka

#### Tikslai

    1. Integracinis testavimas.
    2. Servisų paruošimas testavimui su "Moq" biblioteka.
    3. Duomenų bazės simuliacija testuose saugant duomenų bazę atmintyje ("InMemory Database").

#### Namų darbai/projektas

    Pagrindinis darbas: Integracinių testų pridėjimas "Minima" projektui.
    Papildomai:

### III Pamoka

#### Tikslai

    1. Paskaita bus skirta klausimams, pagalbai ar prisivijimui prie klasės.
    2. Labiau patyrę, neturintys ką daryti, galės daryti užduotį "GildedRose".

#### Namų darbai/projektas

    Papildomai: GildedRose užduotis
    https://github.com/emilybache/GildedRose-Refactoring-Kata

## VI Savaitė: Darbas komandose, grupiniai projektai

### I Pamoka

#### Tikslai

    1. Darbas su Git versijavimo sistema.
    2. Scrum, Sprints projektų valdymo metodologijos.
    3. Pasiskirstymas komandomis, realaus gyvenimo situacijų simuliacija.

#### Namų darbai/projektas

    Savaitės projektas: Banko aplikacija ("Revolut" kopija). Būkite kūrybingi!
    Pasiūlymai: Registracijos bei prisijungimo funkcionalumo pridėjimas (ignoruojame saugumo standartus kol kas).
    Sąskaitos papildimas vienu paspaudimu, pinigų siuntimas į kitas sąskaitas. 
    Valiutos konvertavimas.
    Papildomai: Investavimas, Pinigų prašymo užklausos ("Request money"). Sukurkite ką norite, dirbkite kartu.

#### II-III Pamokos

    Tęsiame darbą prie Banko aplikacijos.

## VII Savaitė: Dizaino, Front-end dalis, Vieno puslapio aplikacija ("SPA")

### I Pamoka

#### Tikslai

    1. Bibliotekų, skirtų Front-end daliai, Vieno puslapio aplikacijai ("SPA") pristatymas.
    2. Angular CLI ir Typescript ekosistemos pristatymas.
    3. HttpClient ir Angular technologijų pristatymas.

#### Namų darbai/projektas

    Pagrindinis darbas: Sukurti paprastą Angular klientą, kuris naudotų .NET Core API.
    Papildomai:

### II Pamoka

#### Tikslai

    1. Tolimesnis gilinimasis į Angular ir Typescript technologijas.
    2. Komponentai ir servisai Angular sistemoje.
    3. Angular "HttpGet", "HttpPost", "Delete" užklausos.

#### Namų darbai/projektas

    Pagrindinis darbas: Esamo funkcionalumo perkėlimas į Angular klientą.
    Papildomai:

### III Pamoka

#### Tikslai

    1. Toliau mokomės Angular, Typescript.
    2. Praeitų modulių apžvalga, kartojimasis.

#### Namų darbai/projektas

    Pagrindinis darbas: Pilna Angular integracija su .NET Core.
    Papildomai:

## VIII Savaitė: Debesų kompiuterija .NET ekosistemoje, Azure technologijos

### I Pamoka

#### Tikslai

    1. Kas yra "pipeline"?
    2. Nuolatinės integracijos ("CI") ir nuolatinio diegimo ("CD") įvadas.
    3. Azure debesų kompiuterijos pristatymas.

### Namų darbai/projektas

    Pagrindinis darbas: Projektų nuolatinės integracijos ("CI") bei nuolatinio diegimo ("CD") pridėjimas, 
    šios integracijos tikrina programas bei testus.
    Papildomai:

### II Pamoka

#### Tikslai

    1. Nemokamos prieglobos ("Hosting") tiekėjų pristatymas.
    2. Azure priegloba.
    3. Duomenų bazių priegloba.

#### Namų darbai/projektas

    Pagrindinis darbas: .NET projekto patalpinimas į internetą.
    Papildomai:

### III Pamoka

#### Tikslai

    1. Gilinimasis į "Azure" toliau: artefaktai, mokėjimo planai, sertifikatai, duomenų bazės.

### Namų darbai/projektas

    Pagrindinis darbas: Bus pridėta.
    Papildomai:

## IX Savaitė: Darbas su senu ir sudėtingu kodu, .NET Framework karkasas

### I Pamoka

#### Tikslai

    1. Išmokti dirbti su sudėtingu kodu, parašytu kitų žmonių.

#### Namų darbai/projektas

    Pagrindinis darbas: Pasirinkti atviro kodo ("Open source") .NET projektą iš GitHub
    ir pristatyti šio projekto kodą. Kokia jo architektūra, kokius "Design pattern" jis naudoja?
    https://github.com/quozd/awesome-dotnet
    Papildomai:

### II Pamoka

#### Tikslai

    1. Darbas su monolitiniais projektais, "spaghetti" kodu.
    2. Kodo tvarkymo metodika.

#### Namų darbai/projektas

    Pagrindinis darbas: Darbo interviu užduotis.
    Papildomai:

### III Pamoka

#### Tikslai

    1. .NET Framework ir kitų senesnių technologijų, kurios dar vis naudojamos rinkoje, apžvalga.
    2. .NET Framework projekto paleidimas su Owin.
    3. Odata WebAPI technologija.

#### Namų darbai/projektas

    Pagrindinis darbas: Odata WebAPI sudiegimas į NET Framework projektą.
    Papildomai:
