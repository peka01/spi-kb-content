---
title: Fortnoxintegrationen (Getting Started)
slug: general-fortnoxintegrationen-getting-started
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-20T14:31:23.310Z'
updatedAt: '2026-01-20T14:31:23.310Z'
id: TDOJWHBtbAkQ5N4iBPXF
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - getting_started
  guidelineVersions:
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
# Kom i gång med Fortnox-integrationen i Skatt & Bokslut

Nu kan du koppla ihop Spiris Skatt & Bokslut direkt med Fortnox via en smidig API-koppling. Det innebär att du slipper manuell hantering av SIE-filer och kan i stället hämta bokföringsdata och skicka tillbaka bokslutsverifikationer med några enkla klick.

### Översikt
Integrationen med Fortnox automatiserar dataflödet mellan din bokföring och ditt bokslutsarbete. Genom att ansluta plattformarna kan du importera all nödvändig bokföringsdata, få automatiskt skapade bilagor för kund- och leverantörsreskontra samt exportera färdiga bokslutsverifikationer direkt tillbaka till Fortnox. Detta sparar tid, minskar risken för fel och ger dig en mer sammanhållen arbetsprocess.

### Viktiga begrepp
*   **API-koppling:** En direkt digital anslutning mellan Spiris och Fortnox som gör att de kan prata med varandra utan mellanhänder.
*   **Token:** En digital "nyckel" som skapas när du loggar in mot Fortnox. Den är giltig i 30 dagar och förnyas automatiskt varje gång du gör en import eller export.
*   **Bokslutsverifikationer (V- och S-serier):** De justeringar och bokslutsposter du skapar i Skatt & Bokslut som sedan skickas tillbaka till Fortnox.
*   **SIE4-data:** Det standardiserade format för bokföringsinformation som används vid importen.

---

### Första steg

**Steg 1: Välj Fortnox som datakälla**  
För att börja använda integrationen behöver du ställa in Fortnox som din datakälla. Gå till **Underhåll**, välj **Inställningar** och därefter **Datakälla**. Här väljer du alternativet **Fortnox** i listan över tillgängliga källor.

**Steg 2: Auktorisera kopplingen**  
När du valt Fortnox kommer du att få klicka på en knapp för att logga in. Du skickas då till Fortnox inloggningssida där du anger dina vanliga användaruppgifter för Fortnox. Genom att logga in godkänner du att Spiris får hämta och lämna data i din bokföring. När det är klart skickas du tillbaka till Skatt & Bokslut och kopplingen är aktiv.

**Steg 3: Gör din första import**  
Gå till översikten för din period och klicka på **Import från Fortnox**. Plattformen hämtar nu din bokföringsdata direkt. I samband med importen skapas automatiskt bilagor för **Konto 1510 (Kundfordringar)** och **Konto 2440 (Leverantörsskulder)**, vilket ger dig ett försprång i avstämningen.

---

### Nästa steg

*   **Periodavstämning:** Efter importen kan du arbeta som vanligt med periodavslut och transaktionsanalys precis som vid en vanlig SIE-import.
*   **Exportera bokslutsverifikationer:** När du är klar med dina justeringar väljer du **Exportera bokslutsverifikationer till Fortnox**. I vyn som visas kan du välja vilken verifikationsserie i Fortnox som dina V- och S-verifikationer ska hamna i.
*   **Håll kopplingen vid liv:** Så länge du gör en import eller export minst var 30:e dag hålls din anslutning (token) aktiv. Om det går längre tid behöver du bara göra en ny inloggning mot Fortnox för att återansluta.
*   **Byta datakälla:** Om du senare behöver byta tillbaka till exempelvis manuell SIE-fil, kan du göra detta under **Inställningar** i vyn **Underhåll**.
