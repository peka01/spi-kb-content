---
title: Matcha Stripebetalning (Faq)
slug: general-matcha-stripebetalning-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-19T07:21:07.556Z'
updatedAt: '2025-12-19T07:21:07.556Z'
id: y8rbEYxaror4YqKUcwDl
metadata:
  productId: Bokföring & Fakturering
  solution: Bokföring & Fakturering
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - faq
---
# Hur matchar jag en Stripebetalning?

Har du fått en inbetalning via Stripe? Härligt! Att matcha dina transaktioner från Stripe i Spiris är enkelt och hjälper dig att hålla din bokföring uppdaterad med minimal ansträngning.

## Hur gör jag för att matcha en inbetalning från Stripe?

När pengarna från Stripe kommer in på ditt bankkonto visas de under dina bankhändelser. Eftersom Stripe ofta drar en avgift innan pengarna landar på ditt konto, behöver du matcha händelsen så att både fakturan och avgiften blir rätt bokförda.

Gör så här:

1. Gå till vyn för dina bankhändelser.
2. Leta upp den aktuella utbetalningen från Stripe och välj att du vill matcha händelsen.
3. Välj att du vill matcha mot en **Kundfaktura**.
4. Sök upp den faktura som betalningen avser. 
5. Om beloppet som kommit in på banken är lägre än fakturabeloppet (på grund av Stripes avgift), väljer du att lägga till en ny bokföringsrad för att hantera mellanskillnaden.
6. Använd ett konto för bankavgifter (exempelvis konto 6570) för att bokföra Stripes avgift.
7. Kontrollera att det totala beloppet nu stämmer och välj att bokföra.

## Hur hanterar jag avgiften som Stripe drar?

Det är vanligt att Stripe drar sin tjänsteavgift direkt från kundens betalning innan resterande belopp skickas vidare till ditt bankkonto. För att din bokföring ska stämma behöver du bokföra fakturan som helt betald, samtidigt som du bokför avgiften som en kostnad i din verksamhet.

*   **Fakturabeloppet:** Det totala beloppet som kunden har betalat.
*   **Bankhändelsen:** Det belopp du faktiskt fått in på kontot (Fakturan minus Stripes avgift).
*   **Differensen:** Denna bokför du som en kostnad på ett konto för bankkostnader.

Genom att göra detta i ett och samma steg när du matchar bankhändelsen ser du till att kundfakturan blir markerad som slutbetald och att dina kostnader blir korrekta.

## Kan jag matcha flera fakturor mot en utbetalning?

Ja, om Stripe har samlat ihop flera kundbetalningar till en och samma utbetalning till ditt bankkonto kan du välja att matcha bankhändelsen mot flera fakturor samtidigt. Du lägger då till de fakturor det gäller och justerar för den totala avgiften som Stripe har dragit för hela bunten.

**Relaterade länkar:**
*   Läs mer om hur du hanterar kassa- och bankhändelser i vår plattform.
*   Behöver du hjälp med konto-val? Kontakta din redovisningskonsult för specifik rådgivning.
