---
format: md
languages:
  - sv
  - en
updatedAt: '2025-12-17T07:19:38.689Z'
slug: general-inbjudningar-i-byrastod-1765893478580
publishedAt: null
title: Inbjudningar i Byråstöd
currentVersion: 2
status: draft
folderId: zBIiVCqNofH1c30iTZQz
createdAt: '2025-12-17T07:19:38.689Z'
id: article-1765955978689-6w9lznirb
metadata:
  solution: Byråstöd
  area2: ''
  tags:
    - update
    - general
  area1: general
  targetAudience: []
  productId: Byråstöd
---
# Förbättrad hantering av inbjudningar i Byråstöd

## Översikt
Den här uppdateringen introducerar förbättringar i hur du hanterar inbjudningar för ärendehantering i Byråstöd. Nu kan du tydligare se och hantera alla begärda samtycken, inklusive de som väntar på beslut eller har avslagits.

## Vad har ändrats?
Tidigare visades alla samtycken oavsett status. Nu, när funktionen för separata flikar för godkända samtycken är aktiv, kommer vyn för begärda samtycken endast att visa de som har statusen "Väntar" eller "Avslagen". Detta ger en tydligare överblick över vilka åtgärder som fortfarande krävs.

Namnen på funktioner och vyer har också uppdaterats för att bättre spegla deras funktion:

*   Metoden `GetGridCaseManagementConsentsAsync` har bytt namn till `GetGridCaseManagementConsentRequestsAsync`.
*   Ajax-anropet `GetConsentsAjax` har bytt namn till `GetConsentRequestsAjax`.

Dessa ändringar gör det enklare att förstå vad som visas och hanteras i de olika delarna av ärendehanteringsinställningarna.

## Användarpåverkan
Ingen negativ påverkan förväntas. Förbättringarna syftar till att ge en tydligare och mer strukturerad överblick över inbjudningar för ärendehantering.

## Relaterade artiklar
*   [Inställningar för ärendehantering](länk-till-relaterad-artikel)
