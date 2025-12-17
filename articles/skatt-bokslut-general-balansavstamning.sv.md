---
lastLLMUpdateAt: '2025-12-17T06:58:38.342Z'
updatedAt: '2025-12-17T07:51:48.774Z'
pendingReview: false
currentVersion: 4
reviewedAt: '2025-12-17T07:07:23.100Z'
format: md
slug: general-balansavstamning
languages:
  - sv
  - en
folderId: null
createdAt: '2025-12-17T06:56:11.985Z'
status: draft
publishedAt: null
title: Balansavstämning
id: DAWh5QiBatBfx9M3OUWL
metadata:
  tags:
    - update
    - general
  area2: ''
  area1: general
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  targetAudience: []
---
# Balansavstämning

## Översikt
Den här uppdateringen introducerar förbättringar i funktionen för balansavstämning i Skatt & Bokslut. Dessa ändringar syftar till att göra processen mer effektiv och användarvänlig.

Balansavstämning – översikten hittar du under både **Periodavslut** och **Årsavslut**.

Översikten i Balansavstämning visar alla balanskonton som har transaktioner bokförda på sig fram till och med den period som du arbetar med för tillfället.

## Vad har ändrats?

### Anpassningsbara kolumner
Vilka kolumner som visas i översikten varierar beroende på storleken på den skärm du arbetar på. På mindre skärmar visas endast de viktigaste kolumnerna.

Du kan välja vilka kolumner som ska visas i Balansavstämning och Resultatanalys genom att klicka på **Dölj/Lägg till kolumn** i den övre delen av fönstret. Inställningen sparas per företag och gäller för alla perioder. För att återställa till standardinställningen, välj **Återställ till förvalda kolumner**.

### Fördjupad detaljnivå med drill down
Du kan utöka detaljnivån i Balansavstämning – Översikt med hjälp av drill down-funktionen, som låter dig titta närmare på verifikationerna som registrerats på kontona.

Belopp som är tillgängliga för drill-down är understrukna och byter färg till blått när du håller pekaren över dem i översikten. Klicka på ett tillgängligt belopp för att öppna en dialogruta vid namn **Kontoanalys**, där alla verifikationer som registrerats på det aktuella kontot visas.

Kontoanalysen öppnas i ett separat webbläsarfönster, vilket gör att du kan ha flera konton öppna samtidigt utan att störa ditt arbete. Du kan fritt flytta fönstret, till exempel till en andra skärm, för ökad översikt. Tänk på att när du stänger fliken stängs även alla fönster som öppnats därifrån.

När bokföringen innehåller resultatenheter, kostnadsbärare eller projekt kommer dessa att visas när verifikationerna öppnas. Notera att endast de 4 första dimensionerna visas.

I Kontoanalys visas det ingående saldot för det valda kontot och perioden ovanför verifikationslistan, medan det utgående saldot för kontot och perioden visas nedanför listan.

I verifikationslistan visas verifikationsdatum, verifikationsnummer, periodens förändring, kontosaldo efter varje verifikation och transaktionstext.

Från Kontoanalys är det möjligt att välja ett annat konto via kontoväljaren längst upp till vänster. Du kan också justera perioden som visas med hjälp av periodväljaren längst upp till höger.

Klicka på pilen bredvid en verifikation i listan för att visa en mer detaljerad vy för just denna verifikation. Den här vyn innehåller information om belastade kredit- och debetkonton, bokförda belopp, samt transaktionstext.

### Visa bifogade filer i kontoanalysen
Klicka på gemet i kolumnen **Bifogade filer** för att visa ett dokument som bifogats en verifikation. Välj vilket dokument du vill visa i rutan som öppnas.

I fönstret för förhandsgranskning kan du ladda ner det bifogade dokumentet genom att klicka på knappen **Ladda ner** och sedan enkelt dra det till en extern bilaga. Det är också möjligt att skapa en ny extern bilaga som dokumentet automatiskt länkas till genom att välja **Lägg till bilaga** i visningsläget.

### Fältförklaringar

