---
title: test (Faq)
slug: General-test-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-23T12:19:44.351Z'
updatedAt: '2026-01-23T12:19:44.351Z'
id: kzo6ZMVhAuZ7R0ApghhN
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  area1: General
  area2: ''
  targetAudience: []
  tags:
    - update
    - General
    - faq
  guidelineVersions:
    instruction: 1
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    tone_voice: 1
---
Här hittar du svar på de vanligaste frågorna om den nya kopplingen mellan **Skatt & Bokslut** och Fortnox. Denna integration gör det enklare än någonsin att hämta bokföringsdata och skicka tillbaka bokslutsverifikationer direkt från vår ekonomiplattform.

## Hur kopplar jag Skatt & Bokslut till Fortnox?
Du kan välja Fortnox som datakälla direkt när du startar ett nytt uppdrag eller genom att ändra inställningarna för ett befintligt.

När du väljer Fortnox som källa i **Startguiden** eller under **Underhåll - Inställningar - Datakälla**, får du klicka på en knapp för att logga in. Du skickas då till Fortnox inloggningssida där du godkänner kopplingen. När det är klart skickas du tillbaka till **Skatt & Bokslut** och kan börja arbeta direkt.

## Vilken information hämtas vid importen från Fortnox?
Integrationen hämtar din bokföringsdata på samma sätt som en SIE4-fil, men helt automatiskt via API. 

Utöver själva bokföringen skapas även två bilagor automatiskt för att underlätta ditt arbete:
*   En bilaga för **Kundfordringar** (konto 1510).
*   En bilaga för **Leverantörsskulder** (konto 2440).

Dessa bilagor fylls i med aktuell data från Fortnox så att du slipper manuell hantering.

## Hur skickar jag tillbaka bokslutsverifikationer till Fortnox?
När du är klar med dina bokslutsdispositioner kan du enkelt exportera dessa tillbaka till Fortnox som verifikationer.

1.  Gå till vyn för **Bokslutsverifikationer**.
2.  Klicka på knappen **Exportera bokslutsverifikationer till Fortnox**.
3.  I rutan som visas väljer du vilken **Verifikationsserie** verifikationerna ska tillhöra i Fortnox.
4.  Klicka på **Exportera**.

Verifikationerna skapas nu direkt i Fortnox utan att du behöver ladda ner eller upp några filer.

## Hur länge är kopplingen mellan plattformarna giltig?
Säkerhetsnyckeln (token) som skapas när du loggar in första gången är giltig i 30 dagar. 

Det fina är att varje gång du gör en ny import eller export så förnyas dessa 30 dagar automatiskt. Om det skulle gå mer än 30 dagar utan att du använder kopplingen behöver du bara logga in på nytt för att återaktivera den. Om kopplingen har löpt ut ser du ett meddelande om att du behöver importera på nytt för att kunna exportera.

## Kan jag byta datakälla till Fortnox på ett befintligt uppdrag?
Ja, det går utmärkt. Du ändrar detta under **Underhåll - Inställningar - Datakälla**. Logiken fungerar på samma sätt som när du byter mellan olika importmetoder, och du kan enkelt växla till Fortnox för att dra nytta av den direkta överföringen.

**Relaterade länkar:**
*   [Arbeta med bilagor](https://example.com/bilagor)
*   [Skapa bokslutsverifikationer](https://example.com/verifikationer)
