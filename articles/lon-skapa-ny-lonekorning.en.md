---
lastLLMUpdateAt: '2025-12-11T10:31:26.115Z'
reviewedAt: '2025-12-11T10:32:14.970Z'
slug: skapa-ny-lonekorning
status: draft
updatedAt: '2025-12-17T07:51:35.620Z'
folderId: S0n4lfJ2K5VQ3piaOGtw
title: Skapa ny lönekörning
createdAt: '2025-12-17T07:51:35.620Z'
publishedAt: null
pendingReview: false
languages:
  - sv
  - en
format: md
currentVersion: 5
id: article-1765957895620-jamzy8nx9
metadata:
  targetAudience: []
  tags:
    - update
  area1: ''
  solution: Lön
  productId: Lön
  area2: ''
---
# Create a New Payroll Run in Spiris Payroll

## Overview
This article describes how to create a new payroll run in Spiris Payroll. By following the steps below, you can easily initiate a payroll run to manage regular salary payments or extra payments.

## Prerequisites
*   You have access to Spiris Payroll.
*   All mandatory fields in the employment record for the employees to be included in the payroll run are filled in. For an employee to appear in the list when you create a new payroll run, all mandatory fields in their employment record must be completed.
*   The employment date for the employees is earlier than or within the current payroll period.
*   If employees have made registrations in Travel & Expenses, ensure that all expenses for the period are compiled before you create the payroll run.

## Steps to Create a New Payroll Run

1.  **Navigate to Payroll Runs:**
    *   Select **Payroll** from the menu.
    *   Then click on **Payroll Runs**.

2.  **Start a New Payroll Run:**
    *   Click the **New Payroll Run** button.

3.  **Select Payroll Run Type:**
    *   Choose either **Regular Salary** or **Extra Payment** from the dropdown list.
        *   **Regular Salary:** Automatically retrieves all registrations for the current period and data from "Recurring Salary Lines" in the employment record. You can also import registrations from functions such as Employee, Time & Project Planning, and Travel & Expenses by checking "Import Registrations".
        *   **Extra Payment:** Creates blank payslips for selected employees. This is useful for, for example, bonus payments.

4.  **Enter Description (Optional):**
    *   You can add a description for the payroll run if you wish.

5.  **Enter Payment Date:**
    *   Select the date when the salary should be paid to the employees under **Payment Date**. The system suggests a date based on the previous payroll run, but you can change it.
    *   **Note:** If the selected date falls on a public holiday or weekend, or is far in the future, a warning will be displayed. Ensure the payment file is sent to the bank in time for the payment to be made on the selected date. If the date you normally pay salaries falls on a non-working day, choose the nearest banking day as the payment date.

6.  **Import Registrations (If Needed):**
    *   If you want to import registrations from other parts of Spiris (e.g., Employee, Time & Project Planning, Travel & Expenses, or Agency Support), check the **Import Registrations** box.
    *   If you have selected in your payroll settings that registrations should always be imported during a payroll run, this box is already checked. You can uncheck it if you do not want to import registrations for this specific run. You can also import registrations after the payroll run has been created.

7.  **Select Employees:**
    *   Verify that all employees to be included in the payroll run have a checkmark in the box to the left of their name in the list.

8.  **Create Payroll Run:**
    *   Click the **Create** button.

The payroll run is now created, and you can proceed with registering and completing the information on the employees' payslips.

## Field Explanations

### Payroll Run Type
*   **Regular Salary:** When you select **Regular Salary**, all registrations in the calendar for the current period are retrieved, as well as the data found under **Recurring Salary Lines** on the **Salary** tab in the employment record. Registrations made in the Employee, Time & Project Planning, and Travel & Expenses functions can be imported into a **Regular Salary** type payroll run. You retrieve these registrations by clicking **Import Registrations**.
*   **Extra Payment:** If you select **Extra Payment**, blank payslips are created for employees who have a checkmark in the box to the left. This is useful, for example, if you pay out a bonus to all or some employees once or twice a year.

### Description
It is optional to provide a description for the payroll run.

### Payment Date
If the previous payroll run is completed, the payment date is suggested, but you can choose another date. A warning appears if the date falls on a Saturday, Sunday, public holiday, or if it is a date far in the future. Ensure the payment file is sent to the bank in time for the payment to be made on the selected date.

### Import Registrations
Check **Import Registrations** if you want to import registrations made in Employee, Time & Project Planning, Travel & Expenses, or Agency Support when the payroll run is created. If you have selected in the payroll settings that registrations should be imported with each payroll run, the **Import Registrations** box is checked. You can uncheck the box if you do not want the import to be made for this payroll run. You can also import the registrations after the payroll run has been created.

If you always want to import registrations from add-on services when a new payroll run is created, you can select **Settings - Payroll Settings**, the **Salaries and Payments** tab, and check the box **Import registrations when payroll run is created**.

### Monthly Salary
This displays the salary and deviation period based on the settings made for the company under **Settings - Payroll Settings**, **Salaries and Payments** tab. Read more in the Payroll Settings section.

### Hourly Wage
This displays the salary and deviation period based on the settings made for the company under **Settings - Payroll Settings**, **Salaries and Payments** tab. Read more in the Payroll Settings section.

### Salary Form
Here you can filter the selection by employees with monthly salary or hourly wage. You can combine this choice with personnel category so that, for example, only salaried employees with a monthly salary are included in the payroll run.

### Personnel Category
Here you can filter the selection by salaried employees or hourly workers. You can combine this choice with salary form so that, for example, only salaried employees with a monthly salary are included in the payroll run.

## Related Articles
*   [Manage Reports in Travel & Expenses]
*   [Payroll Settings]
