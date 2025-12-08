---
id: article-1764763738003-u3zffq6wc
title: 'Changes for issue #ATO-16945'
slug: general-changes-for-issue-ato-16945-1764763723380
format: md
status: draft
folderId: null
createdAt: '2025-12-03T12:08:58.003Z'
updatedAt: '2025-12-08T13:28:58.136Z'
publishedAt: null
metadata:
  productId: skatt-&-bokslut
  area1: general
  area2: '3934'
  tags:
    - update
    - general
  locale: sv-se
---
Här är din kunskapsbasartikel:

# Ny integrationsmöjlighet: Förbereder för import från Fortnox / New Integration Capability: Preparing for Fortnox Import

## Översikt / Overview
**SV:** Denna artikel beskriver den initiala utvecklingen för att möjliggöra import av data från Fortnox till vår tjänst. Med denna uppdatering läggs grunden för en framtida, djupare integration som kommer att förenkla datahanteringen för dig. Denna version fokuserar på att etablera den tekniska infrastrukturen i bakgrunden.

**EN:** This article describes the initial development to enable data import from Fortnox into our service. With this update, the foundation is laid for a future, deeper integration that will simplify data management for you. This version focuses on establishing the technical infrastructure in the background.

## Förutsättningar / Prerequisites
**SV:** För denna initiala uppdatering krävs inga specifika åtgärder från din sida. När den fullständiga Fortnox-integrationen släpps och blir tillgänglig i användargränssnittet kommer du att behöva:
- Ett aktivt Fortnox-konto.
- Rätt behörigheter för att koppla Visma-tjänsten till ditt Fortnox-konto.

**EN:** For this initial update, no specific actions are required from your side. When the full Fortnox integration is released and becomes available in the user interface, you will need:
- An active Fortnox account.
- The correct permissions to connect the Visma service to your Fortnox account.

## Steg / Steps
**SV:** Denna uppdatering etablerar den tekniska grunden för Fortnox-integrationen i bakgrunden. I denna version finns inga direkta användaråtgärder tillgängliga i användargränssnittet för att konfigurera eller utföra en import.

Detaljerade steg för hur du konfigurerar och använder Fortnox-importfunktionen kommer att tillhandahållas i en kommande release när integrationen är fullt utvecklad, säkerställd med tokenkryptering, och tillgänglig i användargränssn


---

## Update: Fortnox Integration - Version 1.0

This update introduces the integration with Fortnox, allowing users to import accounting data and export closing entries.

### Overview
This section details the new Fortnox integration, covering its setup, data import process, and export capabilities for closing entries.

### Prerequisites
- Access to your Fortnox account credentials.
- An active S&B (Skatt & Bokslut) account.

### Steps

#### 1. Initial Setup and Data Import

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
        *   One linked to Account 1510 (Kundfordingar - Accounts receivable ledger).
        *   One linked to Account 2440 (Leverantörsskulder - Accounts payable ledger).
    *   Additional appendices may be added in future releases.

4.  **Validations:**
    *   The import process will utilize the same validations as SIE4, including checks for:
        *   Organization number validity.
        *   File size limits (100 MB).
        *   Automatic filling of missing voucher series.
        *   Skipping objects if more than 500 are present.

5.  **Overview Page:**
    *   A new text string, "Import from Fortnox," is now available on the overview page.

#### 2. Period Closing and Transaction Analysis

*   Period closing and Transaction Analysis are now supported for the Fortnox data source, mirroring the functionality available for SIE4 imports.

#### 3. Exporting Closing Entries

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

#### 4. Maintenance and Activity Log

1.  **Data Source Management:**
    *   Fortnox is now listed as a Data Source under Maintenance > Settings.
    *   You can change your data source here, using the same logic as applied to SIE4.

2.  **Activity Log:**
    *   Fortnox has been added to the import messages within the Activity Log / System Tasks.

### Related Articles
*   [Period Closing in S&B]
*   [Transaction Analysis Guide]
*   [Managing Data Sources]
