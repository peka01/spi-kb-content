---
id: article-1764763738003-u3zffq6wc
title: 'Changes for issue #ATO-16945'
slug: general-changes-for-issue-ato-16945-1764763723380
format: md
status: draft
folderId: null
createdAt: '2025-12-03T12:08:58.003Z'
updatedAt: '2025-12-09T08:44:26.448Z'
publishedAt: null
pendingReview: true
lastLLMUpdateAt: '2025-12-09T08:44:26.432Z'
reviewedAt: null
metadata:
  productId: skatt-&-bokslut
  area1: general
  area2: '3934'
  tags:
    - update
    - general
  locale: sv-se
---
# Ny integrationsmöjlighet: Förbereder för och konfigurerar Fortnox-import / New Integration Capability: Preparing for and Configuring Fortnox Import

## Översikt / Overview
**SV:** Denna artikel beskriver utvecklingen för att möjliggöra import av data från Fortnox till vår tjänst. Med denna uppdatering läggs grunden för en djupare integration som förenklar datahanteringen. Artikeln täcker den initiala tekniska infrastrukturen, installation, processen för dataimport, exportmöjligheter för bokslutsposter samt underhåll.

**EN:** This article describes the development to enable data import from Fortnox into our service. With this update, the foundation is laid for a deeper integration that simplifies data management. The article covers the initial technical infrastructure, setup, data import process, export capabilities for closing entries, and maintenance.

## Förutsättningar / Prerequisites
**SV:**
- Tillgång till dina Fortnox-kontouppgifter.
- Ett aktivt S&B (Skatt & Bokslut)-konto.
- För den initiala uppdateringen krävdes inga specifika åtgärder från din sida. När den fullständiga Fortnox-integrationen släpptes och blev tillgänglig i användargränssnittet behövde du:
    - Ett aktivt Fortnox-konto.
    - Rätt behörigheter för att koppla Visma-tjänsten till ditt Fortnox-konto.

**EN:**
- Access to your Fortnox account credentials.
- An active S&B (Skatt & Bokslut) account.
- For the initial update, no specific actions were required from your side. When the full Fortnox integration was released and became available in the user interface, you needed:
    - An active Fortnox account.
    - The correct permissions to connect the Visma service to your Fortnox account.

## Steg / Steps

### 1. Initial Setup and Data Import
**SV:**
1.  **Startguide:**
    *   Ett nytt alternativ, "Fortnox", har lagts till som den femte datakällan i Startguiden.
    *   Detta möjliggör import av redovisningsdata från Fortnox via API:et.
2.  **Fortnox-inloggning och Token:**
    *   När du väljer att importera från Fortnox, kommer du att omdirigeras till Fortnox inloggningsportal.
    *   Logga in med dina Fortnox-uppgifter.
    *   Efter lyckad inloggning genereras en token, giltig i 30 dagar.
    *   Alla efterföljande import- eller exportåtgärder inom dessa 30 dagar kommer att uppdatera token för ytterligare 30 dagar från det datumet.
3.  **Dataimport och Bilagor:**
    *   Vid import av data från Fortnox skapas automatiskt två bilagor:
        *   En kopplad till konto 1510 (Kundfordringar).
        *   En kopplad till konto 2440 (Leverantörsskulder).
    *   Ytterligare bilagor kan komma att läggas till i framtida versioner.
4.  **Valideringar:**
    *   Importprocessen kommer att använda samma valideringar som SIE4, inklusive kontroller för:
        *   Organisationsnummerns giltighet.
        *   Filstorleksgränser (100 MB).
        *   Automatisk ifyllnad av saknade verifikatserier.
        *   Hoppa över objekt om fler än 500 finns.
5.  **Översiktssida:**
    *   En ny textsträng, "Importera från Fortnox", finns nu tillgänglig på översiktssidan.

**EN:**
1.  **Start Guide:**
    *   A new option, "Fortnox," has been added as the fifth data source in the Start Guide.
    *   This allows for the import of accounting data from Fortnox via the API.
