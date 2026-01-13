---
title: Fortnox integration (Faq)
slug: general-fortnox-integration-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-13T14:15:30.341Z'
updatedAt: '2026-01-13T14:15:30.341Z'
id: XWTc9TKXNvX1S4BxzKhc
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
Här hittar du svar på de vanligaste frågorna om den nya direktkopplingen mellan Fortnox och Skatt & Bokslut i Spiris. Genom att använda denna funktion slipper du manuell hantering av SIE-filer och får ett mer automatiserat flöde i ditt bokslutsarbete.

## Hur aktiverar jag kopplingen till Fortnox?

Du kan enkelt aktivera kopplingen antingen via **Startguiden** när du lägger upp ett nytt uppdrag, eller i efterhand under inställningarna.

*   Gå till **Underhåll** och välj **Inställningar**.
*   Under sektionen **Datakälla** väljer du nu **Fortnox** som alternativ.
*   Klicka på **Import från Fortnox**. Du skickas då till Fortnox inloggningssida där du loggar in med dina vanliga uppgifter och godkänner kopplingen.

När kopplingen är klar skapas en säker anslutning som är giltig i 30 dagar. Varje gång du importerar eller exporterar data förnyas dessa 30 dagar automatiskt, så att du i praktiken alltid har en aktiv koppling så länge du arbetar i plattformen.

## Vilka uppgifter hämtas vid en import?

När du väljer att hämta data via Fortnox-kopplingen läser Skatt & Bokslut in all bokföringsdata på samma detaljnivå som en SIE4-fil. Det innebär att du får med dig alla verifikationer och saldon direkt in i ditt bokslut.

Dessutom automatiseras delar av avstämningen:
*   En bilaga skapas automatiskt för **Kundfordringar** (konto 1510).
*   En bilaga skapas automatiskt för **Leverantörsskulder** (konto 2440).

Detta sparar tid och minskar risken för felaktiga överföringar mellan olika vyer.

## Hur skickar jag tillbaka bokslutsverifikationer till Fortnox?

När du är klar med dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutsverifikationerna (V- och S-serier) direkt till Fortnox utan att behöva ladda ner några filer.

1.  Gå till vyn för **Bokslutsverifikationer**.
2.  Klicka på knappen **Exportera bokslutsverifikationer till Fortnox**.
3.  En dialogruta visas där du får välja i vilken **Verifikationsserie** i Fortnox som dina bokslutsverifikationer ska hamna.
4.  Bekräfta genom att klicka på **Exportera**.

Integrationen stödjer i dagsläget export av själva bokföringsorden, däremot skickas inga bilagor med i just detta steg.

## Vad händer om kopplingen till Fortnox bryts?

Om det har gått mer än 30 dagar sedan din senaste överföring, eller om behörigheten av annan anledning upphört, kommer knappen för export att vara inaktiverad. Du ser då ett meddelande som förklarar att anslutningen behöver förnyas.

För att återställa kopplingen klickar du helt enkelt på **Import från Fortnox** igen och genomför en ny inloggning. Därefter fungerar både import och export som vanligt igen.

## Kan jag byta datakälla till Fortnox på ett befintligt uppdrag?

Ja, det går bra. Om du tidigare har använt SIE-filer eller en annan lösning kan du byta till Fortnox under **Underhåll** och **Inställningar**. 

Tänk på att när du byter datakälla gäller samma logik som vid tidigare byten i Skatt & Bokslut – plattformen hjälper dig att hålla ordning på dina saldon, men det är alltid bra att kontrollera att den nya källan stämmer överens med ditt tidigare arbete innan du går vidare.

**Relaterade länkar:**
*   [Arbeta med bokslutsbilagor](example-link)
*   [Hantera verifikationsserier](example-link)
