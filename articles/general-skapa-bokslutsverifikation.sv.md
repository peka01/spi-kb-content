---
id: FmU1TyeznkiP2QgKKoXI
title: Skapa bokslutsverifikation
slug: general-skapa-bokslutsverifikation
languages:
  - sv
format: md
status: draft
folderId: vZ6IMwn3WcrkxEemzXO8
createdAt: '2026-01-21T08:17:14.791Z'
updatedAt: '2026-01-27T07:43:00.633Z'
publishedAt: null
pendingReview: false
reviewedAt: '2026-01-23T11:32:41.441Z'
lastLLMUpdateAt: null
translationBase: {}
languageUpdatedAt:
  sv: '2026-01-27T07:42:08.888Z'
updatedBy: per.karlsson@visma.com
currentVersion: 2
updatedByName: Per Karlsson
metadata:
  tags: []
  area2: ''
  solution: ''
  area1: ''
  visibility: public
  guidelineVersions:
    instruction: 1
    constitution: 1
    getting_started: 2
    tone_voice: 1
    faq: 1
    news: 3
    article_matching: 1
---
# Skapa bokslutsverifikation

Efter att bokslutsarbetet slutförts fastställs årets resultat och eventuella dispositioner genom en bokslutsverifikation. Denna process nollställer resultaträkningen och överför årets vinst eller förlust till företagets egna kapital i balansräkningen, vilket säkerställer en korrekt övergång till efterföljande räkenskapsår.

## Förutsättningar
Innan bokslutsverifikationen upprättas bör följande kontrolleras:
* Samtliga kund- och leverantörsfakturor, periodiseringar samt avskrivningar är bokförda.
* Eventuella bokslutsdispositioner är beräknade och fastställda.
* Skatteberäkningen är genomförd i systemets bokslutsmodul.

## Tillvägagångssätt

1. Navigera till **Bokslut** och välj fliken **Färdigställande**.
2. Verifiera att checklistan är markerad som slutförd och klicka därefter på **Skapa bokslutsverifikation**.
3. Granska det genererade förslaget i dialogrutan. Verifikationen dateras automatiskt per räkenskapsårets sista dag och tilldelas nästa lediga nummer i aktuell verifikationsserie.
4. Säkerställ att beloppet för "Årets resultat" överensstämmer med fastställd resultaträkning.
5. Välj **Bokför**. Verifikationen registreras därefter i bokföringen och bokslutet anses formellt genomfört.

## Exempel på kontering
Nedan följer två vanligt förekommande exempel på hur bokslutsverifikationen kan struktureras:

### Exempel 1: Aktiebolag med vinst
* **Konto 8999 (Årets resultat):** Debet (kontot nollställs).
* **Konto 2099 (Årets resultat):** Kredit (vinsten överförs till eget kapital).

### Exempel 2: Skatt på årets resultat
* **Konto 8910 (Skatt på årets vinst):** Debet (redovisning av skattekostnad).
* **Konto 2510 (Skatteskulder):** Kredit (skuld till Skatteverket).

## Justeringar och korrigeringar
Om felaktigheter identifieras efter att verifikationen skapats kan denna raderas och genereras på nytt, förutsatt att räkenskapsåret ännu inte har låsts. 

> **Viktigt att notera:** När bokslutet är fastställt bör räkenskapsåret låsas för att förhindra att ytterligare transaktioner registreras på den avslutade perioden av misstag.

## Rekommendationer
Vi rekommenderar att en preliminär balans- och resultatrapport jämförs med värdena i bokslutsmodulen innan verifikationen slutgiltigt bokförs. Detta för att säkerställa att inga manuella korrigeringar har påverkat resultatet på ett oförutsett sätt.

## Mer information
- [Arbeta med bokslutskontroller](link-to-article)
- [Hantera skatteberäkning](link-to-article)
- [Avsluta räkenskapsår i bokföringen](link-to-article)
