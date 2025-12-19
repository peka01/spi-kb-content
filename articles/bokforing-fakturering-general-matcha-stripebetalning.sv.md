---
title: Matcha Stripebetalning
slug: general-matcha-stripebetalning
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-19T07:20:57.547Z'
updatedAt: '2025-12-19T07:20:57.547Z'
id: TakNjG17LC1cxYU0VnKk
metadata:
  productId: Bokföring & Fakturering
  solution: Bokföring & Fakturering
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - instruction
---
# Matcha din Stripebetalning

När du tar emot betalningar via Stripe underlättar det att matcha dessa direkt i din ekonomiplattform. Genom att koppla ihop utbetalningen från Stripe med dina kundfakturor i Spiris håller du din bokföring uppdaterad och får full kontroll på dina transaktionsavgifter.

## Så här gör du

1. Gå till vyn för **Kassa och bankhändelser**.
2. Leta upp den bankhändelse som avser utbetalningen från Stripe och välj **Matcha**.
3. Under rubriken **Bokföringshändelse**, välj alternativet **Inbetalning från kundfaktura**.
4. Sök fram och markera den eller de fakturor som Stripe-betalningen gäller. 
5. Om beloppet från Stripe är lägre än fakturabeloppet (eftersom Stripe dragit sin avgift), välj **Ny bokföringshändelse** för att hantera mellanskillnaden.
6. Välj bokföringshändelsen **Bankavgifter** (eller motsvarande kostnadskonto för transaktionsavgifter, exempelvis konto 6570) och ange beloppet för Stripes avgift så att hela transaktionen går jämnt ut.
7. Avsluta genom att välja **Bokför**.

## Tips
> För att göra matchningen ännu smidigare kan du stämma av beloppen i ditt Stripe-konto först. På så sätt vet du exakt hur stor transaktionsavgiften är innan du påbörjar bokföringen i Spiris, vilket sparar tid och minskar risken för fel.

## Mer information
- Bokför bankavgifter och transaktionskostnader
- Hantera kundfakturor och inbetalningar
