---
updatedAt: '2025-12-17T08:17:16.129Z'
createdAt: '2025-12-17T08:17:16.129Z'
pendingReview: false
lastLLMUpdateAt: '2025-12-16T08:50:43.784Z'
status: draft
title: Dölj korrigeringsverifikationer
publishedAt: null
format: md
currentVersion: 11
folderId: null
languages:
  - sv
  - en
slug: dolj-korrigeringsverifikationer
reviewedAt: '2025-12-16T08:54:02.030Z'
id: article-1765959436129-k6srowqdf
metadata:
  area1: Bokföring
  targetAudience: []
  area2: ''
  solution: Bokföring & Fakturering
  productId: Bokföring & Fakturering
  tags:
    - update
    - general
---
# Hide Correction Vouchers

## Overview
This update introduces a new feature that allows you to hide vouchers created as corrections in your bookkeeping. This helps to keep your voucher history clean and focused on the primary vouchers. The feature is designed to reduce visual "noise" and make it easier to identify and work with primary vouchers.

## What's New?
You can now choose to hide vouchers that were created as a correction to a previous voucher. This is particularly useful if you want a clearer overview of your bookkeeping without being disturbed by correction details.

## How it Works
The correction hiding feature is a setting that can be enabled. When the feature is enabled, vouchers marked as corrections will automatically be hidden from your default view of the voucher list, account specifications, and reports.

To enable or disable this feature, go to **Settings** and look for the option to manage voucher display.

**Important Notes:**
*   This feature only hides direct 1-to-1 corrections. If a voucher is corrected on a different date, or if the correction is split into multiple lines, these vouchers will not be hidden. This is to ensure correct display of balances in analyses and reports.
*   Filtering by project and cost centers is not affected by this setting.
*   Calculated balances in analyses and reports have been tested to ensure they remain accurate even when corrections are hidden.

### Where Corrections Can Be Hidden:
*   **Display:**
    *   Bookkeeping - Vouchers
    *   Account Specifications - Accounts Receivable
    *   Account Specifications - Balance Sheet and Income Statement
*   **Reports:**
    *   Voucher List
    *   Accounts Receivable
    *   Accounts Receivable Accounts (Agricultural Businesses)
    *   Customer Accounts Receivable (only for fully voided invoices)
    *   Supplier Accounts Receivable (only for fully voided invoices)

### Processes Where Corrections Can Be Hidden:
*   Bookkeeping - Vouchers - Actions - Create Correction Voucher
*   Bookkeeping - Vouchers - Edit - Actions - Create Correction Voucher
*   Bookkeeping - Vouchers - New Voucher - Add Manual Correction Voucher
*   Cash and Bank - Bank Transactions This Period - Unmatched
*   Sales - Customer Invoices - Unpaid Customer Invoices - Actions - Recall Direct Debit
*   Sales - Customer Invoices - Unpaid Customer Invoices - Actions - Credit
*   Sales - Customer Invoices - Actions - Credit - Void Invoice
*   Purchases - Supplier Invoices - Unpaid Supplier Invoices - Actions - Void Invoice
*   Purchases - Supplier Invoice - Actions - Offset - Post to Account

## Benefits
*   **Cleaner Overview:** Reduced visual "noise" in the voucher list, account specifications, and reports.
*   **Focus on the Essentials:** Easier to identify and work with primary vouchers.
*   **Flexibility:** You can choose to show or hide corrections based on your needs.

## Related Articles
*   [Manage Vouchers in Bookkeeping]
*   [Bookkeeping Settings]
