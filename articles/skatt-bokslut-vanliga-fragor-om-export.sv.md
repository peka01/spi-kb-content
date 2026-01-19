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
# Vanliga frågor om exporter

Här hittar du information om hur du använder den nya funktionen för att exportera dokumentation i Skatt & Bokslut. Detta är ett smidigt sätt att arkivera företagets underlag och säkerställa att du följer lagkrav på lagring av data.

### Hur exporterar jag dokumentation för flera räkenskapsår?
För att skapa en samlad arkivfil med din dokumentation gör du följande:

1. Gå till menyn **Underhåll** och välj ****{{resource:ExportData_title_ExportData}}****.
2. Välj alternativet ****{{resource:ExportData_option_Documentation}}****.
3. I rullistan för ****{{resource:Startpage_hdr_FinancialYear}}**** markerar du de år du vill inkludera i exporten. Du kan välja ett eller flera år samtidigt genom att bocka i rutorna.
4. Klicka på knappen ****{{resource:Maintenance_ExportData_hdr_Export}}****.
5. En förloppsindikator visas medan filen skapas. När exporten är klar får du en notis och kan ladda ner en ZIP-fil som innehåller din dokumentation.

### Vad innehåller den exporterade ZIP-filen?
Exporten är utformad för att vara tydlig och enkel att navigera i. När du packar upp ZIP-filen möts du av en strukturerad mapphierarki:

*   **Huvudmappar**: Uppdelade per räkenskapsår.
*   **Undermappar**: Varje år innehåller mappar för de specifika perioderna.
*   **Dokument**: I varje periodmapp hittar du PDF-filer för alla relevanta dokument, såsom avstämningar, skatteberäkningar och årsredovisningshandlingar.

### Varför ingår inte alla perioder i min export?
För att hålla exporten relevant och optimerad inkluderas endast perioder där det finns aktiv data. En period kommer med i exporten om den innehåller något av följande:
*   Genomförda autokontroller.
*   Konton som markerats som klara.
*   Minst en användarkommentar.

Om en period är helt tom och ingen aktivitet registrerats, kommer ingen mapp att skapas för just den perioden.

### Vad händer om något går fel under exporten?
Plattformen har en inbyggd felhantering för att säkerställa att du får ut så mycket data som möjligt:

*   **Delvis lyckad export**: Om en enskild PDF inte kan skapas (exempelvis på grund av ett oväntat formatfel i ett dokument), kommer exporten ändå att slutföras. Du får då en notis om att exporten är "delvis lyckad". I ZIP-filen ersätts det felaktiga dokumentet med en informationssida som förklarar vilket dokument som saknas och varför.
*   **Bakgrundshantering**: Exporten körs som en bakgrundsaktivitet. Det betyder att du kan fortsätta arbeta i Spiris medan filen förbereds.

### Vilka användare kan använda funktionen?
Denna funktion är tillgänglig för alla användare i Skatt & Bokslut, inklusive dig som har ett abonnemang med läsrättigheter eller arbetar i ett icke-interaktivt läge. Det gör det enkelt att säkra din data även om du planerar att avsluta ett uppdrag eller byta abonnemangsform.

**Relaterade länkar:**
*   [Läs mer om arkivering av räkenskapsår](#)
*   [Spara underlag enligt bokföringslagen](#)
