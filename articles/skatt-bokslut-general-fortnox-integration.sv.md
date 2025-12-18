---
id: 2oTgOQaCaA0zU4dNcMGw
title: Fortnox integration
slug: general-fortnox-integration
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2025-12-18T12:00:02.117Z'
updatedAt: '2025-12-18T17:09:26.693Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-18T17:09:26.693Z'
lastLLMUpdateAt: '2025-12-18T17:07:40.951Z'
currentVersion: 5
translationBase:
  en: >-
    # Kom igång med Fortnox-integrationen


    ## Översikt

    Nu kan du koppla ihop Spiris Skatt & Bokslut direkt med Fortnox för att
    smidigt hämta din bokföringsdata via API. Integrationen gör det möjligt att
    både importera data för analys och bokslut, samt att skicka tillbaka dina
    bokslutstransaktioner direkt till Fortnox när du är klar. Detta sparar tid
    och minskar risken för fel vid manuell filhantering.


    ## Så här fungerar det


    ### Välj Fortnox som datakälla

    Du kan välja **{{resource:EnumImportSource_lbl_Fortnox}}**som källa för din
    bokföringsdata antingen när du startar ett nytt år eller via
    inställningarna.


    1. Gå till **Startguiden** eller navigera till
    ****{{resource:Menu_title_Maintenance}}**-
    **{{resource:Menu_title_Maintenance_Settings}}** -
    **{{resource:Maintenance_ImportData_hdr_ImportSettings}}****.

    2. Välj alternativet ****{{resource:EnumImportSource_lbl_Fortnox}}****.

    3. Klicka på knappen ****{{resource:Import_imsg_FortnoxImport}}****.

    4. Du skickas nu till Fortnox inloggningsportal. Logga in med dina vanliga
    uppgifter för Fortnox och godkänn kopplingen till Spiris.

    5. När kopplingen är klar skapas en säker anslutning (en så kallad token)
    som är giltig i 30 dagar. Denna förnyas automatiskt varje gång du väljer att
    importera eller exportera data.


    ### Importera data

    När anslutningen är upprättad kan du hämta din bokföring.


    *   Klicka på ****{{resource:Import_imsg_FortnoxImport}}**** på
    översiktssidan.

    *   Plattformen hämtar verifikationer och saldo.

    *   Du kan nu använda funktionerna för periodavslut och transaktionsanalys
    precis som vid en vanlig SIE4-import.


    ### Exportera bokslutstransaktioner

    När du har gjort dina justeringar i Skatt & Bokslut kan du skicka tillbaka
    bokslutstransaktionerna till Fortnox som verifikationer.


    1. Gå till vyn för
    ****{{resource:PdfReport_hdr_Title_Vouchers_ClosingEntries}}****.

    2. Klicka på knappen
    ****{{resource:ClosingTransactionsView_btn_ExportFortnox}}****.

    3. En dialogruta öppnas där du får välja vilken verifikatserie i Fortnox som
    transaktionerna ska bokföras i.

    4. Kontrollera att rätt serie är vald och klicka på
    ****{{resource:Maintenance_ExportData_hdr_Export}}****.

    5. Transaktionerna skickas nu över och får statusen exporterad i listan.


    *Observera: Om kopplingen till Fortnox har löpt ut behöver du göra en ny
    import för att återansluta innan du kan exportera.*


    ### Hantera kopplingen

    Om du behöver byta datakälla eller avbryta kopplingen gör du detta under
    underhållsmenyn.


    *   Gå till *****{{resource:Menu_title_Maintenance}}**-
    **{{resource:Menu_title_Maintenance_Settings}}**-
    **{{resource:Maintenance_ImportData_hdr_ImportSettings}}****..

    *   Här kan du välja att klicka på
    ****{{resource:Maintenance_ImportData_btn_DisconnectFortnoxCompany}}**** för
    att ta bort anslutningen till Fortnox.

    *   Om du vill byta till en annan källa, till exempel en SIE-fil, kan du
    göra det härifrån med samma logik som tidigare.


    ## Bra att veta

    *   **Säkerhet:** Plattformen kontrollerar att organisationsnumret i Fortnox
    matchar det företag du arbetar med i Skatt & Bokslut för att säkerställa att
    data hamnar rätt.

    *   **Begränsningar:** Precis som vid filimport finns det begränsningar för
    filstorlek (100 MB) och antal objekt (t.ex. kostnadsställen) för att
    bibehålla god prestanda.

    *   **Aktivitetslogg:** Du kan se status för dina importer och exporter i
    aktivitetsloggen under systemuppgifter.


    ## Relaterade artiklar

    - [Arbeta med transaktionsanalys]

    - [Hantera bokslutstransaktioner]

    - [Inställningar för datakällor]
