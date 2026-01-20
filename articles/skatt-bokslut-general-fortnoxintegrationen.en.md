---
id: yh0nBPvwjnP2j2EjpLbK
title: Fortnoxintegrationen
slug: general-fortnoxintegrationen
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2026-01-20T14:30:58.465Z'
updatedAt: '2026-01-20T14:37:56.668Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
translationBase:
  en: >-
    # Hantera Fortnox-integrationen i
    **{{resource:common_product_name_variable_taxation_year_end_closing}}**


    Genom att koppla samman Spiris Skatt & Bokslut med Fortnox kan du arbeta mer
    effektivt och säkert med ditt bokslut. Integrationen gör det möjligt att
    hämta bokföringsdata direkt via ett API och skicka tillbaka
    bokslutstransaktioner utan att behöva hantera SIE-filer manuellt. Detta
    minskar risken för fel och sparar värdefull tid.


    ## Så här gör du


    ### Anslut Fortnox som datakälla

    Du kan välja Fortnox som datakälla antingen när du startar ett nytt uppdrag
    i **Startguiden** eller genom att ändra inställningarna för ett befintligt
    uppdrag.


    1. Gå till ****{{resource:Menu_title_Maintenance}}**** –
    ****{{resource:Menu_title_Maintenance_Settings}}**** – **Datakälla**.

    2. Välj **Fortnox** i listan över tillgängliga datakällor.

    3. Klicka på knappen **Importera från Fortnox**.

    4. Du skickas nu till Fortnox inloggningsportal. Logga in med dina vanliga
    uppgifter för Fortnox och godkänn att Spiris får läsa och skriva data.

    5. När kopplingen är klar skickas du tillbaka till Skatt & Bokslut och
    importen påbörjas.


    ### Importera data och automatiska bilagor

    Varje gång du väljer att hämta data från Fortnox synkroniseras bokföringen.
    Integrationen stödjer även automatisk hantering av vissa bilagor:


    *   **Bokföringsdata:** All data importeras på samma sätt som vid en
    SIE4-import, vilket innebär att du kan använda funktioner som
    periodavstämning och transaktionsanalys precis som vanligt.

    *   **Automatiska bilagor:** Vid import skapar plattformen automatiskt
    bilagor för **Kundfordringar (konto 1510)** och **Leverantörsskulder (konto
    2440)** baserat på informationen i Fortnox.


    ### Exportera bokslutstransaktioner till Fortnox

    När du har gjort dina justeringar i Skatt & Bokslut kan du skicka tillbaka
    bokslutstransaktionerna (V- och S-verifikationer) direkt till Fortnox.


    1. Gå till vyn för export av data.

    2. Välj alternativet **Exportera bokslutstransaktioner till Fortnox**.

    3. En dialogruta visas där du får välja vilken **Verifikationsserie** i
    Fortnox som transaktionerna ska bokföras i.

    4. Klicka på **Exportera**. Transaktionerna skickas nu direkt till Fortnox
    bokföring.


    ## Tips

    > **Håll kopplingen vid liv:** Din inloggning (token) mot Fortnox är giltig
    i 30 dagar. Varje gång du gör en import eller export förnyas dessa 30 dagar
    automatiskt. Om knappen för export är gråmarkerad kan det bero på att
    kopplingen gått ut – gör då en ny import för att aktivera anslutningen igen.


    ## Mer information

    - **Periodavstämning**

    - **Arbeta med transaktionsanalys**

    - **Skapa och hantera bilagor**
updatedBy: Per.Karlsson@visma.com
currentVersion: 3
updatedByName: Per Karlsson
languageUpdatedAt:
  sv: '2026-01-20T14:35:23.269Z'
  en: '2026-01-20T14:35:23.269Z'
metadata:
  solution: Skatt & Bokslut
  productId: Skatt & Bokslut
  tags:
    - update
    - general
    - instruction
  visibility: public
  targetAudience: []
  area1: general
  area2: ''
  guidelineVersions:
    news: 3
    getting_started: 2
    instruction: 7
    constitution: 1
    faq: 1
    tone_voice: 1
    article_matching: 1
---
# Manage the Fortnox integration in **{{resource:common_product_name_variable_taxation_year_end_closing}}**

By connecting Spiris Tax & Year-end Closing with Fortnox, you can work more efficiently and securely with your year-end closing. The integration makes it possible to retrieve accounting data directly via an API and send back year-end transactions without having to handle SIE files manually. This reduces the risk of errors and saves valuable time.

## How to do it

### Connect Fortnox as a data source
You can choose Fortnox as a data source either when starting a new engagement in the **Start Guide** or by changing the settings for an existing engagement.

1. Go to ****{{resource:Menu_title_Maintenance}}**** – ****{{resource:Menu_title_Maintenance_Settings}}**** – **Data source**.
2. Select **Fortnox** from the list of available data sources.
3. Click the **Import from Fortnox** button.
4. You will now be redirected to the Fortnox login portal. Log in with your usual Fortnox credentials and authorize Spiris to read and write data.
5. Once the connection is complete, you will be sent back to Tax & Year-end Closing and the import will begin.

### Import data and automatic schedules
Every time you choose to retrieve data from Fortnox, the accounting is synchronized. The integration also supports automatic handling of certain schedules:

*   **Accounting data:** All data is imported in the same way as with a SIE4 import, which means you can use features such as period reconciliation and transaction analysis as usual.
*   **Automatic schedules:** Upon import, the platform automatically creates schedules for **Accounts receivable (account 1510)** and **Accounts payable (account 2440)** based on the information in Fortnox.

### Export year-end transactions to Fortnox
