---
id: tmVg5WVpoOTrypYJN80d
title: Vanliga frågor om export
slug: vanliga-fragor-om-export
languages:
  - sv
  - en
format: md
status: test
folderId: vZ6IMwn3WcrkxEemzXO8
createdAt: '2026-01-08T14:13:44.416Z'
updatedAt: '2026-01-19T15:04:09.088Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
languageUpdatedAt:
  sv: '2026-01-19T15:03:04.949Z'
  en: '2026-01-19T15:03:04.949Z'
updatedBy: Per.Karlsson@visma.com
currentVersion: 7
translationBase:
  en: >
    # Vanliga frågor om exporter


    Här hittar du information om hur du använder den nya funktionen för att
    exportera dokumentation i Skatt & Bokslut. Detta är ett smidigt sätt att
    arkivera företagets underlag och säkerställa att du följer lagkrav på
    lagring av data.


    ### Hur exporterar jag dokumentation för flera räkenskapsår?

    För att skapa en samlad arkivfil med din dokumentation gör du följande:


    1. Gå till menyn **Underhåll** och välj
    ****{{resource:ExportData_title_ExportData}}****.

    2. Välj alternativet ****{{resource:ExportData_option_Documentation}}****.

    3. I rullistan för ****{{resource:Startpage_hdr_FinancialYear}}**** markerar
    du de år du vill inkludera i exporten. Du kan välja ett eller flera år
    samtidigt genom att bocka i rutorna.

    4. Klicka på knappen ****{{resource:Maintenance_ExportData_hdr_Export}}****.

    5. En förloppsindikator visas medan filen skapas. När exporten är klar får
    du en notis och kan ladda ner en ZIP-fil som innehåller din dokumentation.


    ### Vad innehåller den exporterade ZIP-filen?

    Exporten är utformad för att vara tydlig och enkel att navigera i. När du
    packar upp ZIP-filen möts du av en strukturerad mapphierarki:


    *   **Huvudmappar**: Uppdelade per räkenskapsår.

    *   **Undermappar**: Varje år innehåller mappar för de specifika perioderna.

    *   **Dokument**: I varje periodmapp hittar du PDF-filer för alla relevanta
    dokument, såsom avstämningar, skatteberäkningar och
    årsredovisningshandlingar.


    ### Varför ingår inte alla perioder i min export?

    För att hålla exporten relevant och optimerad inkluderas endast perioder där
    det finns aktiv data. En period kommer med i exporten om den innehåller
    något av följande:

    *   Genomförda autokontroller.

    *   Konton som markerats som klara.

    *   Minst en användarkommentar.


    Om en period är helt tom och ingen aktivitet registrerats, kommer ingen mapp
    att skapas för just den perioden.


    ### Vad händer om något går fel under exporten?

    Plattformen har en inbyggd felhantering för att säkerställa att du får ut så
    mycket data som möjligt:


    *   **Delvis lyckad export**: Om en enskild PDF inte kan skapas (exempelvis
    på grund av ett oväntat formatfel i ett dokument), kommer exporten ändå att
    slutföras. Du får då en notis om att exporten är "delvis lyckad". I
    ZIP-filen ersätts det felaktiga dokumentet med en informationssida som
    förklarar vilket dokument som saknas och varför.

    *   **Bakgrundshantering**: Exporten körs som en bakgrundsaktivitet. Det
    betyder att du kan fortsätta arbeta i Spiris medan filen förbereds.


    ### Vilka användare kan använda funktionen?

    Denna funktion är tillgänglig för alla användare i Skatt & Bokslut,
    inklusive dig som har ett abonnemang med läsrättigheter eller arbetar i ett
    icke-interaktivt läge. Det gör det enkelt att säkra din data även om du
    planerar att avsluta ett uppdrag eller byta abonnemangsform.


    **Relaterade länkar:**

    *   [Läs mer om arkivering av räkenskapsår](#)

    *   [Spara underlag enligt bokföringslagen](#)
updatedByName: Per Karlsson
metadata:
  locale: sv-se
  targetAudience: []
  solution: Skatt & Bokslut
  productId: Skatt & Bokslut
  guidelineVersions:
    constitution: 1
    article_matching: 1
    instruction: 7
    faq: 1
    getting_started: 2
    news: 3
    tone_voice: 1
  tags:
    - update
    - general
    - faq
  area2: ''
  area1: general
  visibility: public
  cshAnchors: []
---
# Frequently asked questions about exports

Here you’ll find information on how to use the new feature for exporting documentation in Skatt & Bokslut (Tax & Balance Sheet). This is a convenient way to archive your company’s records and ensure you comply with legal requirements for data storage.

### How do I export documentation for multiple accounting years?
To create a consolidated archive file with your documentation, follow these steps:

1. Go to the **Maintenance** menu and select ****{{resource:ExportData_title_ExportData}}****.
2. Select the option ****{{resource:ExportData_option_Documentation}}****.
3. In the dropdown list for ****{{resource:Startpage_hdr_FinancialYear}}****, select the years you want to include in the export. You can select one or more years simultaneously by checking the boxes.
4. Click the button ****{{resource:Maintenance_ExportData_hdr_Export}}****.
5. A progress indicator will appear while the file is being created. Once the export is complete, you will receive a notification and can download a ZIP file containing your documentation.

### What does the exported ZIP file contain?

The export is designed to be clear and easy to navigate. When you extract the ZIP file, you will find a structured folder hierarchy:

*   **Main Folders**: Divided by accounting year.
*   **Subfolders**: Each year contains folders for the specific periods.
*   **Documents**: In each period folder, you will find PDF files for all relevant documents, such as balance sheets, tax calculations, and annual report documents.

### Why are not all periods included in my export?

To keep the export relevant and optimized, only periods with active data are included. A period will be included in the export if it contains any of the following:
*   Completed auto-checks.
*   Accounts marked as complete.
*   At least one user comment.

If a period is completely empty and no activity has been recorded, no folder will be created for that period.

### What happens if something goes wrong during the export?

The platform has built-in error handling to ensure you get as much data as possible:

*   **Partially Successful Export**: If a single PDF cannot be created (for example, due to an unexpected format error in a document), the export will still complete. You will then receive a notification that the export is “partially successful”. In the ZIP file, the incorrect document will be replaced with an information page explaining which document is missing and why.
*   **Background Processing**: The export runs as a background task. This means you can continue working in Spiris while the file is being prepared.

### Which users can use the feature?

This feature is available to all users in Skatt & Bokslut, including those with read permissions and those working in a non-interactive mode. It makes it easy to secure your data even if you plan to end an assignment or change your subscription form.

**Related Links:**

*   [Read more about archiving accounting years](#)
*   [Save records according to the Swedish Accounting Act](#)
