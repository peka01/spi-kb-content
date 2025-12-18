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
updatedAt: '2025-12-18T17:13:27.247Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-18T17:09:26.693Z'
lastLLMUpdateAt: '2025-12-18T17:07:40.951Z'
translationBase:
  en: >-
    # Kom igång med Fortnox-integrationen


    Genom att koppla ihop Spiris Skatt & Bokslut direkt med Fortnox kan du
    smidigt hämta din bokföringsdata via API. Integrationen gör det möjligt att
    både importera data för analys och bokslut samt att skicka tillbaka dina
    bokslutstransaktioner direkt till Fortnox. Detta sparar tid, minskar risken
    för fel och ger dig en helt digital arbetsprocess.


    ## Så här gör du


    ### Koppla Fortnox som datakälla

    Du kan välja Fortnox som källa för din bokföringsdata antingen när du
    startar ett nytt år i startguiden eller via inställningarna.


    1. Gå till **Startguiden** eller navigera till **Underhåll** –
    **Inställningar** – **Importinställningar**.

    2. Välj alternativet **Fortnox**.

    3. Klicka på knappen **Importera från Fortnox**.

    4. Du skickas nu till Fortnox inloggningsportal. Logga in med dina vanliga
    uppgifter för Fortnox och godkänn kopplingen till Spiris.

    5. När kopplingen är klar skapas en säker anslutning (en så kallad token)
    som är giltig i 30 dagar. Denna förnyas automatiskt varje gång du väljer att
    importera eller exportera data.


    ### Importera data

    När anslutningen är upprättad kan du hämta din bokföring direkt till
    plattformen.


    1. Klicka på **Importera från Fortnox** på översiktssidan.

    2. Plattformen hämtar nu verifikationer och saldon. Vid importen skapas
    automatiskt bilagor för **Kundfordringar (konto 1510)** och
    **Leverantörsskulder (konto 2440)** för att underlätta ditt arbete.

    3. Du kan nu använda funktionerna för periodavslut och transaktionsanalys på
    samma sätt som vid en SIE4-import.


    ### Exportera bokslutstransaktioner

    När du är klar med dina justeringar i Skatt & Bokslut kan du skicka tillbaka
    bokslutstransaktionerna till Fortnox som färdiga verifikationer.


    1. Gå till vyn för **Bokslutstransaktioner**.

    2. Klicka på knappen **Exportera bokslutstransaktioner till Fortnox**.

    3. En dialogruta öppnas där du får välja vilken verifikatserie i Fortnox som
    transaktionerna ska bokföras i (exempelvis serie V och S).

    4. Kontrollera att rätt serie är vald och klicka på **Exportera**.

    5. Transaktionerna skickas över och får statusen **Exporterad** i listan.


    ## Tips

    > Om knappen för export är gråmarkerad kan det bero på att din anslutning
    (token) har löpt ut. Håll muspekaren över knappen för att se status. För att
    återansluta klickar du helt enkelt på **Importera från Fortnox** igen, så
    förnyas kopplingen i 30 nya dagar.


    ## Bra att veta

    *   **Automatiska bilagor:** Vid varje import skapas aktuella underlag för
    kundreskontra och leverantörsreskontra automatiskt i plattformen.

    *   **Säkerhet:** Spiris kontrollerar att organisationsnumret i Fortnox
    matchar det företag du arbetar med för att säkerställa att data hamnar rätt.
    Om de inte matchar visas en varning.

    *   **Begränsningar:** Precis som vid filimport finns det begränsningar för
    filstorlek (100 MB) och antal objekt (max 500 kostnadsställen/projekt) för
    att säkerställa hög prestanda.

    *   **Aktivitetslogg:** Du kan följa status för dina överföringar och se
    eventuella felmeddelanden i aktivitetsloggen under systemuppgifter.


    ## Mer information

    - Arbeta med transaktionsanalys

    - Hantera bokslutstransaktioner

    - Inställningar för datakällor
currentVersion: 6
languageUpdatedAt:
  sv: '2025-12-18T17:11:26.330Z'
  en: '2025-12-18T17:11:26.330Z'
metadata:
  solution: Skatt & Bokslut
  area1: general
  targetAudience: []
  tags:
    - update
    - general
  area2: ''
  guidelineVersions:
    writing_guide: 7
    constitution: 1
    tone_voice: 1
  productId: Skatt & Bokslut
---
# Get started with the Fortnox integration

By connecting Spiris Skatt & Bokslut directly with Fortnox, you can seamlessly retrieve your accounting data via API. The integration makes it possible to both import data for analysis and year-end closing, as well as send your year-end transactions back directly to Fortnox. This saves time, reduces the risk of errors, and provides you with a fully digital workflow.

## How to

### Connect Fortnox as a data source
You can choose Fortnox as the source for your accounting data either when starting a new year in the startup wizard or via the settings.

1. Go to the **Startup Wizard** or navigate to **Maintenance** – **Settings** – **Import Settings**.
2. Select the **Fortnox** option.
3. Click the **Import from Fortnox** button.
4. You will now be redirected to the Fortnox login portal. Log in with your regular Fortnox credentials and authorize the connection to Spiris.
5. Once the connection is established, a secure connection (a so-called token) is created, which is valid for 30 days. This is automatically renewed every time you choose to import or export data.

### Import data
Once the connection is established, you can retrieve your accounting data directly to the platform.

1. Click **Import from Fortnox** on the overview page.
2. The platform will now retrieve vouchers and balances. During the import, attachments for **Accounts Receivable (account 1510)** and **Accounts Payable (account 2440)** are automatically created to facilitate your work.
3. You can now use the features for period closing and transaction analysis in the same way as with a SIE4 import.

### Export year-end transactions
When you have finished your adjustments in Skatt & Bokslut, you can send the year-end transactions back to Fortnox as completed vouchers.

1. Go to the **Year-end transactions** view.
2. Click the button **Export year-end transactions to Fortnox**.
3. A dialog box opens where you can choose which voucher series in Fortnox the transactions should be posted to (for example, series V and S).
4. Check that the correct series is selected and click **Export**.
5. The transactions are sent over and receive the status **Exported** in the list.

## Tips
> If the export button is grayed out, it may be because your connection (token) has expired. Hover your mouse over the button to see the status. To reconnect, simply click **Import from Fortnox** again, and the connection will be renewed for another 30 days.

## Good to know
*   **Automatic attachments:** With every import, current supporting documents for accounts receivable and accounts payable are automatically created in the platform.
*   **Security:** Spiri checks that the organization number in Fortnox matches the company you are working with to ensure that data is placed correctly. If they do not match, a warning is displayed.
*   **Limitations:** Just like with file imports, there are limitations on file size (100 MB) and the number of objects (max 500 cost centers/projects) to ensure high performance.
*   **Activity log:** You can follow the status of your transfers and see any error messages in the activity log under system tasks.

## More information
- Work with transaction analysis
- Manage closing transactions
- Data source settings
