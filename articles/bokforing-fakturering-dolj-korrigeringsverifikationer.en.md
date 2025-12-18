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
updatedAt: '2025-12-18T10:04:39.272Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-18T10:02:08.262Z'
lastLLMUpdateAt: '2025-12-18T10:00:05.314Z'
languageUpdatedAt:
  sv: '2025-12-18T10:03:58.543Z'
  en: '2025-12-18T10:03:58.543Z'
translationBase:
  en: >-
    # Dölj ändringsverifikationer i bokföringen


    ## Snabbare överblick

    Nu kan du enkelt dölja verifikat som skapats för att korrigera tidigare
    bokföringar. Detta gör din verifikatshistorik renare och hjälper dig att
    snabbt se det som är viktigast. Tänk dig att slippa allt extra "brus" – så
    blir det lättare att hitta och arbeta med dina huvudsakliga verifikat.


    ## Vad är nytt?

    Du kan välja att gömma verifikat som är gjorda för att rätta till något som
    redan bokförts. Med den senaste uppdateringen kan du nu även dölja
    korrigeringar av periodiseringar. Det här är perfekt när du vill ha en
    tydligare bild av din bokföring, utan att detaljer kring korrigeringar tar
    uppmärksamheten.


    ## Så här fungerar det

    Att dölja korrigeringar är en inställning du enkelt kan slå på eller av. När
    den är på kommer verifikat som är markerade som korrigeringar att gömmas
    automatiskt. Du slipper se dem i din vanliga lista över verifikat, i
    kontospecifikationer och i rapporter.


    För att aktivera eller stänga av funktionen, gå till **Inställningar** och
    leta efter valet för att hantera hur verifikat visas.


    **Bra att veta:**

    *   Den här funktionen gömmer bara direkta, en-till-en-korrigeringar. Om ett
    verifikat rättas till på ett annat datum, eller om korrigeringen delas upp
    på flera rader, kommer dessa verifikat inte att gömmas. Detta för att
    säkerställa att saldon alltid visas korrekt i analyser och rapporter.

    *   Om du filtrerar på projekt eller kostnadsställen påverkas inte den här
    inställningen.

    *   Vi har kollat att beräknade saldon i analyser och rapporter fortfarande
    blir helt rätt, även när korrigeringar göms.


    ### Var korrigeringar kan döljas:

    *   **I vyn:**
        *   Bokföring - Verifikat
        *   Kontospecifikationer - Reskontra
        *   Kontospecifikationer - Balans- och Resultaträkning
    *   **I rapporter:**
        *   Verifikatlista
        *   Reskontra
        *   Reskontra konton (för jordbruksföretag)
        *   Kundreskontra (gäller bara om en hel faktura makulerats)
        *   Leverantörsreskontra (gäller bara om en hel faktura makulerats)

    ### Processer där korrigeringar kan döljas:

    *   Bokföring - Verifikat - Åtgärder - Skapa korrigeringsverifikat

    *   Bokföring - Verifikat - Redigera - Åtgärder - Skapa
    korrigeringsverifikat

    *   Bokföring - Verifikat - Nytt verifikat - Lägg till manuellt
    korrigeringsverifikat

    *   Korrigering av periodiseringsverifikat

    *   Kassa och bank - Banktransaktioner denna period - Ej matchade

    *   Försäljning - Kundfakturor - Ej betalda kundfakturor - Åtgärder -
    Återkalla autogiro

    *   Försäljning - Kundfakturor - Ej betalda kundfakturor - Åtgärder -
    Kreditera

    *   Försäljning - Kundfakturor - Åtgärder - Kreditera - Makulera faktura

    *   Inköp - Leverantörsfakturor - Ej betalda leverantörsfakturor - Åtgärder
    - Makulera faktura

    *   Inköp - Leverantörsfaktura - Åtgärder - Kvitta - Bokför mot konto


    ## Dina fördelar

    *   **Få en renare överblick:** Mindre "brus" i verifikatlistan,
    kontospecifikationer och rapporter.

    *   **Fokusera på det viktiga:** Det blir enklare att se och arbeta med dina
    huvudsakliga verifikat.

    *   **Anpassa efter ditt behov:** Du väljer själv om du vill visa eller
    dölja korrigeringar.


    ## Mer att läsa

    *   [Hantera verifikat i bokföringen]

    *   [Inställningar för bokföring]
