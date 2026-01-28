---
id: T2H6OMx7qwxezvL03Q68
title: Add new print for all years in Skatt & Bokslut (+7 more)
slug: General-add-new-print-for-all-years-in-skatt-bokslut-7-more
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2026-01-28T07:50:47.333Z'
updatedAt: '2026-01-28T07:52:57.862Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
languageUpdatedAt:
  sv: '2026-01-28T07:52:26.866Z'
  en: '2026-01-28T07:50:47.333Z'
updatedBy: per.karlsson@visma.com
updatedByName: Per Karlsson
translationBase: {}
currentVersion: 1
metadata:
  area1: General
  solution: Skatt & Bokslut
  area2: ''
  tags:
    - update
    - General
    - instruction
  productId: H9lmIe7pbreUwWDp3K3X
  visibility: public
  guidelineVersions:
    constitution: 1
    instruction: 1
    getting_started: 2
    tone_voice: 1
    article_matching: 1
    news: 7
    faq: 1
  targetAudience: []
---
# Exportera och arkivera företagets dokumentation

I Spiris Skatt & Bokslut kan du nu enkelt exportera företagets data för ett eller flera år samtidigt. Detta är en värdefull funktion när du behöver arkivera räkenskaperna enligt lagkrav eller vill spara ner all dokumentation för att ha en lokal kopia.

Denna funktion är tillgänglig för alla användare, oavsett om du har ett aktivt abonnemang eller om företaget befinner sig i läsläge.

## Förutsättningar
För att kunna exportera dokumentation behöver du ha behörighet att arbeta i **Spiris Skatt & Bokslut**.

## Så här gör du
Följ dessa steg för att skapa din export:

1. Gå till menyn och välj ****{{resource:Menu_title_Maintenance}}**** – **Exportera data**.
2. Markera kryssrutan för **Dokumentation**.
3. Under rubriken **Räkenskapsår**, klicka i rullistan och välj de år du vill inkludera i exporten. Om du vill exportera allt kan du välja alternativet **Alla år**.
4. (Valfritt) Håll muspekaren över informationsikonen (tooltip) till höger om valet för dokumentation för att se detaljerad information om vad exporten innehåller och vilket format den levereras i.
5. Klicka på knappen **Exportera**.
6. En förloppsindikator visas nu som håller dig uppdaterad om hur exporten fortskrider. Medan exporten pågår är knappen inaktiverad.

## Resultat
När exporten är klar får du en bekräftelse och kan ladda ner en ZIP-fil. Inuti ZIP-filen är din data logiskt organiserad för att det ska vara enkelt att hitta rätt:

*   **Toppnivå**: Mappar namngivna efter räkenskapsår.
*   **Undernivå**: Mappar för varje period inom året.
*   **Dokument**: PDF-filer med all relevant dokumentation för den specifika perioden (exempelvis skattebilagor, årsredovisning, avstämningar och transaktionsanalyser).

**Observera:** För att hålla exporten relevant inkluderas endast perioder som innehåller automatiska kontroller, klarmarkerade konton eller minst en kommentar.

## Felsökning
Om något dokument i exporten inte kan skapas (exempelvis på grund av ett ovanligt filformat eller tekniskt fel), kommer du att få en avisering om detta.

*   **Delvis lyckad export**: Om de flesta dokument kunde skapas men något enstaka misslyckades, visas meddelandet "Rapporten misslyckades delvis men genererades ändå". 
*   **Felmeddelande**: Om ett fel uppstår visas en vit sida med information om vilket specifikt dokument det gäller och vad som orsakade problemet, så att du kan åtgärda det och försöka igen.
