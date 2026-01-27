---
id: FmU1TyeznkiP2QgKKoXI
title: Skapa bokslutsverifikation
slug: general-skapa-bokslutsverifikation
languages:
  - sv
  - en
format: md
status: draft
folderId: vZ6IMwn3WcrkxEemzXO8
createdAt: '2026-01-21T08:17:14.791Z'
updatedAt: '2026-01-27T08:19:30.477Z'
publishedAt: null
pendingReview: false
reviewedAt: '2026-01-23T11:32:41.441Z'
lastLLMUpdateAt: null
translationBase: {}
updatedBy: per.karlsson@visma.com
updatedByName: Per Karlsson
currentVersion: 5
languageUpdatedAt:
  sv: '2026-01-27T08:04:58.799Z'
metadata:
  tags: []
  area2: ''
  solution: Skatt & Bokslut
  area1: ''
  guidelineVersions:
    instruction: 1
    news: 3
    tone_voice: 1
    faq: 1
    getting_started: 2
    constitution: 1
    article_matching: 1
  visibility: public
---
# Skapa bokslutsverifikation

Bokslutsverifikationen är den avslutande posten i bokföringen för ett räkenskapsår. Den nollställer samtliga intäkts- och kostnadskonton i resultaträkningen och överför årets vinst eller förlust till företagets egna kapital i balansräkningen. Detta säkerställer att nästa räkenskapsår påbörjas med ett nollställt resultat.

## Förutsättningar
Innan du skapar bokslutsverifikationen måste alla affärshändelser för året vara färdigställda. Kontrollera följande:
*   **Kund- och leverantörsfakturor:** Alla fakturor som tillhör räkenskapsåret ska vara bokförda.
*   **Periodiseringar:** Förutbetalda kostnader och upplupna intäkter ska vara justerade.
*   **Avskrivningar:** Årets avskrivningar på anläggningstillgångar ska vara genomförda.
*   **Lager:** Eventuell lagerinventering ska vara bokförd.
*   **Skatteberäkning:** Den beräknade inkomstskatten för aktiebolag ska vara bokförd för att resultatet ska bli korrekt.
*   **Avstämning:** Kontrollera att bankkonton och skattekonto stämmer mot utdrag från bank och Skatteverket.

## Tillvägagångssätt
Följ dessa steg för att generera verifikationen automatiskt i systemet:

1.  Navigera till **Bokslut** > **Färdigställande**.
2.  Välj funktionen **Skapa bokslutsverifikation**.
3.  **Granska underlaget:** Systemet visar en sammanställning av årets resultat. Kontrollera att datering (oftast räkenskapsårets sista dag) och belopp överensstämmer med din fastställda resultaträkning.
4.  **Välj bokföringskonto:** Säkerställ att rätt konto för årets resultat i balansräkningen är valt (t.ex. konto 2099).
5.  Välj **Bokför**. Systemet skapar nu en verifikation som nollställer klass 3–8 och balanserar mot valt konto i klass 2.

## Konteringsexempel
Här visas hur de vanligaste posterna i en bokslutsverifikation ser ut för ett aktiebolag:

### 1. Bokföring av skatt (görs innan bokslutsverifikationen)
Om bolaget har gjort en vinst ska skatten bokföras:
*   **Debet 8910** (Skatt på årets resultat)
*   **Kredit 2510** (Skatteskulder)

### 2. Överföring av årets vinst
När resultaträkningen nollställs förs vinsten över till balansräkningen:
*   **Debet 8999** (Årets resultat)
*   **Kredit 2099** (Årets resultat, balansräkningen)

### 3. Överföring av årets förlust
Om företaget har gått med förlust blir konteringen den omvända:
*   **Debet 2099** (Årets resultat, balansräkningen)
*   **Kredit 8999** (Årets resultat)

## Korrigeringar och låsning
Om du upptäcker fel efter att bokslutsverifikationen har skapats kan den raderas och återskapas, förutsatt att räkenskapsåret inte har låsts. 

*   **Radera:** Gå till verifikationslistan, leta upp bokslutsverifikationen och välj ångra/radera.
*   **Låsa perioden:** När bokslutet är helt klart och deklarationen inskickad bör du låsa räkenskapsåret under **Inställningar** > **Räkenskapsår**. Detta förhindrar att bokföringen ändras av misstag i efterhand, vilket skulle leda till differenser mot den officiella årsredovisningen.

## Mer information
- [Arbeta med bokslutskontroller](link-to-article)
- [Hantera skatteberäkning för aktiebolag](link-to-article)
- [Avsluta räkenskapsår i bokföringen](link-to-article)
- [Checklista inför bokslut](link-to-article)
