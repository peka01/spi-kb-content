---
id: yh0nBPvwjnP2j2EjpLbK
title: Fortnoxintegrationen
slug: general-fortnoxintegrationen
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2026-01-20T14:30:58.465Z'
updatedAt: '2026-01-20T14:32:57.719Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
currentVersion: 1
updatedByName: Per Karlsson
updatedBy: Per.Karlsson@visma.com
translationBase: {}
languageUpdatedAt:
  en: '2026-01-20T14:30:58.465Z'
  sv: '2026-01-20T14:32:53.775Z'
metadata:
  targetAudience: []
  tags:
    - update
    - general
    - instruction
  solution: Skatt & Bokslut
  area1: general
  area2: ''
  guidelineVersions:
    faq: 1
    instruction: 7
    constitution: 1
    tone_voice: 1
    news: 3
    article_matching: 1
    getting_started: 2
  visibility: public
  productId: Skatt & Bokslut
---
# Hantera Fortnox-integrationen i Skatt & Bokslut

Genom att koppla samman Spiris Skatt & Bokslut med Fortnox kan du arbeta mer effektivt och säkert med ditt bokslut. Integrationen gör det möjligt att hämta bokföringsdata direkt via ett API och skicka tillbaka bokslutstransaktioner utan att behöva hantera SIE-filer manuellt. Detta minskar risken för fel och sparar värdefull tid.

## Så här gör du

### Anslut Fortnox som datakälla
Du kan välja Fortnox som datakälla antingen när du startar ett nytt uppdrag i **Startguiden** eller genom att ändra inställningarna för ett befintligt uppdrag.

1. Gå till ****{{resource:Menu_title_Maintenance}}**** – **Inställningar** – **Datakälla**.
2. Välj **Fortnox** i listan över tillgängliga datakällor.
3. Klicka på knappen **Importera från Fortnox**.
4. Du skickas nu till Fortnox inloggningsportal. Logga in med dina vanliga uppgifter för Fortnox och godkänn att Spiris får läsa och skriva data.
5. När kopplingen är klar skickas du tillbaka till Skatt & Bokslut och importen påbörjas.

### Importera data och automatiska bilagor
Varje gång du väljer att hämta data från Fortnox synkroniseras bokföringen. Integrationen stödjer även automatisk hantering av vissa bilagor:

*   **Bokföringsdata:** All data importeras på samma sätt som vid en SIE4-import, vilket innebär att du kan använda funktioner som periodavstämning och transaktionsanalys precis som vanligt.
*   **Automatiska bilagor:** Vid import skapar plattformen automatiskt bilagor för **Kundfordringar (konto 1510)** och **Leverantörsskulder (konto 2440)** baserat på informationen i Fortnox.

### Exportera bokslutstransaktioner till Fortnox
När du har gjort dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutstransaktionerna (V- och S-verifikationer) direkt till Fortnox.

1. Gå till vyn för export av data.
2. Välj alternativet **Exportera bokslutstransaktioner till Fortnox**.
3. En dialogruta visas där du får välja vilken **Verifikationsserie** i Fortnox som transaktionerna ska bokföras i.
4. Klicka på **Exportera**. Transaktionerna skickas nu direkt till Fortnox bokföring.

## Tips
> **Håll kopplingen vid liv:** Din inloggning (token) mot Fortnox är giltig i 30 dagar. Varje gång du gör en import eller export förnyas dessa 30 dagar automatiskt. Om knappen för export är gråmarkerad kan det bero på att kopplingen gått ut – gör då en ny import för att aktivera anslutningen igen.

## Mer information
- **Periodavstämning**
- **Arbeta med transaktionsanalys**
- **Skapa och hantera bilagor**
