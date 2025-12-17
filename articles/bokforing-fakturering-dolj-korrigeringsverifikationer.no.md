---
status: draft
folderId: null
lastLLMUpdateAt: '2025-12-16T08:50:43.784Z'
pendingReview: false
createdAt: '2025-12-16T08:45:06.743Z'
slug: dolj-korrigeringsverifikationer
updatedAt: '2025-12-17T07:49:45.606Z'
reviewedAt: '2025-12-16T08:54:02.030Z'
title: Dölj korrigeringsverifikationer
languages:
  - sv
  - en
currentVersion: 11
publishedAt: null
format: md
id: xUYgEGpkq9Hf6P1jkvgS
metadata:
  productId: Bokföring & Fakturering
  targetAudience: []
  area1: Bokföring
  solution: Bokföring & Fakturering
  area2: ''
  tags:
    - update
    - general
---
# Skjul korreksjonsbilag

## Oversikt
Denne oppdateringen introduserer en ny funksjon som lar deg skjule bilag som er opprettet som korrigeringer i regnskapet ditt. Dette bidrar til å holde bilagshistorikken din ryddig og fokusert på de primære bilagene. Funksjonen er designet for å redusere visuell "støy" og gjøre det enklere å identifisere og arbeide med primære bilag.

## Hva er nytt?
Du kan nå velge å skjule bilag som er opprettet som en korrigering av et tidligere bilag. Dette er spesielt nyttig hvis du ønsker en tydeligere oversikt over regnskapet ditt uten å bli forstyrret av detaljer rundt korrigeringer.

## Hvordan det fungerer
Funksjonen for å skjule korrigeringer er en innstilling som kan aktiveres. Når funksjonen er aktivert, vil bilag som er merket som korrigeringer automatisk bli skjult fra standardvisningen av bilagslisten, kontospesifikasjoner og rapporter.

For å aktivere eller deaktivere denne funksjonen, gå til **Innstillinger** og se etter alternativet for å administrere bilagsvisning.

**Viktig å merke seg:**
*   Denne funksjonen skjuler kun direkte 1-til-1-korrigeringer. Hvis et bilag korrigeres på en annen dato, eller hvis korrigeringen deles opp i flere linjer, vil disse bilagene ikke bli skjult. Dette er for å sikre korrekt visning av saldi i analyser og rapporter.
*   Filtrering på prosjekter og kostnadssteder påvirkes ikke av denne innstillingen.
*   Beregnet saldi i analyser og rapporter er testet for å sikre at de forblir korrekte selv når korrigeringer skjules.

### Hvor korrigeringer kan skjules:
*   **Visning:**
    *   Regnskap - Bilag
    *   Kontospesifikasjoner - Reskontro
    *   Kontospesifikasjoner - Balanse- og resultatregnskap
*   **Rapporter:**
    *   Bilagsliste
    *   Reskontro
    *   Reskontro kontoer (landbruksselskap)
    *   Kundereskontro (kun ved helt makulert faktura)
    *   Leverandørreskontro (kun ved helt makulert faktura)

### Prosesser der korrigeringer kan skjules:
*   Regnskap - Bilag - Handlinger - Opprett korrigeringsbilag
*   Regnskap - Bilag - Rediger - Handlinger - Opprett korrigeringsbilag
*   Regnskap - Bilag - Nytt bilag - Legg til manuelt korrigeringsbilag
*   Kasse og bank - Banktransaksjoner denne perioden - Ikke matchet
*   Salg - Kundefakturaer - Ubetalte kundefakturaer - Handlinger - Tilbakekall autogiro
*   Salg - Kundefakturaer - Ubetalte kundefakturaer - Handlinger - Kreditér
*   Salg - Kundefakturaer - Handlinger - Kreditér - Makulér faktura
*   Innkjøp - Leverandørfakturaer - Ubetalte leverandørfakturaer - Handlinger - Makulér faktura
*   Innkjøp - Leverandørfaktura - Handlinger - Kvitt - Bokfør mot konto

## Fordeler
*   **Ryddigere oversikt:** Redusert visuell "støy" i bilagslisten, kontospesifikasjoner og rapporter.
*   **Fokus på det vesentlige:** Enklere å identifisere og arbeide med primære bilag.
*   **Fleksibilitet:** Du kan velge å vise eller skjule korrigeringer basert på dine behov.

## Relaterte artikler
*   [Administrere bilag i regnskapet]
*   [Innstillinger for regnskap]
