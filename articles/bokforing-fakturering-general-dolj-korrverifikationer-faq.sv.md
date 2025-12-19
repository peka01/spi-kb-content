---
title: Dölj korrverifikationer (Faq)
slug: general-dolj-korrverifikationer-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-19T08:43:15.440Z'
updatedAt: '2025-12-19T08:43:15.440Z'
id: Qno4c94fpivvUxCmwSFR
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
  guidelineVersions:
    faq: 1
    constitution: 1
    getting_started: 1
    news: 2
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
# Dölj korrverifikationer i din bokföring

För att göra din bokföring mer överskådlig och minska bruset i dina rapporter har vi lagt till en funktion som gör det möjligt att dölja korrigeringsverifikationer. Här hittar du svar på de vanligaste frågorna om hur det fungerar i Spiris.

## Hur döljer jag korrigeringsverifikationer i mina rapporter?

När du skapar rapporter, till exempel en huvudbok, kan du nu välja att filtrera bort verifikationer som har korrigerats. 

1. Gå till den rapport du vill skapa.
2. Leta efter kryssrutan **Dölj korrverifikationer** i urvalsmenyn.
3. Markera rutan och klicka på knappen för att visa eller skriva ut rapporten.

Nu visas endast de verifikationer som faktiskt påverkar ditt resultat, medan de som tagits ut av en korrigering döljs.

## Vilka verifikationer döljs när jag använder funktionen?

Funktionen är smart nog att identifiera verifikationer som helt tar ut varandra. För att en verifikation ska döljas krävs det att:

*   Det finns en ursprunglig verifikation och en tillhörande korrigeringsverifikation.
*   De har exakt samma belopp men med motsatta tecken (debet och kredit har bytt plats).
*   De är bokförda på samma datum.

Om en korrigering bara delvis ändrar en tidigare bokning, eller om den är gjord på ett annat datum, kommer båda verifikationerna fortfarande att synas för att säkerställa att din historik är korrekt och spårbar.

## Varför ser jag fortfarande vissa korrigeringar trots att jag valt att dölja dem?

Det beror oftast på att korrigeringen inte är en direkt "spegling" av ursprungsverifikationen. Om du till exempel har korrigerat ett belopp genom att lägga till en ny post, snarare än att vända på hela den gamla posten, räknas det inte som en 1:1-korrigering. 

Spiris döljer endast de verifikationer där nettot av den ursprungliga posten och korrigeringen blir noll på alla rader, för att du aldrig ska råka dölja information som faktiskt påverkar saldot på dina konton.

## Blir bokföringen felaktig om jag döljer dessa poster?

Nej, inte alls! Att dölja korrverifikationer är bara en visuell inställning för att göra det lättare för dig att läsa dina rapporter. Alla verifikationer finns kvar i bakgrunden precis som vanligt, och ditt bokföringsmässiga resultat påverkas inte. Det blir helt enkelt bara lite snyggare och mer lättläst när du vill stämma av dina konton.

### Relaterade länkar
*   [Skapa huvudbok]
*   [Korrigera en verifikation]
