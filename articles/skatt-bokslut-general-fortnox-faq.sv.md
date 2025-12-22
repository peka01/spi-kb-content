---
title: Fortnox (Faq)
slug: general-fortnox-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-22T14:59:54.440Z'
updatedAt: '2025-12-22T14:59:54.440Z'
id: Lqfmul0kYDlQbGhiALWY
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - faq
  guidelineVersions:
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
Här hittar du svar på de vanligaste frågorna gällande de senaste uppdateringarna i Spiris Skatt & Bokslut, med fokus på förbättrad hantering av koncernredovisning, verifikationer och integrationer.

## Varför visas en varning om valutaformat när jag skapar en ny period i koncernredovisningen?
För att säkerställa att dina finansiella rapporter blir korrekta och konsekventa har vi lagt till en kontroll av valutaformatet. När du skapar en ny period i din koncernredovisning känner plattformen av om det valda valutaformatet skiljer sig från föregående period. 

Om en skillnad upptäcks visas en varningsruta. Detta är till för att förhindra att siffror tolkas felaktigt i de sammanställda rapporterna. Du kan då välja att korrigera formatet direkt eller gå vidare om ändringen är avsiktlig.

## Kan jag redigera verifikationer som kommer från externa funktioner?
Ja, vi har gjort det enklare att hantera systemgenererade verifikationer (till exempel de som kommer via avstämningar). Du kan nu redigera dessa verifikationer under förutsättning att de ännu inte har förts över till ditt ekonomisystem. 

Om verifikationen har statusen **Ej överförd** eller **Intern** kan du göra justeringar direkt i vyn för **Manuella verifikationer**. När överföringen väl är genomförd låses verifikationen för redigering för att bibehålla spårbarheten mellan Spiris och ditt bokföringsprogram.

## Vad innebär uppdateringen för importen från Fortnox?
Vi har optimerat hur information från externa källor, som Fortnox, läses in och presenteras i plattformen. Uppdateringen innebär bland annat:
*   Tydligare namngivning av importkällor i listor och dialogrutor.
*   Stabilare synkronisering av räkenskapsår och perioder.
*   Förbättrad felhantering vid import, vilket gör det lättare att se om något behöver åtgärdas i källdata.

## Hur påverkas borttagning av byråkonton?
För administratörer som hanterar stora byråstrukturer har vi förbättrat säkerheten och logiken vid borttagning av konton. När ett byråkontor tas bort säkerställer plattformen nu att alla kopplingar och identiteter hanteras korrekt i bakgrunden. Detta minskar risken för att kvarliggande data skapar problem vid framtida uppsättningar och ger en renare datastruktur för hela byrån.

## Relaterade länkar
*   Läs mer om hur du arbetar med koncernredovisning i vår kom-igång-guide.
*   Se instruktioner för hur du importerar data från Fortnox under inställningar för import.
