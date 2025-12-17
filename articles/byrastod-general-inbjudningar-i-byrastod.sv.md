---
status: draft
folderId: zBIiVCqNofH1c30iTZQz
slug: general-inbjudningar-i-byrastod
format: md
currentVersion: 3
title: Inbjudningar i Byråstöd
updatedAt: '2025-12-17T07:50:46.605Z'
createdAt: '2025-12-16T13:58:02.458Z'
publishedAt: null
languages:
  - sv
  - en
id: 5VNi0RwECDdg5mhhvCpL
metadata:
  tags:
    - update
    - general
  productId: Byråstöd
  area1: general
  targetAudience: []
  area2: ''
  solution: Byråstöd
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
