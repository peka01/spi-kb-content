---
id: DAWh5QiBatBfx9M3OUWL
title: Balansavstämning
slug: general-balansavstamning
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2025-12-17T06:56:11.985Z'
updatedAt: '2025-12-17T10:20:35.920Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-17T07:07:23.100Z'
lastLLMUpdateAt: '2025-12-17T06:58:38.342Z'
currentVersion: 5
metadata:
  productId: Skatt & Bokslut
  area2: ''
  solution: Skatt & Bokslut
  tags:
    - update
    - general
  targetAudience: []
  area1: general
---
# Balance Reconciliation

## Overview
This update introduces improvements to the balance reconciliation feature in Tax & Accounting. These changes aim to make the process more efficient and user-friendly.

Balance Reconciliation – the overview can be found under both **Period Closing** and **Year-End Closing**.

The overview in Balance Reconciliation displays all balance sheet accounts that have transactions posted to them up to and including the period you are currently working with.

## What Has Changed?

### Customizable Columns
Which columns are displayed in the overview varies depending on the size of the screen you are working on. On smaller screens, only the most important columns are shown.

You can choose which columns to display in Balance Reconciliation and Profit Analysis by clicking **Hide/Add Column** at the top of the window. The setting is saved per company and applies to all periods. To reset to the default setting, select **Reset to Default Columns**.

### In-depth Detail with Drill-Down
You can expand the level of detail in Balance Reconciliation – Overview using the drill-down function, which allows you to examine the vouchers recorded for the accounts more closely.

Amounts available for drill-down are underlined and change color to blue when you hover over them in the overview. Click on an available amount to open a dialog box named **Account Analysis**, where all vouchers recorded for the current account are displayed.

Account Analysis opens in a separate browser window, allowing you to have multiple accounts open simultaneously without disrupting your work. You can freely move the window, for example, to a second screen, for increased overview. Note that when you close the tab, all windows opened from it will also be closed.

When the bookkeeping includes result units, cost carriers, or projects, these will be displayed when the vouchers are opened. Note that only the first 4 dimensions are displayed.

In Account Analysis, the opening balance for the selected account and period is shown above the voucher list, while the closing balance for the account and period is shown below the list.

The voucher list displays the voucher date, voucher number, period change, account balance after each voucher, and transaction text.

From Account Analysis, it is possible to select another account via the account selector at the top left. You can also adjust the period displayed using the period selector at the top right.

Click the arrow next to a voucher in the list to display a more detailed view for that specific voucher. This view contains information about debited and credited accounts, posted amounts, and transaction text.

### View Attached Files in Account Analysis
Click the paperclip in the **Attachments** column to view a document attached to a voucher. Select which document you want to view in the box that opens.

In the preview window, you can download the attached document by clicking the **Download** button and then easily drag it to an external attachment. It is also possible to create a new external attachment to which the document is automatically linked by selecting **Add Attachment** in the view mode.

### Field Explanations

*   **Reconciliation Amount:** You can choose to fill in the reconciliation amount either directly in the overview or on an attachment. If you have an integration with Bookkeeping & Invoicing, some of the amounts in this column will be filled in automatically when you import bookkeeping data.
*   **Reconciliation Difference:** If a difference arises between the closing balance and the reconciliation amount, this difference is displayed in this column. You can choose to create a closing voucher for the difference by clicking the blue symbol in the **Reconciliation Difference** column. You can view the closing vouchers you have created under Closing Vouchers. Read more in Closing Vouchers.
*   **Attachments:** If an account or account group has an attachment linked to it, the paperclip icon in this column is blue; otherwise, it is gray. When you click a gray paperclip icon, you can go directly to the main attachment for the account or account group, or add an attachment. To add an attachment, click the paperclip icon, select **Add Attachment**, and choose which attachment you want to add. After selecting the attachment and clicking **Add**, you will be taken to the **Attachments** view and can continue working with the attachment as usual. If you add an attachment to an account, that account will automatically be added to the created attachment. No account is added if the attachment is created for an account group. When you click a blue paperclip icon, a list of attachments linked to that account is displayed, along with a link to the main attachment.
*   **Automatic Checks:** This column shows the result of the automatic checks that have been run. A red symbol indicates that the check has found something. Clicking the symbol provides more detailed information. An orange symbol indicates that the check could not be run. An example of this is when a check is supposed to compare with previous periods, but there are no previous periods imported into Tax & Accounting. A green symbol indicates that the check has been run, but no discrepancies were found. Deviating check results can be cleared using the **Clear Check** button. When you clear a check result, the icon changes appearance and becomes gray with a green checkmark in the lower right corner. A result only needs to be cleared once, meaning that if you, for example, clear a result for an account in the balance reconciliation, the same result will also be cleared in the Transaction Analysis section. If a change occurs that affects the check result after it has been cleared, the clearing will be removed, and the icon will change appearance to indicate that the result needs to be updated. Read more in Automatic Checks.
*   **Checklist Status:** This column shows the status of the checklist questions for the account. A gray symbol indicates that no checklist questions have been cleared, a blue symbol indicates that some checklist questions have been cleared, and a green symbol indicates that all checklist questions have been cleared. The symbol is also a shortcut to the **Checklist** tab. Hover over the symbol to see how many checklist questions have been cleared.
*   **Cleared:** When you are finished reconciling an account, mark it as cleared in the **Cleared** column. Depending on where you click, you can set the status for individual accounts, account groups, or all accounts.
*   **Quality Assurance:** The internal quality assurance functionality, available via the **Quality Assurance** column, supports the firm in documenting the quality assurance work. After reviewing the work done on an account or account group, the person responsible for quality assurance can go to the **Quality Assurance** column on the right and click the icon to change the status of the account or account group. There are two available options: **Approved** and **Not Approved**. To reset the status of an account or account group, select **Reset Status**. When you select **Approved** for an account or account group, its status icon in the **Quality Assurance** column turns green. For individual accounts, you can hover over the icon to see the date and time of approval, as well as the name of the quality assurer. If the quality assurer has been removed from the accounting firm, they will be displayed as **Unknown User**. When you select **Not Approved** for an account or account group, the status icon in the **Quality Assurance** column turns orange, and you are given the option to leave a comment. For individual accounts, you can hover over the icon to see the date and time the status was set, as well as the name of the quality assurer. If a comment has been left, it will be displayed in the side panel. When you select **Reset Status**, the status icon in the **Quality Assurance** column turns gray and reverts to its original value.

## How Are You Affected?
You will experience an improved user experience when working with balance reconciliations, with new possibilities to customize the view and delve into details.

## Steps to Use the Updated Feature

1.  **Navigate to Balance Reconciliation:** Open Tax & Accounting and locate the balance reconciliation feature under **Period Closing** or **Year-End Closing**.
2.  **Customize the View:** Use **Hide/Add Column** to select which columns to display.
3.  **Drill Down into Details:** Click on underlined amounts to use the drill-down function and analyze vouchers in **Account Analysis**.
4.  **Manage Attachments and Checks:** Utilize the features for attachments and automatic checks to ensure accuracy.
5.  **Save Your Work:** When you are finished, make sure to save your changes.

## Related Articles
*   [Getting Started with Tax & Accounting]
*   [Working with Financial Statements]
*   [Closing Vouchers]
*   [Automatic Checks]
