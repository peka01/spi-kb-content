---
title: Fortnox integration (Getting Started)
slug: general-fortnox-integration-getting-started
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-13T14:15:42.212Z'
updatedAt: '2026-01-13T14:15:42.212Z'
id: iLE6ShgsYCNKpF1eFXPL
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
# Komma igång med Fortnox-integrationen

Nu kan du koppla ihop Spiris Skatt & Bokslut direkt med Fortnox. Genom denna API-baserade integration slipper du manuell hantering av SIE-filer och kan istället importera bokföringsdata och exportera bokslutstransaktioner med några få klick.

### Översikt
Integrationen med Fortnox är utformad för att göra ditt arbete mer effektivt och minska risken för fel. Genom att upprätta en säker anslutning mellan plattformarna flyttas data sömlöst, vilket ger dig mer tid till analys och rådgivning istället för administration.

### Viktiga begrepp
*   **API-anslutning:** En direkt digital koppling som gör att Skatt & Bokslut kan prata direkt med Fortnox utan att du behöver ladda ner filer till din dator.
*   **Token:** En digital "nyckel" som skapas när du loggar in mot Fortnox. Den är giltig i 30 dagar och förnyas automatiskt varje gång du gör en import eller export.
*   **Bokslutstransaktioner:** De justeringar (V- och S-verifikationer) som du gör i Skatt & Bokslut och som kan skickas direkt tillbaka till huvudbokföringen i Fortnox.
*   **Automatiska bilagor:** Vid import skapar plattformen automatiskt avstämningsbilagor för kund- och leverantörsreskontra.

---

### Första steg

#### Steg 1: Förutsättningar
Innan du börjar behöver du se till att du har tillgång till inloggningsuppgifterna för det Fortnox-abonnemang du vill koppla samman med Skatt & Bokslut.

#### Steg 2: Konfiguration och anslutning
Du kan ställa in Fortnox som datakälla antingen via **Startguiden** när du skapar ett nytt uppdrag, eller i ett befintligt uppdrag under **Underhåll** > **Inställningar** > **Datakälla**.

1.  Välj **Fortnox** som datakälla.
2.  Klicka på knappen för att ansluta eller importera. Du skickas då till Fortnox inloggningsportal.
3.  Logga in med dina uppgifter och godkänn att Spiris får läsa och skriva data. 
4.  När kopplingen är klar skickas du tillbaka till Skatt & Bokslut.

#### Steg 3: Din första import
När anslutningen är upprättad är det dags att hämta data:

1.  Gå till **Översikt** och välj **Importera från Fortnox**.
2.  Bokföringsdatan hämtas nu direkt in i ditt bokslut.
3.  Kontrollera dina bilagor. Plattformen har nu automatiskt skapat bilagor för **Kundfordringar (konto 1510)** och **Leverantörsskulder (konto 2440)** baserat på reskontradatan från Fortnox.

---

### Nästa steg

När du har arbetat klart med ditt bokslut och gjort dina justeringar kan du enkelt skicka tillbaka resultatet till Fortnox:

*   **Exportera bokslutshändelser:** Gå till vyn för bokslutstransaktioner och välj **Exportera bokslutshändelser till Fortnox**.
*   **Välj verifikationsserie:** I den ruta som visas kan du välja i vilken verifikationsserie i Fortnox som dina V- och S-verifikationer ska hamna.
*   **Transaktionsanalys:** Du kan använda funktionerna för transaktionsanalys och periodavstämning på precis samma sätt som när du arbetar med SIE-filer, men med fördelen att datan alltid är uppdaterad direkt från källan.

Om din koppling (token) skulle löpa ut ser du en instruktion om att logga in på nytt nästa gång du försöker hämta eller skicka data. Det är en säkerhetsåtgärd för att skydda din ekonomiska information.
