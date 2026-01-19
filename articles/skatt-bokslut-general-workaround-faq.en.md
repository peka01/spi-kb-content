---
id: PQBQCoo7XyaqMLcLpaJi
title: Workaround (Faq)
slug: general-workaround-faq
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2026-01-15T12:40:31.691Z'
updatedAt: '2026-01-19T13:39:09.717Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
languageUpdatedAt:
  sv: '2026-01-15T12:40:31.691Z'
  en: '2026-01-15T12:40:31.691Z'
translationBase:
  en: >-
    ## Hur kan jag lägga till eller ändra information för föregående år?


    För att din årsredovisning ska vara komplett och följa årsredovisningslagen
    (ÅRL) måste den innehålla jämförelsetal från föregående år. Om dessa siffror
    saknas i din bokföring eller om det har blivit fel vid importen, kan du lösa
    det på ett smidigt sätt direkt i vår ekonomiplattform.


    ### Föregående år saknas helt i Skatt & Bokslut

    Om du är ny användare av **Skatt & Bokslut** och inte har hunnit lägga in
    tidigare räkenskapsår, eller om du har importerat data där historiken
    saknas, finns det två sätt att lösa detta:


    #### Alternativ 1: Skapa föregående år manuellt (Rekommenderas)

    Detta är en effektiv metod för att få in rätt siffror i årsredovisningen
    utan att behöva ändra i din löpande bokföring.


    **Viktigt:** Denna metod kräver att du nollställer ditt nuvarande arbete i
    **Skatt & Bokslut**. Om du redan har gjort justeringar i innevarande år
    kommer dessa att försvinna.


    1. Gå till **Underhåll - Inställningar** och välj **Nollställ uppgifter**.
    Bekräfta för att rensa all inmatad data i den aktuella perioden.

    2. Gå igenom startguiden och välj **Manuell inmatning** som datakälla.

    3. Skapa det saknade föregående året och mata in bokföringen för det året
    manuellt.

    4. När du är klar, välj **Lås** för det föregående året.

    5. Gå till **Underhåll - Inställningar - Datakälla** och välj din vanliga
    datakälla (till exempel **Spiris Bokföring** eller **SIE-fil**) och klicka
    på **Ändra datakälla**.

    6. Ignorera meddelandet om att data kommer att raderas och genomför importen
    för innevarande år.


    Nu finns dina manuellt inmatade uppgifter för föregående år kvar som
    jämförelsetal, medan siffrorna för det aktuella året hämtas automatiskt.


    #### Alternativ 2: Komplettera i din bokföring

    1. Skapa det saknade räkenskapsåret direkt i din bokföring.

    2. Bokför föregående års siffror (exempelvis via en samlingsverifikation).

    3. Gör en ny import till **Skatt & Bokslut** för den nyskapade perioden.


    ### Bokföringen är fel i föregående år

    Om du får felmeddelanden som till exempel "Föregående år balanserar inte",
    innebär det att föregående år inte kan importeras korrekt.


    *   **Alternativ 1:** Åtgärda problemet direkt i den löpande bokföringen och
    gör sedan en ny import.

    *   **Alternativ 2:** Använd samma metod som beskrivs under "Alternativ 1:
    Skapa föregående år manuellt" ovan. Genom att nollställa och välja manuell
    inmatning kan du själv skriva in de korrekta balans- och resultaträkningarna
    för föregående år och sedan låsa dem innan du byter tillbaka till din
    automatiska datakälla.


    ### Tips för ett smidigare bokslut

    För att spara tid och undvika onödigt dubbelarbete är det en god vana att
    alltid kontrollera att föregående år ser rätt ut i årsredovisningen
    **innan** du påbörjar arbetet med årets balansavstämningar. På så sätt
    slipper du nollställa funktionerna när du redan är halvvägs klar med årets
    siffror!


    **Relaterade länkar:**

    *   Skapa årsredovisning

    *   Importera data från SIE-fil
currentVersion: 1
updatedByName: Per Karlsson
updatedBy: Per.Karlsson@visma.com
metadata:
  area1: general
  solution: Skatt & Bokslut
  tags:
    - update
    - general
    - faq
  productId: Skatt & Bokslut
  guidelineVersions:
    tone_voice: 1
    news: 3
    getting_started: 2
    article_matching: 1
    constitution: 1
    instruction: 7
    faq: 1
  targetAudience: []
  visibility: public
  area2: ''
---
## How can I add or change information for the previous year?

To ensure your annual report is complete and complies with the Annual Accounts Act (ÅRL), it must include comparative figures from the previous year. If these figures are missing from your accounting or if an error occurred during import, you can easily resolve this directly in our financial platform.

### Previous year is completely missing in Tax & Year-end Closing
If you are a new user of **Tax & Year-end Closing** and have not yet added previous financial years, or if you have imported data where the history is missing, there are two ways to resolve this:

#### Option 1: Create the previous year manually (Recommended)
This is an effective method for getting the correct figures into the annual report without having to change your ongoing bookkeeping.

**Important:** This method requires you to reset your current work in **Tax & Year-end Closing**. If you have already made adjustments in the current year, these will be lost.

1. Go to **Maintenance - Settings** and select **Reset data**. Confirm to clear all entered data in the current period.
2. Go through the startup wizard and select **Manual entry** as the data source.
3. Create the missing previous year and enter the accounting for that year manually.
4. When finished, select **Lock** for the previous year.
5. Go to **Maintenance - Settings - Data Source** and select your usual data source (for example, **Spiri Accounting** or **SIE file**) and click **Change data source**.
6. Ignore the message stating that data will be deleted and proceed with the import for the current year.

Your manually entered data for the previous year will now remain as comparative figures, while the figures for the current year are retrieved automatically.

#### Option 2: Supplement in your bookkeeping
1. Create the missing financial year directly in your bookkeeping.
2. Record the previous year's figures (for example, via a summary journal entry).
3. Perform a new import to **Tax & Year-end Closing** for the newly created period.

### The accounting is incorrect for the previous year
If you receive error messages such as "Previous year does not balance," it means the previous year cannot be imported correctly.

*   **Option 1:** Fix the problem directly in the ongoing bookkeeping and then perform a new import.
*   **Option 2:** Use the same method described under "Option 1: Create the previous year manually" above. By resetting and selecting manual entry, you can enter the correct balance sheets and income statements for the previous year yourself and then lock them before switching back to your automatic data source.

### Tips for a smoother year-end closing
To save time and avoid unnecessary duplication of work, it is good practice to always check that the previous year looks correct in the annual report **before** you begin working on the current year's balance reconciliations. This way, you avoid having to reset functions when you are already halfway through the current year's figures!

**Related links:**
*   Create annual report
*   Import data from SIE file
