---
title: Skatt att betala eller få tillbaka
slug: '-skatt-att-betala-eller-fa-tillbaka-1765290040344'
format: md
status: draft
folderId: null
publishedAt: null
id: article-1765290046430-gi2z6veh6
createdAt: '2025-12-09T14:20:46.430Z'
updatedAt: '2025-12-09T14:20:46.430Z'
metadata:
  productId: Bokföring & Fakturering
  solution: Bokföring & Fakturering
  area1: ''
  area2: ''
  tags:
    - update
    - ''
---
# Skatt att betala eller få tillbaka

## Översikt
Den här artikeln beskriver en ny funktion i Bokföring & Fakturering som gör det enklare att förstå om du ska betala moms eller få tillbaka moms.

## Varför det är viktigt
För att underlätta för dig att förstå din momssituation har vi lagt till en indikator som tydligt visar om du ska betala moms till Skatteverket eller om du har moms att få tillbaka. Detta gör det enklare att planera din ekonomi och säkerställa korrekt rapportering.

## Förutsättningar
* Du har tillgång till modulen Bokföring & Fakturering.

## Hur du använder det
Vi har lagt till en ny funktion i momsspecifikationen som visar om momsen är att betala eller att få tillbaka.

1.  Navigera till **Rapporter** i din meny.
2.  Välj **Momsspecifikation**.
3.  Generera rapporten för den aktuella perioden.

Du kommer nu att se en ny text som indikerar din momssituation:

*   Om beloppet i fält 49 är positivt (utgående moms är större än ingående moms), kommer texten att vara: **"Moms att betala"**.
*   Om beloppet i fält 49 är negativt (ingående moms är större än utgående moms), kommer texten att vara: **"Moms att få tillbaka"**.

### Exempel
Anta att du har genererat din momsspecifikation för kvartalet och ser följande:

*   **Utgående moms:** 15 000 SEK
*   **Ingående moms:** 10 000 SEK
*   **Belopp i fält 49:** 5 000 SEK

Eftersom beloppet i fält 49 är positivt, kommer rapporten att visa texten **"Moms att betala"**.

Om istället:

*   **Utgående moms:** 10 000 SEK
*   **Ingående moms:** 15 000 SEK
*   **Belopp i fält 49:** -5 000 SEK

Eftersom beloppet i fält 49 är negativt, kommer rapporten att visa texten **"Moms att få tillbaka"**.

## Tekniska detaljer
Denna uppdatering lägger till en visuell indikator i momsspecifikationen baserad på värdet i fält 49. Om fält 49 > 0 visas "Moms att betala". Om fält 49 < 0 visas "Moms att få tillbaka".

## Relaterade artiklar
* [Skapa en momsspecifikation](länk_till_artikel_om_momsspecifikation)
* [Förstå momsrapportering](länk_till_artikel_om_momsrapportering)