2.  **Fortnox Login and Token:**
    *   When you choose to import from Fortnox, you will be redirected to the Fortnox login portal.
    *   Log in using your Fortnox credentials.
    *   Upon successful login, a token will be generated, valid for 30 days.
    *   Any subsequent import or export action within these 30 days will refresh the token for another 30 days from that date.
3.  **Data Import and Appendices:**
    *   When importing data from Fortnox, two appendices will be automatically created:
        *   One linked to Account 1510 (Accounts receivable ledger).
        *   One linked to Account 2440 (Accounts payable ledger).
    *   Additional appendices may be added in future releases.
4.  **Validations:**
    *   The import process will utilize the same validations as SIE4, including checks for:
        *   Organization number validity.
        *   File size limits (100 MB).
        *   Automatic filling of missing voucher series.
        *   Skipping objects if more than 500 are present.
5.  **Overview Page:**
    *   A new text string, "Import from Fortnox," is now available on the overview page.

### 2. Period Closing and Transaction Analysis
**SV:** Periodavslut och Transaktionsanalys stöds nu för Fortnox som datakälla, vilket speglar funktionaliteten som är tillgänglig för SIE4-importer.

**EN:** Period closing and Transaction Analysis are now supported for the Fortnox data source, mirroring the functionality available for SIE4 imports.

### 3. Exporting Closing Entries
**SV:**
1.  **Exportfunktionalitet:**
    *   Ett nytt alternativ, "Exportera bokslutsposter till Fortnox (utan bilagor)", är tillgängligt.
    *   Att klicka på detta alternativ öppnar ett modal-fönster.
2.  **Val av Verifikatserie:**
    *   Inom modal-fönstret kan du välja önskad verifikatserie i Fortnox för dina V- och S-verifikat. En rullgardinsmeny med tillgängliga verifikatserier från Fortnox presenteras.
3.  **Initiera Export:**
    *   Att klicka på "Exportera" i modal-fönstret påbörjar exportprocessen.
4.  **Hantering av Tokenförlust:**
    *   Om din Fortnox-token har gått ut eller förlorats, kommer exportknappen att vara inaktiverad.
    *   En tooltip kommer att visa meddelandet: "Du har förlorat din token, för att fortsätta importera igen."

**EN:**
1.  **Export Functionality:**
    *   A new option, "Export closing entries to Fortnox (without attachments)," is available.
    *   Clicking this option will open a modal window.
2.  **Voucher Series Selection:**
    *   Within the modal, you can select the desired voucher series in Fortnox for your V and S vouchers. A dropdown list of available voucher series from Fortnox will be presented.
3.  **Initiating Export:**
    *   Clicking "Export" in the modal will begin the export process.
4.  **Token Loss Handling:**
    *   If your Fortnox token has expired or been lost, the export button will be disabled.
    *   A tooltip will display the message: "You have lost your token, to proceed import again."

### 4. Maintenance and Activity Log
**SV:**
1.  **Hantering av Datakällor:**
    *   Fortnox är nu listat som en Datakälla under Underhåll > Inställningar.
    *   Du kan ändra din datakälla här, med samma logik som tillämpas på SIE4.
2.  **Aktivitetslogg:**
    *   Fortnox har lagts till i importmeddelandena inom Aktivitetslogg / Systemuppgifter.

**EN:**
1.  **Data Source Management:**
    *   Fortnox is now listed as a Data Source under Maintenance > Settings.
    *   You can change your data source here, using the same logic as applied to SIE4.
2.  **Activity Log:**
    *   Fortnox has been added to the import messages within the Activity Log / System Tasks.

## Relaterade artiklar / Related Articles
**SV:**
- [Periodavslut i S&B]
- [Guide för Transaktionsanalys]
- [Hantering av Datakällor]

**EN:**
- [Period Closing in S&B]
- [Transaction Analysis Guide]
- [Managing Data Sources]
