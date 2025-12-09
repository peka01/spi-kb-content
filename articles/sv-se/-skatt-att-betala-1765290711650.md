---
id: article-1765290717799-p7v33wd66
title: Skatt att betala
slug: '-skatt-att-betala-1765290711650'
format: md
status: draft
folderId: null
createdAt: '2025-12-09T14:31:57.799Z'
updatedAt: '2025-12-09T14:45:33.769Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-09T14:45:33.762Z'
lastLLMUpdateAt: '2025-12-09T14:41:42.470Z'
metadata:
  productId: Bokföring & Fakturering
  solution: Bokföring & Fakturering
  area1: ''
  area2: ''
  tags:
    - update
    - ''
  locale: sv-se
---
# Moms att betala – Förstå momsbehandlingen

## Översikt
Den här artikeln förklarar en ny funktion i Bokföring & Fakturering som ger dig en tydligare indikation på om du ska betala moms eller få moms återbetald. Denna uppdatering är utformad för att göra det enklare för alla användare att förstå momssituationen.

## Förutsättningar
*   Du har åtkomst till modulen Bokföring & Fakturering.
*   Du har tillgång till momsrapporten.

## Steg
Denna uppdatering lägger till en ny indikator på momsrapporten.

1.  Navigera till din **Momsrapport**.
2.  På rapporten ser du en ny text som indikerar momshanteringen baserat på saldot i fält 49 (netto moms):
    *   Om beloppet i fält 49 är **positivt** (utgående moms är större än ingående moms), visar rapporten **"Moms att betala"**.
    *   Om beloppet i fält 49 är **negativt** (ingående moms är större än utgående moms), visar rapporten **"Moms att återbetala"**.

### Exempel

*   **Scenario 1: Moms att betala**
    Om din utgående moms är 10 000 SEK och din ingående moms är 6 000 SEK, blir saldot i fält 49 +4 000 SEK. Momsrapporten visar då **"Moms att betala"**.

*   **Scenario 2: Moms att återbetala**
    Om din utgående moms är 5 000 SEK och din ingående moms är 8 000 SEK, blir saldot i fält 49 -3 000 SEK. Momsrapporten visar då **"Moms att återbetala"**.

## Relaterade artiklar
*   [Skapa en momsrapport](länk-till-momsrapport-artikel)
*   [Förstå momsredovisning](länk-till-momsredovisning-artikel)
