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
# Get started with the Fortnox integration

## Overview
Now you can connect Spiris Tax & Year-end directly with Fortnox to seamlessly retrieve your accounting data via API. The integration makes it possible to both import data for analysis and year-end, as well as send back your year-end transactions directly to Fortnox when you are finished. This saves time and reduces the risk of errors during manual file handling.

## How it works

### Select Fortnox as Data Source
You can select **{{resource:EnumImportSource_lbl_Fortnox}}** as the source for your accounting data either when you start a new year or via the settings.1. Go to the **Getting Started Guide** or navigate to ****{{resource:Menu_title_Maintenance}}**- **{{resource:Menu_title_Maintenance_Settings}}** - **{{resource:Maintenance_ImportData_hdr_ImportSettings}}****.
2. Select the option ****{{resource:EnumImportSource_lbl_Fortnox}}****.
3. Click the button ****{{resource:Import_imsg_FortnoxImport}}****.
4. You will now be redirected to the Fortnox login portal. Log in with your regular Fortnox credentials and authorize the connection to Spiris.
5. Once the connection is established, a secure connection (a so-called token) is created, which is valid for 30 days. This is automatically renewed every time you choose to import or export data.### Import data
Once the connection is established, you can retrieve your accounting.

*   Click ****{{resource:Import_imsg_FortnoxImport}}**** on the overview page.
*   The platform retrieves vouchers and balances.
*   You can now use the functions for period closing and transaction analysis just like with a standard SIE4 import.

### Export year-end transactions
Once you have made your adjustments in Tax & Year-end, you can send the year-end transactions back to Fortnox as vouchers.

1. Go to the view for ****{{resource:PdfReport_hdr_Title_Vouchers_ClosingEntries}}****.
2. Click the button ****{{resource:ClosingTransactionsView_btn_ExportFortnox}}****.
3. A dialog box opens where you can choose which voucher series in Fortnox the transactions should be posted to.
4. Check that the correct series is selected and click ****{{resource:Maintenance_ExportData_hdr_Export}}****.
5. The transactions are now sent over and receive the status "exported" in the list.

*Note: If the connection to Fortnox has expired, you need to perform a new import to reconnect before you can export.*

### Manage the connection
If you need to change the data source or cancel the connection, you do this under the maintenance menu.

*   Go to *****{{resource:Menu_title_Maintenance}}**- **{{resource:Menu_title_Maintenance_Settings}}**- **{{resource:Maintenance_ImportData_hdr_ImportSettings}}****..
*   Here you can choose to click ****{{resource:Maintenance_ImportData_btn_DisconnectFortnoxCompany}}**** to remove the connection to Fortnox.
*   If you want to switch to another source, for example a SIE file, you can do it from here using the same logic as before.

## Good to know
*   **Security:** The platform checks that the organization number in Fortnox matches the company you are working with in Tax & Year-end to ensure that data ends up in the right place.
*   **Limitations:** Just like with file imports, there are limitations on file size (100 MB) and the number of objects (e.g., cost centers) to maintain good performance.
*   **Activity log:** You can see the status of your imports and exports in the activity log under system tasks.

## Related articles
- [Working with transaction analysis]
- [Managing year-end transactions]
- [Data source settings]
## Related articles
- [Working with transaction analysis]
- [Managing year-end transactions]
- [Data source settings]