*   **Avstämningsbelopp:** Du kan välja att fylla i avstämningsbeloppet antingen direkt i översikten eller på en bilaga. Om du har en integration med Bokföring & Fakturering, kommer några av beloppen i denna kolumn att fyllas i automatiskt när du importerar bokföringsuppgifter.
*   **Avstämningsdifferens:** Om det uppstår en differens mellan utgående balans och avstämningsbeloppet visas denna differens i denna kolumn. Du kan välja att skapa en bokslutsverifikation för differensen genom att klicka på den blåa symbolen i kolumnen **Avstämningsdifferens**. De bokslutsverifikationer som du skapat kan du se under Bokslutsverifikationer. Läs mer i Bokslutsverifikationer.
*   **Bilagor:** Om ett konto eller en kontogrupp har en bilaga kopplad till sig är gemikonen i denna kolumn blå, annars är den grå. När du klickar på en grå gemikon kan du gå direkt till huvudbilagan för kontot eller kontogruppen, eller lägga till en bilaga. För att lägga till en bilaga, klicka på gemikonen, välj **Lägg till bilaga** och välj vilken bilaga du vill lägga till. När du har valt bilaga och klickar på **Lägg till** blir du förflyttad till vyn **Bilagor** och kan fortsätta att arbeta med bilagan som vanligt. Om du lägger till en bilaga till ett konto kommer det kontot automatiskt att läggas till på bilagan som skapas. Det läggs inte till något konto om bilagan skapas på en kontogrupp. När du klickar på en blå gemikon visas en lista av de bilagor som finns bifogat till det kontot, samt en länk till huvudbilagan.
*   **Automatiska kontroller:** Denna kolumn visar resultatet av de automatiska kontroller som körts. En röd symbol visar att kontrollen hittat något. När du klickar på symbolen får du mer detaljerad information. En orange symbol visar att kontrollen inte kunnat köras. Ett exempel på detta är att kontrollen ska jämföra med tidigare perioder, men att det inte finns några tidigare perioder importerade till Skatt & Bokslut. En grön symbol visar att kontrollen har körts, men att ingen avvikelse hittades. Avvikande kontrollresultat kan klarmarkeras via knappen **Klarmarkera kontroll**. När du klarmarkerar ett kontrollresultat ändrar ikonen utseende och blir grå med en grön bock i nedre högra hörnet. Ett resultat behöver bara klarmarkeras en gång vilket innebär att om du exempelvis klarmarkerar ett resultat på ett konto i balansavstämningen, så blir samma resultat även klarmarkerat i delen Transaktionsanalys. Om det sker en förändring som påverkar kontrollresultatet efter att det klarmarkerats, så försvinner klarmarkeringen och ikonen ändrar utseende för att indikera att resultatet måste uppdateras. Läs mer i Automatiska kontroller.
*   **Status checklista:** Denna kolumn visar statusen på kontrollfrågorna på kontot. En grå symbol visar att inga kontrollfrågor har klarmarkerats, en blå symbol visar att några kontrollfrågor har klarmarkerats, och en grön symbol visar att alla kontrollfrågor är klarmarkerade. Symbolen är också en genväg till fliken **Checklista**. För muspekaren över symbolen för att se hur många kontrollfrågor som klarmarkerats.
*   **Klart:** När du är färdig med avstämningen av ett konto ska du klarmarkera det i kolumnen **Klart**. Beroende på var du klickar, kan du sätta status på enstaka konton, kontogrupper eller samtliga konton.
*   **Kvalitetssäkring:** Funktionaliteten för intern kvalitetssäkring, som finns tillgänglig via kolumnen **Kvalitetssäkring**, ger ett stöd för byrån att dokumentera arbetet med kvalitetssäkringen. Efter att ha granskat det arbete som gjorts på ett konto eller en kontogrupp, kan personen som ansvarar för kvalitetssäkringen gå till kolumnen **Kvalitetssäkring** till höger och klicka på ikonen för att ändra status för kontot eller kontogruppen. Det finns två tillgängliga alternativ: **Godkänd** och **Ej godkänd**. För att återställa statusen för ett konto eller en kontogrupp, välj **Återställ status**. När du väljer **Godkänd** för ett konto eller en kontogrupp ändrar dess statusikon i kolumnen **Kvalitetssäkring** färg till grön. På enskilda konton kan du hålla pekaren över ikonen för att visa datum och klockslag för godkännandet, samt kvalitetssäkrarens namn. Om kvalitetssäkraren har tagits bort från redovisningsbyrån kommer han eller hon att visas som **Okänd användare**. När du väljer **Ej godkänd** för ett konto eller en kontogrupp ändrar statusikonen i kolumnen **Kvalitetssäkring** färg till orange och du ges möjlighet att lämna en kommentar. På enskilda konton kan du hålla pekaren över ikonen för att visa datum och klockslag för då statusen sattes, samt kvalitetssäkrarens namn. Om en kommentar har lämnats, så visas denna i sidopanelen. När du väljer **Återställ status** ändrar statusikonen i kolumnen **Kvalitetssäkring** färg till grått och återgår till sitt ursprungliga värde.

## Hur påverkas du?
Du kommer att märka en förbättrad användarupplevelse när du arbetar med balansavstämningar, med nya möjligheter att anpassa vyn och fördjupa dig i detaljer.

## Steg för att använda den uppdaterade funktionen

1.  **Navigera till Balansavstämning:** Öppna Skatt & Bokslut och leta upp funktionen för balansavstämning under **Periodavslut** eller **Årsavslut**.
2.  **Anpassa vyn:** Använd **Dölj/Lägg till kolumn** för att välja vilka kolumner som ska visas.
3.  **Fördjupa dig i detaljer:** Klicka på understrukna belopp för att använda drill down-funktionen och analysera verifikationer i **Kontoanalys**.
4.  **Hantera bilagor och kontroller:** Använd funktionerna för bilagor och automatiska kontroller för att säkerställa noggrannhet.
5.  **Spara ditt arbete:** När du är klar, se till att spara dina ändringar.

## Relaterade artiklar
*   [Kom igång med Skatt & Bokslut]
*   [Att arbeta med bokslut]
*   [Bokslutsverifikationer]
*   [Automatiska kontroller]
