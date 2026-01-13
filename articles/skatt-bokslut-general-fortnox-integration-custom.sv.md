---
title: Fortnox integration (Custom)
slug: general-fortnox-integration-custom
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-13T15:08:09.357Z'
updatedAt: '2026-01-13T15:08:09.357Z'
id: D5jHPOAfaW7xJjPeIE5v
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
# Direktintegration med Fortnox i Skatt & Bokslut

Nu blir det ännu enklare att arbeta med bokslut och skatt i Spiris. Genom vår nya direktintegration med Fortnox kan du koppla ihop din ekonomiplattform med Skatt & Bokslut för att automatiskt hämta bokföringsdata och skicka tillbaka bokslutsverifikationer. Du slipper helt den manuella hanteringen av SIE-filer, vilket sparar tid och minskar risken för fel.

## Fördelar med integrationen

*   **Smidig start:** Kom igång med ditt bokslutsarbete på några sekunder genom att hämta data direkt via API.
*   **Automatiska bilagor:** När du importerar data skapas automatiskt avstämda bilagor för kundfordringar (konto 1510) och leverantörsskulder (konto 2440).
*   **Tvåvägsflöde:** Du kan skicka tillbaka dina färdiga bokslutsverifikationer (V- och S-serier) direkt till Fortnox.
*   **Alltid uppdaterat:** Du kan enkelt uppdatera din import om bokföringen i Fortnox förändras under arbetets gång.

## Så kommer du igång

Du kan aktivera kopplingen antingen när du skapar ett nytt bokslutsår eller i efterhand via inställningarna.

### Första gången i Startguiden
1.  När du startar ett nytt år i Skatt & Bokslut möts du av **Startguiden**.
2.  Välj **Fortnox** som datakälla bland alternativen.
3.  Klicka på knappen för att ansluta. Du skickas nu till Fortnox inloggningssida.
4.  Logga in med dina vanliga Fortnox-uppgifter och godkänn att Spiris får läsa och skriva data.
5.  När kopplingen är klar skickas du tillbaka till Skatt & Bokslut och importen påbörjas.

### Via inställningar (Underhåll)
Om du redan har påbörjat ett arbete och vill byta datakälla:
1.  Gå till **Underhåll** och välj **Inställningar**.
2.  Under sektionen för **Datakälla**, välj **Fortnox**.
3.  Följ instruktionerna för att logga in och auktorisera kopplingen.

## Importera data och arbeta med bilagor

När kopplingen är upprättad kan du när som helst klicka på **Importera från Fortnox** på översiktssidan. Plattformen hämtar då alla verifikationer och saldon.

I samband med importen skapas två viktiga bilagor automatiskt:
*   **Kundfordringar (Konto 1510):** En bilaga som visar dina utestående kundfakturor hämtas direkt från Fortnox reskontra.
*   **Leverantörsskulder (Konto 2440):** En bilaga som visar dina obetalda leverantörsfakturor hämtas på samma sätt.

Dessa bilagor hjälper dig att snabbt stämma av reskontran mot huvudboken utan manuell handpåläggning.

## Exportera bokslutsverifikationer

När du är klar med dina justeringar och bokslutsverifikationer i Skatt & Bokslut kan du skicka tillbaka dessa till Fortnox.

1.  Gå till vyn för **Bokslutsverifikationer**.
2.  Välj **Exportera bokslutsverifikationer till Fortnox**.
3.  En dialogruta visas där du får välja vilken **Verifikationsserie** i Fortnox som verifikationerna ska hamna i (exempelvis serie V eller S).
4.  Klicka på **Exportera**. Verifikationerna skapas nu direkt i Fortnox som bokförda eller ej bokförda beroende på dina inställningar i Fortnox.

## Bra att veta om säkerhet och anslutning

*   **Säker koppling:** Integrationen använder en säker API-nyckel (token) som är giltig i 30 dagar.
*   **Automatisk förnyelse:** Varje gång du gör en import eller export förnyas din koppling automatiskt med 30 nya dagar.
*   **Om kopplingen bryts:** Om du inte har använt integrationen på över 30 dagar behöver du bara klicka på knappen för att ansluta igen och logga in på nytt hos Fortnox.
*   **Aktivitetslogg:** Under **Underhåll** och **Aktivitetslogg** kan du se status för alla importer som gjorts från Fortnox, vilket ger dig full kontroll över när data senast hämtades.
