---
id: tFWkveiYr9hUV5pYuWdm
title: Nettosemester (Faq)
slug: general-nettosemester-faq
languages:
  - sv
format: md
status: draft
folderId: null
createdAt: '2026-01-21T08:57:18.299Z'
updatedAt: '2026-01-27T11:10:31.594Z'
publishedAt: null
pendingReview: true
reviewedAt: '2026-01-27T10:47:11.644Z'
lastLLMUpdateAt: '2026-01-27T11:10:31.093Z'
currentVersion: 2
metadata:
  guidelineVersions:
    news: 3
    tone_voice: 1
    getting_started: 2
    article_matching: 1
    instruction: 1
    faq: 1
    constitution: 1
---
# Vanliga frågor om nettosemester

Här har vi samlat svar på de vanligaste frågorna om beräkningsmetoden för nettosemester i Spiris. Denna funktion är särskilt hjälpsam för dig som har anställda som arbetar färre dagar per vecka än företagets standard (intermittent anställda).

## Vad innebär nettosemester?
Nettosemester är en beräkningsmetod som anpassar antalet semesterdagar och semesterlönen baserat på den anställdes faktiska arbetsdagar i förhållande till en heltidsvecka. Istället för att dra semesterdagar även på dagar då personen inte skulle ha arbetat (bruttosemester), räknar plattformen om dagarna till nettodagar. 

Detta innebär att en anställd som arbetar deltid får färre semesterdagar, men varje dag är värd mer pengar. Slutresultatet blir detsamma i ledighet och ersättning, men administrationen blir betydligt enklare då du bara registrerar semester på de dagar den anställde faktiskt skulle ha arbetat.

## Hur aktiverar jag nettosemester för mitt företag?
För nystartade företag i Spiris är nettosemester förvalt som standard. Om du har ett befintligt företag kan du själv välja att byta metod.

1. Gå till **Inställningar**.
2. Välj **Löneinställningar** och fliken **Semester**.
3. Under rubriken **Beräkningsmetod för semester** väljer du **Nettosemester**.
4. Klicka på **Spara**.

**Observera:** När du byter från bruttosemester till nettosemester rekommenderar vi att du ser över företagets arbetsscheman för att säkerställa korrekta beräkningar.

## Vad behöver jag uppdatera i arbetsscheman?
För att beräkningen ska bli korrekt behöver plattformen veta vad som räknas som en full arbetsvecka på ditt företag. 

I varje arbetsschema under **Inställningar** > **Löneinställningar** > **Arbetsscheman** finns fältet: **Företagets ordinarie veckoarbetsdagar vid heltid**. Som standard är detta inställt på 5 dagar, men du kan ändra det om ditt företag har en annan standardvecka. Detta värde ligger till grund för hur de anställdas semesterdagar räknas om.

## Hur ser jag vilka anställda som är intermittenta?
En anställd räknas som intermittent om hen arbetar färre dagar per vecka än företagets standard för heltid. Du kan identifiera dessa personer på följande ställen:

*   **Anställdas register**: På fliken **Semester** visas en markering eller informationsbubbla som anger att den anställde är intermittent.
*   **Semesterskuldlistan**: I rapporten visas texten **Intermittent anställd** vid de personer det berör.
*   **Ingångsvärden**: När du fyller i värden visas information om att beräkningen sker enligt nettometoden.

## Hur beräknas semesterdagarna för en intermittent anställd?
Plattformen använder följande formel för att räkna ut antalet betalda semesterdagar (för semestervillkor 10 och 20):

**Betalda semesterdagar (brutto) × (Genomsnittlig veckoarbetstid i dagar / Veckoarbetsdagar vid heltid)**

Antalet dagar avrundas alltid uppåt till hela dagar för att säkerställa att den anställde får sin rättmätiga ledighet.

## Kan jag återställa manuella ändringar av semesterdagar?
Ja, om du har gjort manuella justeringar av antalet semesterdagar i anställningsregistret och vill gå tillbaka till plattformens ursprungliga beräkning finns en funktion för detta. 

Klicka på ikonen **Återställ till standard** (visas som en roterande pil) vid fälten för semesterdagar på fliken **Semester**. När du för muspekaren över ikonen visas texten **Återställ antal dagar till semesterårets ursprungsvärde**.

## Hur påverkas semesterskuldlistan?
När du använder nettosemester kommer **Semesterskuldlistan** automatiskt att visa nettovärden för både dagar och belopp. Om en anställd byter arbetsschema under året kommer listan att ta hänsyn till detta och visa de uppdaterade värdena baserat på det schema som gäller vid rapporttillfället.

### Relaterade länkar
*   Instruktioner för semesterårsavslut
*   Hantera arbetsscheman för deltidstjänster
