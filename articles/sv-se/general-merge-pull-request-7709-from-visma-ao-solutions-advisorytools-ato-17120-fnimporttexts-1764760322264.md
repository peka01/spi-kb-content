---
id: article-1764760322277-yfgz3sruv
title: >-
  Merge pull request #7709 from
  Visma-AO-Solutions-AdvisoryTools/ATO-17120-FNImportTexts
slug: >-
  general-merge-pull-request-7709-from-visma-ao-solutions-advisorytools-ato-17120-fnimporttexts-1764760322264
format: md
status: draft
folderId: null
createdAt: '2025-12-03T11:12:02.277Z'
updatedAt: '2025-12-09T08:44:32.331Z'
publishedAt: null
pendingReview: true
lastLLMUpdateAt: '2025-12-09T08:44:32.315Z'
reviewedAt: null
metadata:
  productId: skatt-&-bokslut
  area1: general
  area2: '7709'
  tags:
    - deprecation
    - general
  locale: sv-se
---
# Fortnox Integration Updates

## Overview
This article details recent updates to the Fortnox integration, focusing on improvements to data import, export of closing entries, and related system functionalities.

## Prerequisites
- Access to Visma software with Fortnox integration enabled.
- Valid Fortnox credentials.

## Steps

### Fortnox Data Import Enhancements

The Fortnox import functionality has been refined to improve user experience and data accuracy.

#### Import Process Adjustments

1.  **Data Source Selection:** In the Start Guide, "Fortnox" remains the selectable data source.
2.  **Authentication and Token Management:**
    *   Upon initial connection, you will be redirected to the Fortnox login portal. After successful authentication, an access token is generated, valid for 30 days.
    *   The token is automatically extended for another 30 days from the date of your next import or export action within the current 30-day validity period.
3.  **Appendix Generation:** When importing data, the system continues to create two appendices:
    *   Linked to Account 1510 (Kundfordringar - Accounts Receivable Ledger).
    *   Linked to Account 2440 (Leverantörsskulder - Accounts Payable Ledger).
    *   Support for additional appendices may be introduced in future releases.

#### Data Source Settings

*   Fortnox is available as a data source option under **Maintenance** > **Settings** > **Data Source**.
*   The logic for changing your import source is consistent with SIE4 imports.

#### Validation Updates

The import process utilizes the same validations as SIE4, including:

*   Organization number (Orgnr) validation.
*   File size limits (e.g., 100 MB).
*   Automatic filling of missing voucher series.
*   Skipping objects if more than 500 are present.

#### Supported Functionality

Imported vouchers from Fortnox are supported for both **Period Closing** and **Transaction Analysis**, similar to SIE4 data.

### Export Closing Entries to Fortnox Improvements

The process for exporting closing entries to Fortnox has been refined.

#### Export Process

1.  **Initiate Export:** Navigate to the **Closing Entries** section and select "Export closing entries to Fortnox (without attachments)".
2.  **Voucher Series Selection:** A modal appears, allowing you to select the desired voucher series in Fortnox for your closing entries (V and S vouchers) via a dropdown menu.
3.  **Execute Export:** Click "Export" in the modal to initiate the export.

#### Token Status and Export Availability

*   The export button will be disabled if a valid token is not available.
*   A tooltip will be displayed stating, "You have lost your token, to proceed import again," prompting re-authentication.

### Activity Log and System Tasks

*   The **Activity Log** and **System Tasks** now include specific messages related to Fortnox imports.

### License Information for Icons

*   Support has been added for including manual external components, such as icons, with associated licenses. This includes nodes for licenses like Lucide.
*   Scripts have been updated to handle manually added nodes for external components.

### Combined Changes

#### User Impact

*   **Date Format for AR Locked Data in English:** For users operating in English, the date format for Accounts Receivable (AR) locked data has been corrected. This ensures consistency and accuracy when handling financial records in English.

## Related Articles
* [Importing Data from Fortnox](link_to_fortnox_import_article)
* [Exporting Closing Entries](link_to_closing_entries_export_article)
* [Managing Data Sources](link_to_data_sources_article)
