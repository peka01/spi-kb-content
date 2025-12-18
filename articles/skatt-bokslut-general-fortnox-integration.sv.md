---
title: Fortnox integration
slug: general-fortnox-integration
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-18T12:00:02.117Z'
updatedAt: '2025-12-18T12:00:02.117Z'
id: 2oTgOQaCaA0zU4dNcMGw
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
---
# Kom igång med Fortnox-integrationen

## Översikt
Nu kan du koppla ihop Spiris Skatt & Bokslut direkt med Fortnox för att smidigt hämta din bokföringsdata via API. Integrationen gör det möjligt att både importera data för analys och bokslut, samt att skicka tillbaka dina bokslutstransaktioner direkt till Fortnox när du är klar. Detta sparar tid och minskar risken för fel vid manuell filhantering.

## Så här fungerar det

### Välj Fortnox som datakälla
Du kan välja Fortnox som källa för din bokföringsdata antingen när du startar ett nytt år eller via inställningarna.

1. Gå till **Startguiden** eller navigera till **Underhåll - Inställningar - Datakälla**.
2. Välj alternativet **Fortnox**.
3. Klicka på knappen **Importera från Fortnox**.
4. Du skickas nu till Fortnox inloggningsportal. Logga in med dina vanliga uppgifter för Fortnox och godkänn kopplingen till Spiris.
5. När kopplingen är klar skapas en säker anslutning (en så kallad token) som är giltig i 30 dagar. Denna förnyas automatiskt varje gång du väljer att importera eller exportera data.

### Importera data
När anslutningen är upprättad kan du hämta din bokföring.

*   Klicka på **Importera från Fortnox** på översiktssidan.
*   Plattformen hämtar verifikationer och saldo.
*   Vid importen skapas automatiskt två bilagor för att underlätta ditt arbete: en för **Kundfordringar (konto 1510)** och en för **Leverantörsskulder (konto 2440)**.
*   Du kan nu använda funktionerna för periodavslut och transaktionsanalys precis som vid en vanlig SIE4-import.

### Exportera bokslutstransaktioner
När du har gjort dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutstransaktionerna till Fortnox som verifikationer.

1. Gå till vyn för **Bokslutstransaktioner**.
2. Klicka på knappen **Exportera bokslutstransaktioner till Fortnox**.
3. En dialogruta öppnas där du får välja vilken verifikatserie i Fortnox som transaktionerna ska bokföras i.
4. Kontrollera att rätt serie är vald och klicka på **Exportera**.
5. Transaktionerna skickas nu över och får statusen exporterad i listan.

*Observera: Om kopplingen till Fortnox har löpt ut behöver du göra en ny import för att återansluta innan du kan exportera.*

### Hantera kopplingen
Om du behöver byta datakälla eller avbryta kopplingen gör du detta under underhållsmenyn.

*   Gå till **Underhåll - Inställningar - Datakälla**.
*   Här kan du välja att klicka på **Koppla ifrån företag** för att ta bort anslutningen till Fortnox.
*   Om du vill byta till en annan källa, till exempel en SIE-fil, kan du göra det härifrån med samma logik som tidigare.

## Bra att veta
*   **Säkerhet:** Plattformen kontrollerar att organisationsnumret i Fortnox matchar det företag du arbetar med i Skatt & Bokslut för att säkerställa att data hamnar rätt.
*   **Begränsningar:** Precis som vid filimport finns det begränsningar för filstorlek (100 MB) och antal objekt (t.ex. kostnadsställen) för att bibehålla god prestanda.
*   **Aktivitetslogg:** Du kan se status för dina importer och exporter i aktivitetsloggen under systemuppgifter.

## Relaterade artiklar
- [Arbeta med transaktionsanalys]
- [Hantera bokslutstransaktioner]
- [Inställningar för datakällor]