languageUpdatedAt:
  en: '2025-12-18T12:23:42.904Z'
  sv: '2025-12-18T12:23:42.904Z'
metadata:
  solution: Skatt & Bokslut
  area1: general
  productId: Skatt & Bokslut
  area2: ''
  guidelineVersions:
    template: 4
    writing_guide: 7
    tone_voice: 1
    constitution: 1
  tags:
    - update
    - general
  targetAudience: []
---
# Kom igång med Fortnox-integrationen

Genom att koppla ihop Spiris Skatt & Bokslut direkt med Fortnox kan du smidigt hämta din bokföringsdata via API. Integrationen gör det möjligt att både importera data för analys och bokslut samt att skicka tillbaka dina bokslutstransaktioner direkt till Fortnox. Detta sparar tid, minskar risken för fel och ger dig en helt digital arbetsprocess.

## Så här gör du

### Koppla Fortnox som datakälla
Du kan välja Fortnox som källa för din bokföringsdata antingen när du startar ett nytt år i startguiden eller via inställningarna.

1. Gå till **Startguiden** eller navigera till **Underhåll** – **Inställningar** – **Importinställningar**.
2. Välj alternativet **Fortnox**.
3. Klicka på knappen **Importera från Fortnox**.
4. Du skickas nu till Fortnox inloggningsportal. Logga in med dina vanliga uppgifter för Fortnox och godkänn kopplingen till Spiris.
5. När kopplingen är klar skapas en säker anslutning (en så kallad token) som är giltig i 30 dagar. Denna förnyas automatiskt varje gång du väljer att importera eller exportera data.

### Importera data
När anslutningen är upprättad kan du hämta din bokföring direkt till plattformen.

1. Klicka på **Importera från Fortnox** på översiktssidan.
2. Plattformen hämtar nu verifikationer och saldon. Vid importen skapas automatiskt bilagor för **Kundfordringar (konto 1510)** och **Leverantörsskulder (konto 2440)** för att underlätta ditt arbete.
3. Du kan nu använda funktionerna för periodavslut och transaktionsanalys på samma sätt som vid en SIE4-import.

### Exportera bokslutstransaktioner
När du är klar med dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutstransaktionerna till Fortnox som färdiga verifikationer.

1. Gå till vyn för **Bokslutstransaktioner**.
2. Klicka på knappen **Exportera bokslutstransaktioner till Fortnox**.
3. En dialogruta öppnas där du får välja vilken verifikatserie i Fortnox som transaktionerna ska bokföras i (exempelvis serie V och S).
4. Kontrollera att rätt serie är vald och klicka på **Exportera**.
5. Transaktionerna skickas över och får statusen **Exporterad** i listan.

## Tips
> Om knappen för export är gråmarkerad kan det bero på att din anslutning (token) har löpt ut. Håll muspekaren över knappen för att se status. För att återansluta klickar du helt enkelt på **Importera från Fortnox** igen, så förnyas kopplingen i 30 nya dagar.

## Bra att veta
*   **Automatiska bilagor:** Vid varje import skapas aktuella underlag för kundreskontra och leverantörsreskontra automatiskt i plattformen.
*   **Säkerhet:** Spiris kontrollerar att organisationsnumret i Fortnox matchar det företag du arbetar med för att säkerställa att data hamnar rätt. Om de inte matchar visas en varning.
*   **Begränsningar:** Precis som vid filimport finns det begränsningar för filstorlek (100 MB) och antal objekt (max 500 kostnadsställen/projekt) för att säkerställa hög prestanda.
*   **Aktivitetslogg:** Du kan följa status för dina överföringar och se eventuella felmeddelanden i aktivitetsloggen under systemuppgifter.

## Mer information
- Arbeta med transaktionsanalys
- Hantera bokslutstransaktioner
- Inställningar för datakällor
