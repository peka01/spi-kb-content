---
title: Fortnox tech (Custom)
slug: general-fortnox-tech-custom
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-22T15:20:41.991Z'
updatedAt: '2025-12-22T15:20:41.991Z'
id: nWFqZaChF5lH5XUfnbiZ
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - custom
  guidelineVersions:
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
# Ny koppling mellan Skatt & Bokslut och Fortnox

För att göra ditt arbete med bokslut och skatt ännu smidigare har vi på Spiris nu lanserat en direktkoppling mellan vår ekonomiplattform och Fortnox. Denna funktion är utformad för att spara tid och minska manuell datahantering genom att låta information flöda sömlöst mellan systemen.

## Vad innebär uppdateringen?

Tidigare har överföring av data ofta krävt manuell export och import av filer. Med den nya kopplingen kan du nu hämta bokföringsdata och skicka tillbaka verifikationer direkt via Fortnox API. Detta skapar ett mer effektivt arbetsflöde för både redovisningskonsulter och företagare.

### Nyckelfunktioner i kopplingen:

*   **Import av SIE4-data:** Hämta bokföringsdata direkt från Fortnox utan att behöva hantera lösa filer.
*   **Bilagor för kund- och leverantörsreskontra:** Överför relevanta underlag och bilagor för att få ett komplett beslutsunderlag i Skatt & Bokslut.
*   **Export av verifikationer:** När du är klar i Skatt & Bokslut kan du skicka färdiga verifikationer direkt tillbaka till Fortnox.

## För dig som är utvecklare eller administratör

Integrationen bygger på Fortnox moderna API och använder säkra autentiseringsmetoder för att säkerställa att data överförs korrekt och tryggt. 

*   **Teknisk bas:** Lösningen använder Fortnox.NET.SDK för stabil kommunikation med deras API.
*   **Sömlös autentisering:** Genom att använda OAuth-flöden kan användaren enkelt godkänna kopplingen mellan Spiris och Fortnox direkt i webbläsaren.
*   **Konfiguration:** Inställningar för omdirigerings-URI och klientautentisering hanteras centralt i plattformens konfigurationsfiler för att säkerställa hög driftsäkerhet.

## Så här kommer du igång

För att börja använda kopplingen behöver du ha ett aktivt abonnemang för både Skatt & Bokslut och Fortnox.

1.  Gå till vyn för dataimport i Skatt & Bokslut.
2.  Välj Fortnox som källa för din import.
3.  Följ instruktionerna på skärmen för att logga in på Fortnox och godkänna att Spiris får läsa och skriva data.
4.  När kopplingen är upprättad kan du välja vilken period du vill hämta data för.

Genom att använda denna koppling minskar risken för fel vid manuell inmatning, och du får mer tid över till rådgivning och analys istället för administration. Vi hoppas att detta ska göra din arbetsdag lite enklare och roligare!
