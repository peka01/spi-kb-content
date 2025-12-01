---
id: article-1764583390260-x1qdl1cn5
title: Ta bort faktura
slug: forsaljning-ta-bort-faktura-1764583380602
format: md
status: draft
folderId: folder-1764579266505
createdAt: '2025-12-01T10:03:10.260Z'
updatedAt: '2025-12-01T11:05:35.737Z'
publishedAt: null
metadata:
  productId: bokforing-fakturering
  area1: Fakturering
  area2: Kundfakturor
  solution: Bokföring & Fakturering
  targetAudience:
    - administrator
    - ekonomiansvarig
    - fakturerare
  tags:
    - new_feature
    - forsaljning
  locale: sv
---
# Ta bort faktura

## Översikt
dsfsdf
Denna artikel beskriver hur du använder den nya funktionen för att ta bort en kundfaktura direkt från redigeringsvyn i Visma Bokföring & Fakturering. Den nya knappen "Ta bort faktura" gör det enklare och snabbare att radera fakturor som skapats av misstag eller inte längre behövs, innan de har skickats eller bokförts.

Du hittar knappen "Ta bort faktura" i verktygsfältet när du skapar eller redigerar en kundfaktura.

## Förutsättningar
För att kunna ta bort en faktura behöver du:
-   Behörighet för `invoice.delete` och `invoice.edit`.
-   Fakturan måste ha statusen **Utkast** eller **Ej skickad**.
-   Bokförda eller skickade fakturor kan inte tas bort. De måste i stället krediteras.

## Steg

Följ dessa steg för att ta bort en kundfaktura:

1.  **Navigera till fakturan:**
    *   Gå till `/forsaljning/kundfaktura/skapa` för att skapa en ny faktura.
    *   Eller gå till `/forsaljning/kundfaktura/:id/redigera` för att redigera en befintlig faktura.
    <!-- SCREENSHOT: Exempel på Skapa Kundfaktura-vyn med fakturainformation -->

2.  **Leta upp knappen "Ta bort faktura":**
    *   I verktygsfältet högst upp på skärmen, till höger om andra åtgärdsknappar, hittar du knappen **Ta bort faktura**. Den är markerad med röd färg och en papperskorgsikon.
    *   Om fakturan redan är skickad eller bokförd kommer knappen att vara inaktiv.
    <!-- SCREENSHOT: Plats för knappen 'Ta bort faktura' i SkapaKundfakturaToolbar -->

3.  **Klicka på "Ta bort faktura":**
    *   Klicka på knappen **Ta bort faktura**.
    *   En bekräftelsedialogruta öppnas för att förhindra oavsiktlig radering.

4.  **Bekräfta borttagningen:**
    *   I dialogrutan **DeleteInvoiceConfirmDialog** visas information om fakturan som ska tas bort.
    *   För fakturor med ett belopp över 10 000 SEK måste du skriva in ordet "TA BORT" i ett textfält för att aktivera bekräftelseknappen. Detta är en extra säkerhetsåtgärd.
    *   Klicka på **Bekräfta** för att slutföra borttagningen.
    <!-- SCREENSHOT: DeleteInvoiceConfirmDialog, eventuellt med exemplet för >10 000 SEK -->

5.  **Fakturan raderas:**
    *   Fakturan tas nu bort från systemet och du omdirigeras till fakturaöversikten.

## Relaterade artiklar
-   [Skapa en kundfaktura](länk-till-skapa-faktura-artikel)
-   [Kreditera en kundfaktura](länk-till-kreditera-faktura-artikel)
-   [Hantera fakturastatusar](länk-till-fakturastatus-artikel)
