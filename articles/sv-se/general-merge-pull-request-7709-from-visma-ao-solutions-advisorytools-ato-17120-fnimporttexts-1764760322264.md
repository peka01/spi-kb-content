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
updatedAt: '2025-12-08T13:29:02.058Z'
publishedAt: null
metadata:
  productId: skatt-&-bokslut
  area1: general
  area2: '7709'
  tags:
    - deprecation
    - general
  locale: sv-se
---
# Merge pull request #7709 from Visma-AO-Solutions-AdvisoryTools/ATO-17120-FNImportTexts

1. Merge pull request #7709 from Visma-AO-Solutions-AdvisoryTools/ATO-17120-FNImportTexts
   ATO-17120 Adjust import texts for Fortnox

2. ATO-17120 Adjust import texts for Fortnox

3. ATO-17263 Update orgno validation for fortnox company import (#7657)
   * ATO-17263 Update orgno validation for fortnox company import

* Update src/services/core.services/core/Core.Logic/ResourcesWeb/AppResources.resx

Co-authored-by: Copilot <175728472+Copilot@users.noreply.github.com>

* ATO-17263 Fix test issue

---------

Co-authored-by: Copilot <175728472+Copilot@users.noreply.github.com>

4. ATO-17118 Redo authentication (#7642)
   * ATO-17118 Add a way to remove tokens for current company

* ATO-17118 Add displaying fortnox company info

* ATO-17118 Add resource and tooltip for company info

* ATO-17118 Cleanup cache when disconnecting the company

* ATO-17118 Say no connected company instead of blank space

* Revert "ATO-17118 Say no connected company instead of blank space"

This reverts commit ca9cb3cb55fde52883a1ef2fe538c1d23a17048d.

* Revert "ATO-17118 Cleanup cache when disconnecting the company"

This reverts commit aaaa6c9b052c69eeb1be4c9f1d82770fdcd6a9ed.

* Revert "ATO-17118 Add resource and tooltip for company info"

This reverts commit 5237ccf372301c0909e37f5c33f8485e774d6af2.

* Revert "ATO-17118 Add displaying fortnox company info"

This reverts commit 519e44534f24ce6f032280d239a91aff9c582cef.

* ATO-17118 Keep the fix for unauthenticated fn companies

5. ATO-16945 Add Fortnox import source (#3934)

## User Impact
Combined changes from 5 commits affecting 0 files

---
*This article was auto-generated from manifest 4mHaePKBCWtBaFX15YaZ*


---

## Update: Fortnox Integration

This update introduces integration with Fortnox, allowing users to import accounting data and export closing entries.

### New: Fortnox Data Import

This section details how to import accounting data from Fortnox.

#### Overview of Fortnox Import

You can now import accounting data directly from Fortnox using their API. This feature adds Fortnox as a fifth data source option within the application.

#### Import Process

1.  **Start Guide:** In the Start Guide, select "Fortnox" as your data source.
2.  **Fortnox Login:** You will be redirected to the Fortnox login portal. Authenticate with your Fortnox credentials. Upon successful authentication, a token will be generated, valid for 30 days.
3.  **Token Refresh:** The token will be automatically refreshed for another 30 days from the date of your next import or export action within this 30-day period.
4.  **Data Import:** When importing data, the system will create two appendices:
    *   One linked to Account 1510 (Kundfordringar - Accounts Receivable Ledger).
    *   One linked to Account 2440 (Leverantörsskulder - Accounts Payable Ledger).
    *   Additional appendices may be supported in future releases.

#### Data Source Settings

*   Fortnox will be available as a data source option under **Maintenance** > **Settings** > **Data Source**.
*   You can change your import source here, utilizing the same logic as for SIE4 imports.

#### Validations

The import process will use the same validations as for SIE4, including:

*   Organization number (Orgnr) validation.
*   File size limits (e.g., 100 MB).
*   Automatic filling of missing voucher series.
*   Skipping objects if more than 500 are present.

#### Period Closing and Transaction Analysis

Imported vouchers from Fortnox will be supported for both **Period Closing** and **Transaction Analysis**, mirroring the functionality available for SIE4 data.

### New: Export Closing Entries to Fortnox

This section describes how to export closing entries to Fortnox.

#### Export Process

1.  **Initiate Export:** Navigate to the **Closing Entries** section and select "Export closing entries to Fortnox (without attachments)".
2.  **Voucher Series Selection:** A modal will appear, allowing you to choose the desired voucher series in Fortnox for your closing entries (V and S vouchers) via a dropdown menu.
3.  **Execute Export:** Click "Export" in the modal to begin the export process.

#### Token Status and Export

*   If a valid token is not available, the export button will be disabled.
*   A tooltip will be displayed stating, "You have lost your token, to proceed import again," guiding you to re-authenticate.

### Activity Log / System Tasks

The **Activity Log** and **System Tasks** will now include messages related to Fortnox imports.