currentVersion: 16
metadata:
  solution: Bokföring & Fakturering
  targetAudience: []
  tags:
    - update
    - general
  productId: Bokföring & Fakturering
  area2: ''
  area1: Bokföring
---
# Hide change vouchers in accounting

In some cases, it may be desirable to hide change vouchers in the accounting. This can be relevant, for example, if you have made many changes that do not need to be visible in the reports.

## How to hide change vouchers?

To hide change vouchers, follow these steps:

1.  Go to `Accounting > Reports > General Ledger`.
2.  Click the `Options` button in the upper right corner.
3.  Select the `Hide change vouchers` checkbox.
4.  Click `OK` to save the changes.

<!--SPI_KB_IMAGE_0-->

When you now generate a report, the change vouchers will be hidden.

## Important to consider

-   This setting only affects the display in the reports and does not delete any data.
-   The change vouchers still remain in the system and can be displayed again by unchecking the checkbox.
-   The feature is intended to simplify report reading and should be used with discretion.## Quicker Overview
Now you can easily hide vouchers created to correct previous entries. This makes your voucher history cleaner and helps you quickly see what is most important. Imagine getting rid of all the extra "noise" – making it easier to find and work with your main vouchers.## What's new?
You can choose to hide vouchers made to correct something that has already been recorded. With the latest update, you can now also hide corrections of accruals. This is perfect when you want a clearer view of your accounting, without the details of corrections drawing your attention.

## How it works
Hiding corrections is a setting you can easily turn on or off. When it's on, vouchers marked as corrections will be hidden automatically. You won't see them in your regular list of vouchers, in account specifications, or in reports.

To enable or disable the feature, go to **Settings** and look for the option to manage how vouchers are displayed.

**Good to know:**
*   This feature only hides direct, one-to-one corrections. If a voucher is corrected on a different date, or if the correction is split across multiple lines, these vouchers will not be hidden. This is to ensure that balances are always displayed correctly in analyses and reports.
*   If you filter by project or cost centers, this setting is not affected.
*   We have verified that calculated balances in analyses and reports remain completely correct, even when corrections are hidden.

### Where corrections can be hidden:
*   **In the view:**
    *   Accounting - Vouchers
    *   Account Specifications - Subledger
    *   Account Specifications - Balance Sheet and Income Statement
*   **In reports:**
    *   Voucher List
    *   Subledger
    *   Subledger accounts (for agricultural businesses)
    *   Accounts Receivable Ledger (only applies if an entire invoice has been voided)
    *   Accounts Payable Ledger (only applies if an entire invoice has been voided)

### Processes where corrections can be hidden:
*   Accounting - Vouchers - Actions - Create correction voucher
*   Accounting - Vouchers - Edit - Actions - Create correction voucher
*   Accounting - Vouchers - New voucher - Add manual correction voucher
*   Correction of accrual vouchers
*   Cash and bank - Bank transactions this period - Unmatched
*   Sales - Customer invoices - Unpaid customer invoices - Actions - Revoke direct debit
*   Sales - Customer invoices - Unpaid customer invoices - Actions - Credit
*   Sales - Customer invoices - Actions - Credit - Void invoice
*   Purchasing - Supplier invoices - Unpaid supplier invoices - Actions - Void invoice
*   Purchasing - Supplier invoice - Actions - Offset - Post to account

## Your benefits
*   **Get a cleaner overview:** Less "noise" in the voucher list, account specifications, and reports.
*   **Focus on what's important:** It becomes easier to see and work with your main vouchers.
*   **Customize to your needs:** You choose whether to show or hide corrections.

## Further reading
*   [Manage vouchers in accounting]
*   [Settings for accounting]
## Further reading
*   [Manage vouchers in accounting]
*   [Accounting settings]
