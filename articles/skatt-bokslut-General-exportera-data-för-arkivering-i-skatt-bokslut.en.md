---
id: 95rxy3wTOLMiWPbsDnUF
title: Exportera data för arkivering i Skatt & Bokslut
slug: General-exportera-data-för-arkivering-i-skatt-bokslut
languages:
  - sv
  - en
format: md
status: test
folderId: null
createdAt: '2026-01-29T09:41:22.369Z'
updatedAt: '2026-01-29T09:49:09.528Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
updatedByName: Per Karlsson
currentVersion: 2
languageUpdatedAt:
  en: '2026-01-29T09:44:02.829Z'
  sv: '2026-01-29T09:44:02.829Z'
updatedBy: per.karlsson@visma.com
translationBase:
  en: >-
    # Exportera data för arkivering i Skatt & Bokslut


    I {{resource:Common_Company_Name_Short}} är det enkelt att spara ner
    företagets historiska data för att uppfylla lagkrav på arkivering. Genom den
    nya exportfunktionen kan du ladda ner all dokumentation för ett eller flera
    räkenskapsår i ett smidigt, komprimerat format (ZIP-fil).


    Denna funktion är tillgänglig för alla användare, även för dig som har ett
    abonnemang i läsläge (read-only).


    ## Förutsättningar

    För att kunna exportera data behöver du ha tillgång till företaget i Skatt &
    Bokslut.


    ## Så här gör du


    Följ dessa steg för att skapa en export av företagets dokumentation:


    1. Navigera till menyn för underhåll i plattformen.

    2. Välj **{{resource:ExportData_title_Export}}**.

    3. Markera alternativet **{{resource:ExportData_option_Documentation}}**. 
       *Tips! Håll muspekaren över informationsikonen bredvid alternativet för att se exakt vad exporten innehåller.*
    4. Under rubriken **{{resource:ExportData_label_FinancialYears}}** väljer du
    de år du vill arkivera. Du kan välja ett enskilt år eller markera alla år
    samtidigt.

    5. Klicka på knappen för att starta exporten. 

    6. En förloppsindikator visas medan filen förbereds. Du kan fortsätta arbeta
    i plattformen under tiden.

    7. När exporten är klar får du en notis. Klicka på
    **{{resource:DocumentationExport_Notification_Download}}** i notisen för att
    spara ZIP-filen på din dator.


    ## Resultat


    När exporten är klar laddas en ZIP-fil ner. Filen har en tydlig mappstruktur
    som gör det enkelt att hitta rätt i arkivet:


    *   **Toppnivå:** Mappar namngivna efter räkenskapsår.

    *   **Undernivå:** Varje år innehåller mappar för respektive period.

    *   **Innehåll:** I periodmapparna hittar du PDF-dokument för alla relevanta
    underlag, såsom skatteberäkningar, avstämningar och årsredovisningar.


    **Observera:** Endast perioder som innehåller aktiva kontroller, markerade
    konton eller kommentarer inkluderas i exporten. Detta för att ditt arkiv ska
    bli så relevant och kompakt som möjligt.


    ## Felsökning


    Om exporten inte kan genomföras fullt ut eller om ett specifikt dokument
    inte kan skapas:


    *   **Delvis lyckad export:** Du får en notis om att rapporten genererats
    men att vissa delar saknas
    (**{{resource:DocumentationExport_Notification_ExportIsPartiallySuccessful}}**).
    ZIP-filen kommer fortfarande att skapas med de dokument som gick att
    generera.

    *   **Felmeddelanden:** Om ett fel uppstår visas en sida som förklarar
    vilket dokument som orsakade problemet och varför. Detta kan hända om ett
    dokument har ett ovanligt format eller om tekniska anslutningsfel uppstår.

    *   **Ingen data:** Om inga PDF-filer kunde skapas (exempelvis om inga
    markeringar eller kommentarer finns för de valda åren) får du ett meddelande
    om att exporten misslyckades på grund av saknat innehåll.
metadata:
  guidelineVersions:
    article_matching: 1
    constitution: 1
    news: 9
    faq: 1
    getting_started: 2
    instruction: 1
    tone_voice: 1
  visibility: public
  solution: Skatt & Bokslut
  targetAudience: []
  tags:
    - instruction
    - update
    - General
  area1: General
  productId: H9lmIe7pbreUwWDp3K3X
  area2: ''
---
# Export data for archiving in Tax & Closing

In {{resource:Common_Company_Name_Short}}, it is easy to save the company's historical data to comply with legal archiving requirements. Through the new export function, you can download all documentation for one or more financial years in a convenient, compressed format (ZIP file).

This function is available to all users, including those with a read-only subscription.

## Prerequisites
To be able to export data, you need access to the company in Tax & Closing.

## How to do it

Follow these steps to create an export of the company's documentation:

1. Navigate to the maintenance menu in the platform.
2. Select **{{resource:ExportData_title_Export}}**.
3. Select the option **{{resource:ExportData_option_Documentation}}**. 
   *Tip! Hover your mouse over the information icon next to the option to see exactly what the export contains.*
4. Under the heading **{{resource:ExportData_label_FinancialYears}}**, select the years you want to archive. You can select a single year or mark all years at once.
5. Click the button to start the export. 
6. A progress bar is displayed while the file is being prepared. You can continue working in the platform in the meantime.
7. When the export is complete, you will receive a notification. Click **{{resource:DocumentationExport_Notification_Download}}** in the notification to save the ZIP file to your computer.

## Result

When the export is complete, a ZIP file is downloaded. The file has a clear folder structure that makes it easy to find your way in the archive:

*   **Top level:** Folders named after financial years.
*   **Sub-level:** Each year contains folders for the respective period.
*   **Content:** In the period folders, you will find PDF documents for
