---
id: article-1764775811669-se2s8bnw6
title: Fortnox som datakälla
slug: fortnox-som-datakalla
format: md
status: draft
folderId: folder-1764579275638
createdAt: '2025-12-03T15:30:11.669Z'
updatedAt: '2025-12-08T13:28:54.303Z'
publishedAt: null
metadata:
  productId: Skatt & Bokslut
  area1: ''
  area2: ''
  solution: Skatt & Bokslut
  tags:
    - import
    - datakälla
  locale: sv
---
# Förbättringar för Fortnox-import i Visma Skatt & Bokslut

## Översikt
Denna artikel beskriver de senaste förbättringarna och nya funktionerna för integrationen med Fortnox i Visma Skatt & Bokslut. Dessa uppdateringar gör det enklare att importera data, hantera din Fortnox-anslutning och säkerställer bättre datakvalitet genom förbättrad validering. Du kan nu tydligare se vilket Fortnox-företag som är anslutet och enklare koppla bort anslutningen vid behov.

## Prerequisites
För att kunna använda Fortnox-integrationen behöver du:
- Ett aktivt Visma Skatt & Bokslut-konto.
- Ett aktivt Fortnox-konto med nödvändiga behörigheter för att exportera data.
- En aktiv koppling mellan Visma Skatt & Bokslut och ditt Fortnox-konto.

## Steg

### 1. Ansluta till Fortnox och visa företagsuppgifter
Om du inte redan har anslutit ditt Fortnox-konto kan du göra det under inställningarna. När anslutningen är etablerad, eller om du redan är ansluten, kommer du nu tydligare att se information om det anslutna Fortnox-företaget direkt i gränssnittet.

1.  **Navigera till inställningar:** Gå till `Inställningar` (eller motsvarande menyalternativ för integrationer).
2.  **Välj Fortnox-integration:** Leta upp avsnittet för `Fortnox-anslutning` eller `Importkällor`.
3.  **Anslut eller verifiera anslutning:**
    *   Om du inte är ansluten, följ instruktionerna för att logga in på ditt Fortnox-konto och godkänna anslutningen.
    *   Om du redan är ansluten, kommer du att se namnet på det Fortnox-företag som är kopplat.
    *   **(Bild: Skärmbild som visar var Fortnox-företagets namn visas och eventuell tooltip för mer information.)**
    *   Håll muspekaren över företagsnamnet för att se ytterligare information via en tooltip, vilket ger dig en snabb överblick över den aktuella anslutningen.

### 2. Importera data från Fortnox
Nu kan du importera relevant data från Fortnox direkt till Visma Skatt & Bokslut. Detta förenklar processen för att få in uppgifter som behövs för din boksluts- och deklarationsprocess.

1.  **Starta importen:** Gå till den funktion där du normalt importerar data, t.ex. `Import av bokföringsdata` eller `Företagsimport`.
2.  **Välj Fortnox som källa:** I listan över tillgängliga importkällor, välj `Fortnox`.
3.  **Följ importguiden:** Systemet kommer att guida dig genom de steg som krävs för att välja vilken data du vill importera och slutföra processen. Importtexterna har justerats för att vara tydligare och mer informativa.
    *   **(Bild: Skärmbild som visar val av Fortnox som importkälla och de justerade importtexterna.)**

### 3. Förbättrad validering av organisationsnummer
Vid import av företag från Fortnox har valideringen av organisationsnummer förbättrats. Detta minskar risken för felaktig data och säkerställer att informationen om dina företag är korrekt.

*   Om ett organisationsnummer inte uppfyller kraven eller är felaktigt, kommer systemet att ge dig tydligare feedback, vilket hjälper dig att korrigera eventuella fel innan importen slutförs.

### 4. Koppla bort Fortnox-företag
Du har nu möjlighet att enkelt koppla bort ett Fortnox-företag från Visma Skatt & Bokslut om du inte längre behöver integrationen eller om du vill ansluta ett annat företag.

1.  **Navigera till


---

## Update: Fortnox Integration - API Import and Export

This update introduces the ability to import accounting data from Fortnox directly into S&B via their API, and to export closing entries back to Fortnox.

### New Functionality: Fortnox Data Source

We have added Fortnox as a new data source, enabling seamless integration with your Fortnox accounting system.

### User Impact

*   **Direct Import from Fortnox:** You can now import your accounting data directly from Fortnox, eliminating manual data entry or the need for intermediate file formats like SIE4 for this specific source.
*   **Automated Appendix Creation:** Upon importing data, S&B will automatically create appendices for Accounts Receivable (linked to account 1510) and Accounts Payable (linked to account 2440).
*   **Export Closing Entries to Fortnox:** You can now export your generated closing entries (V and S vouchers) directly back to Fortnox.

### Prerequisites

*   **Fortnox Account:** You must have an active Fortnox account with the necessary permissions to authorize API access.
*   **Existing S&B Data:** Ensure you have existing accounting data within S&B for the import process.

### Steps: Importing Data from Fortnox

1.  **Navigate to Start Guide:** In the S&B application, go to the "Start Guide".
2.  **Select Fortnox:** Choose "Fortnox" as your data source. You will see this as the 5th option available.
3.  **Login to Fortnox:** You will be redirected to the Fortnox login portal. Authenticate using your Fortnox credentials.
4.  **Authorize Access:** Grant S&B permission to access your Fortnox accounting data. This will generate an API token that is valid for 30 days.
5.  **Initiate Import:** Once authorized, you can initiate the data import. If you perform an import or export within the 30-day token validity period, the token will be refreshed for another 30 days from that date.
6.  **Review Imported Data:** After the import is complete, S&B will create the associated appendices for Accounts Receivable and Accounts Payable.

### Steps: Exporting Closing Entries to Fortnox

1.  **Navigate to Closing Entries:** In S&B, go to the "Closing entries" section.
2.  **Select Export Option:** Choose the "Export closing entries to Fortnox" option.
3.  **Configure Export:** A modal window will appear. Here, you can select the desired voucher series in Fortnox where the V and S vouchers should be placed.
4.  **Initiate Export:** Click "Export" to send the closing entries to your Fortnox account.

**Note:** If your Fortnox API token has expired, the export button will be disabled. A tooltip will indicate that you have lost your token and need to perform an import again to re-establish the connection.

### Maintenance and Settings

*   **Add Fortnox as Data Source:** Fortnox is now available as a selectable data source under "Maintenance" > "Settings" > "Data source".
*   **Change Data Source:** You can change your data source to Fortnox (or back to SIE4) using the same logic and interface as currently applied for SIE4 data sources.

### Activity Log and System Tasks

*   **Import Message Update:** The "Activity log / System tasks" will now include specific messages related to Fortnox imports.

### Validations

The following validations, similar to those used for SIE4, will be applied during Fortnox imports:

*   Organization number validation.
*   File size limit (100 MB).
*   Automatic filling of missing voucher series.
*   Skipping objects if more than 500 are present.

### Related Articles

*   [Importing Data from SIE4]
*   [Period Closing in S&B]
*   [Managing System Tasks]
