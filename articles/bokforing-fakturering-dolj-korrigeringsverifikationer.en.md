---
id: xUYgEGpkq9Hf6P1jkvgS
title: Dölj korrigeringsverifikationer
slug: dolj-korrigeringsverifikationer
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2025-12-16T08:45:06.743Z'
updatedAt: '2025-12-18T10:31:59.026Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-18T10:30:11.880Z'
lastLLMUpdateAt: '2025-12-18T10:29:34.119Z'
translationBase:
  en: >-
    # Dölj korrigeringsverifikationer i bokföringen


    ## Overview

    I Spiris är det enkelt att hålla din bokföring ren och överskådlig. Genom
    att dölja verifikationer som skapats enbart för att korrigera tidigare
    bokföringsposter slipper du onödigt "brus" i dina listor. Det gör att du kan
    fokusera på de faktiska affärshändelserna och snabbare hitta det du letar
    efter i din ekonomiplattform.


    Denna funktion döljer automatiskt direkta korrigeringar (1:1) i både
    verifikatlistan, kontospecifikationer och i flera av dina rapporter,
    inklusive reskontra för jordbruksföretag.


    ## Steps

    Följ dessa steg för att aktivera eller inaktivera visningen av
    korrigeringsverifikationer:


    1. Gå till **Inställningar** i huvudmenyn.

    2. Välj **Företagsinställningar** och klicka på fliken **Bokföring**.

    3. Markera eller avmarkera rutan för att dölja korrigeringsverifikationer. 

    4. Klicka på **Spara**.


    När inställningen är aktiverad kommer systemet automatiskt att filtrera bort
    de verifikat som är markerade som korrigeringar i dina vyer och rapporter.


    ### Bra att veta

    *   **Krav för att döljas:** Endast direkta korrigeringar där ett verifikat
    rättar ett annat i sin helhet (1:1) döljs. Om en korrigering görs på ett
    annat datum än originalet, eller om den delas upp på flera rader, kommer
    verifikaten fortfarande att visas. Detta är för att säkerställa att dina
    saldon alltid är korrekta i analyser.

    *   **Periodiseringar:** Funktionen omfattar även korrigeringar av
    periodiseringsverifikat.

    *   **Projekt och kostnadsställen:** Om du filtrerar din vy på specifika
    projekt eller kostnadsställen påverkas inte visningen av denna inställning.

    *   **Saldon:** Dina beräknade saldon i rapporter och analyser förblir
    korrekta även när korrigeringarna är dolda.


    ### Här döljs korrigeringarna

    När funktionen är påslagen döljs verifikaten på följande ställen:


    **I vyer:**

    *   **Bokföring** - **Verifikat**

    *   **Kontospecifikationer** - **Reskontra**

    *   **Kontospecifikationer** - **Balans- och Resultaträkning**


    **I rapporter:**

    *   **Verifikatlista**

    *   **Reskontra**

    *   **Reskontra konton** (specifikt för jordbruksföretag)

    *   **Kundreskontra** och **Leverantörsreskontra** (när en hel faktura har
    makulerats)


    ### Processer som stödjer döljning

    Funktionen fungerar vid flera olika typer av korrigeringar, till exempel när
    du väljer **Skapa korrigeringsverifikat** under **Åtgärder** i
    verifikatlistan, eller när du makulerar kund- och leverantörsfakturor. Det
    gäller även vid återkallande av autogiro och när du kvittar
    leverantörsfakturor mot ett konto.


    ## Related Articles

    * [Hantera verifikat i bokföringen]

    * [Inställningar för bokföring]

    * [Korrigera ett bokfört verifikat]
currentVersion: 18
languageUpdatedAt:
  sv: '2025-12-18T10:03:58.543Z'
  en: '2025-12-18T10:31:31.923Z'
metadata:
  tags:
    - update
    - general
  targetAudience: []
  area2: ''
  solution: Bokföring & Fakturering
  productId: Bokföring & Fakturering
  area1: Bokföring
---
# Hide correction vouchers in the accounting
## Overview
In Spiris, it is easy to keep your accounting clean and organized. By hiding journal entries created solely to correct previous accounting entries, you avoid unnecessary "noise" in your lists. This allows you to focus on the actual business transactions and find what you are looking for in your financial platform more quickly.This function automatically hides direct corrections (1:1) in the voucher list, account specifications, and in several of your reports, including ledgers for agricultural businesses.## Steps
Follow these steps to enable or disable the display of correction vouchers:1. Go to **Settings** in the main menu.
2. Select **Company Settings** and click the **Accounting** tab.
3. Check or uncheck the box to hide correction vouchers.
4. Click **Save**.When the setting is enabled, the system will automatically filter out the vouchers marked as corrections in your views and reports.### Good to know
*   **Requirements for hiding:** Only direct corrections where one voucher corrects another in its entirety (1:1) are hidden. If a correction is made on a different date than the original, or if it is split into multiple lines, the vouchers will still be displayed. This is to ensure that your balances are always correct in analyses.
*   **Accruals:** The function also includes corrections of accrual vouchers.
*   **Projects and cost centers:** If you filter your view by specific projects or cost centers, the display is not affected by this setting.
*   **Balances:** Your calculated balances in reports and analyses remain correct even when corrections are hidden.### Where corrections are hidden
When the feature is enabled, the vouchers are hidden in the following places:**In views:**
*   **Accounting** - **Journal entries**
*   **Account specifications** - **Ledgers**
*   **Account specifications** - **Balance Sheet and Income Statement****In reports:**
*   **Voucher list**
*   **Ledger**
*   **Ledger accounts** (specific to agricultural businesses)
*   **Accounts Receivable** and **Accounts Payable** (when an entire invoice has been voided)### Processes that support hiding
The function works for several different types of corrections, for example when you select **Create correction journal entry** under **Actions** in the journal entry list, or when you void customer and supplier invoices. It also applies when revoking direct debits and when you offset supplier invoices against an account.## Related Articles
* [Manage journal entries]
* [Accounting settings]
* [Correct a posted journal entry]
