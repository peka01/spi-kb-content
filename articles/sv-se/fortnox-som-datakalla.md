---
id: article-1764775811669-se2s8bnw6
title: Fortnox som datakälla
slug: fortnox-som-datakalla
format: md
status: draft
folderId: null
createdAt: '2025-12-03T15:30:11.669Z'
updatedAt: '2025-12-03T15:37:15.386Z'
publishedAt: null
metadata:
  productId: Skatt & Bokslut
  area1: ''
  area2: ''
  tags:
    - update
  locale: sv
---
# Förbättringar för Fortnox-import i Visma Skatt & Bokslut

## Översikt
Denna artikel beskriver de senaste förbättringarna och nya funktionerna för integrationen med Fortnox i Visma Skatt & Bokslut. Dessa uppdateringar gör det enklare att importera data, hantera din Fortnox-anslutning och säkerställer bättre datakvalitet genom förbättrad validering. Du kan nu tydligare se vilket Fortnox-företag som är anslutet och enklare koppla bort anslutningen vid behov.

## Prerequisites
För att kunna använda Fortnox-integrationen behöver du:
- Ett aktivt Visma Skatt & Bokslut-konto.
- Ett aktivt Fortnox-konto med nödvändiga behörigheter för att exportera data.
- En aktiv koppling mellan Visma Skatt & Bokslut och ditt Fortnox-konto.

## Steg

### 1. Ansluta till Fortnox och visa företagsuppgifter
Om du inte redan har anslutit ditt Fortnox-konto kan du göra det under inställningarna. När anslutningen är etablerad, eller om du redan är ansluten, kommer du nu tydligare att se information om det anslutna Fortnox-företaget direkt i gränssnittet.

1.  **Navigera till inställningar:** Gå till `Inställningar` (eller motsvarande menyalternativ för integrationer).
2.  **Välj Fortnox-integration:** Leta upp avsnittet för `Fortnox-anslutning` eller `Importkällor`.
3.  **Anslut eller verifiera anslutning:**
    *   Om du inte är ansluten, följ instruktionerna för att logga in på ditt Fortnox-konto och godkänna anslutningen.
    *   Om du redan är ansluten, kommer du att se namnet på det Fortnox-företag som är kopplat.
    *   **(Bild: Skärmbild som visar var Fortnox-företagets namn visas och eventuell tooltip för mer information.)**
    *   Håll muspekaren över företagsnamnet för att se ytterligare information via en tooltip, vilket ger dig en snabb överblick över den aktuella anslutningen.

### 2. Importera data från Fortnox
Nu kan du importera relevant data från Fortnox direkt till Visma Skatt & Bokslut. Detta förenklar processen för att få in uppgifter som behövs för din boksluts- och deklarationsprocess.

1.  **Starta importen:** Gå till den funktion där du normalt importerar data, t.ex. `Import av bokföringsdata` eller `Företagsimport`.
2.  **Välj Fortnox som källa:** I listan över tillgängliga importkällor, välj `Fortnox`.
3.  **Följ importguiden:** Systemet kommer att guida dig genom de steg som krävs för att välja vilken data du vill importera och slutföra processen. Importtexterna har justerats för att vara tydligare och mer informativa.
    *   **(Bild: Skärmbild som visar val av Fortnox som importkälla och de justerade importtexterna.)**

### 3. Förbättrad validering av organisationsnummer
Vid import av företag från Fortnox har valideringen av organisationsnummer förbättrats. Detta minskar risken för felaktig data och säkerställer att informationen om dina företag är korrekt.

*   Om ett organisationsnummer inte uppfyller kraven eller är felaktigt, kommer systemet att ge dig tydligare feedback, vilket hjälper dig att korrigera eventuella fel innan importen slutförs.

### 4. Koppla bort Fortnox-företag
Du har nu möjlighet att enkelt koppla bort ett Fortnox-företag från Visma Skatt & Bokslut om du inte längre behöver integrationen eller om du vill ansluta ett annat företag.

1.  **Navigera till
