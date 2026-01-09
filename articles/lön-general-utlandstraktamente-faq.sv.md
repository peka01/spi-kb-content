---
id: q0v0j54QDzr62sXw5QFp
title: Utlandstraktamente (Faq)
slug: general-utlandstraktamente-faq
languages:
  - sv
  - en
format: md
status: test
folderId: null
createdAt: '2026-01-08T15:41:16.389Z'
updatedAt: '2026-01-09T10:45:32.224Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
translationBase: {}
updatedBy: Per.Karlsson@visma.com
updatedByName: Per Karlsson
currentVersion: 1
languageUpdatedAt:
  en: '2026-01-09T09:56:34.046Z'
  sv: '2026-01-09T10:33:07.075Z'
metadata:
  locale: sv-se
  tags:
    - update
    - general
    - faq
  productId: Lön
  targetAudience: []
  cshAnchors: []
  area1: general
  area2: ''
  guidelineVersions:
    getting_started: 2
    article_matching: 1
    constitution: 1
    faq: 1
    instruction: 7
    news: 3
    tone_voice: 1
  solution: Lön
  visibility: public
---
## Hur kan jag ändra antal på kopplade lönearter för utlandstraktamente?
Tidigare var det inte möjligt att justera antalet på de lönearter som automatiskt följer med vid utlandstraktamente (exempelvis lönearterna 1215, 1216 och 1217). I och med den senaste uppdateringen har vi öppnat upp för mer flexibilitet.

När du använder snabbvalet för resor, kost och utlägg kan du nu:
* Ändra antal direkt på de kopplade raderna.
* Justera beloppen vid behov.
* Ta bort specifika rader som inte är relevanta för just den resan.

Detta gör att du får full kontroll över registreringen direkt i snabbvalet och slipper korrigera informationen i efterhand på själva lönebeskedet.

## Vad har ändrats vid import från tjänsten Resor & Utlägg?
Vi har förbättrat synkroniseringen mellan den externa tjänsten för utlägg och Spiris Lön. Tidigare kunde det uppstå ett problem där extra, automatiska lönearter dök upp på lönebeskedet trots att de inte fanns med i den ursprungliga utläggsrapporten.

Nu fungerar importen så här:
* Endast de lönearter som faktiskt har registrerats i utläggsrapporten följer med till lönebeskedet.
* Systemet lägger inte längre till extra rader för traktamente som inte efterfrågats.
* Lönebeskedet blir en exakt spegling av det som godkänts i utläggstjänsten, vilket minskar risken för dubbelregistreringar eller felaktiga utbetalningar.

## Vad händer om jag lägger till löneart 1204 manuellt?
Om du väljer att inte använda snabbvalet utan istället registrerar löneart 1204 (Utlandstraktamente) manuellt på en lönerad, har vi nu sett till att logiken följer med på ett korrekt sätt.

När du skriver in löneart 1204 kommer systemet nu automatiskt att föreslå och lägga till de tillhörande kopplade lönearterna. Detta säkerställer att alla delar av traktamentet hanteras korrekt enligt gällande regler, även vid manuell hantering.

**Relaterade länkar:**
* Registrera resor och utlägg
* Hantera lönearter för traktamente
