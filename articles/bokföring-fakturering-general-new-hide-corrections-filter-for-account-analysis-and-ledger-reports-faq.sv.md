---
title: New 'Hide Corrections' Filter for Account Analysis and Ledger Reports (Faq)
slug: >-
  general-new-hide-corrections-filter-for-account-analysis-and-ledger-reports-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-08T13:23:18.632Z'
updatedAt: '2026-01-08T13:23:18.632Z'
id: TztOijzkjAbkQAlai9Z6
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
    getting_started: 2
    news: 3
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
# Hur fungerar filtret "Dölj korrigeringar" i bokföringen?

För att göra din bokföring mer överskådlig och minska det visuella bruset har vi infört en ny funktion i Spiris. Nu kan du enkelt dölja verifikationer som har korrigerats helt och hållet, vilket gör att du kan fokusera på de siffror som faktiskt betyder något för ditt resultat.

### Vad innebär ändringen?
När du rättar en verifikation i Spiris skapas ofta en korrigeringsverifikation som vänder på den ursprungliga bokningen. Detta är nödvändigt för bokföringens spårbarhet, men det kan göra att listor och rapporter ser röriga ut med många extra rader.

Med det nya filtret **Dölj korrigeringar** kan du dölja dessa par av verifikationer (ursprunglig post + korrigering) så länge de har samma transaktionsdatum. Om en korrigering i sin tur har blivit korrigerad, ser funktionen till att även dessa döljs, så att endast den slutgiltiga, korrekta posten visas.

### Hur använder jag filtret?

Du hittar funktionen på två ställen i din ekonomiplattform:

**1. I Kontoanalysen**
När du granskar dina konton kan du aktivera filtret för att få en renare vy:
*   Gå till **Bokföring** och välj **Kontoanalys**.
*   Filtret är tillgängligt på samtliga flikar: **Huvudbok**, **Balansräkning** och **Resultaträkning**.
*   Markera rutan **Dölj korrigeringar** för att rensa vyn.

**2. I Rapporter**
När du ska skriva ut eller förhandsgranska rapporter kan du välja att dölja korrigeringar för att göra rapporten mer lättläst:
*   Gå till **Utskrifter** och välj rapporten **Huvudbok**.
*   Innan du skapar rapporten, markera kryssrutan **Dölj korrigeringar**.

### Bra att veta
*   **Samma datum krävs**: För att en korrigering ska döljas måste den ha samma transaktionsdatum som originalet. Detta är för att säkerställa att ditt saldo alltid stämmer överens med verkligheten vid varje givet tillfälle.
*   **Delvisa korrigeringar visas**: Om en verifikation bara har korrigerats delvis, eller om korrigeringen gjorts på ett annat datum, kommer raderna fortfarande att synas. Detta garanterar att du alltid har full kontroll på din data.
*   **Information direkt i vyn**: Vid filtret i **Kontoanalys** finns en liten informationsikon (i). Om du håller muspekaren över den får du en kort påminnelse om vilka kriterier som gäller för att poster ska döljas.

Genom att använda **Dölj korrigeringar** får du en betydligt tydligare bild av din ekonomi, utan att tumma på bokföringens noggrannhet.

### Relaterade länkar
*   [Skapa manuell verifikation](https://example.com/sv-se/manual-journal-entry)
*   [Rätta en bokföringspost](https://example.com/sv-se/correct-entry)
