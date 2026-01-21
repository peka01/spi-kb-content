---
id: YARiDM51q82pcd2nJRTk
title: Nettosemester
slug: general-nettosemester
languages:
  - sv
  - en
format: md
status: test
folderId: IKNKCDDC45TUZXBVLz0i
createdAt: '2026-01-21T08:57:04.214Z'
updatedAt: '2026-01-21T12:41:42.878Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
currentVersion: 4
languageUpdatedAt:
  en: '2026-01-21T12:10:37.294Z'
  sv: '2026-01-21T12:41:32.077Z'
translationBase: {}
updatedBy: Per.Karlsson@visma.com
updatedByName: Per Karlsson
metadata:
  targetAudience: []
  tags:
    - update
    - general
    - instruction
  productId: Lön
  area2: ''
  cshAnchors:
    - app_angularrecon_analysis_appendix
  guidelineVersions:
    instruction: 7
    constitution: 1
    tone_voice: 1
    getting_started: 2
    faq: 1
    news: 3
    article_matching: 1
  visibility: public
  solution: Lön
  area1: general
---
# Hantera SEM för intermittenta anställda

Nettosemester är en beräkningsmetod som anpassar antal semesterdagar och semesterlön efter en anställds faktiska arbetsdagar i förhållande till en heltidstjänst. Denna funktion är särskilt användbar för intermittenta anställda, det vill säga personer som arbetar färre dagar per vecka än vad som är standard på företaget (exempelvis tre dagar i veckan istället för fem). 

Genom att använda nettosemester ser plattformen till att den anställde får rätt antal betalda dagar och korrekt semesterlön per dag, utan att du behöver göra manuella omräkningar.

## Så här gör du

### 1. Aktivera nettosemester
För nya företag är nettosemester förvalt som beräkningsmetod. Om du har ett befintligt företag kan du själv välja att byta metod.

1. Gå till **Inställningar - Löneinställningar**.
2. Välj fliken **Semester**.
3. Under rubriken för beräkningsmetod markerar du alternativet **Nettosemester**.
4. Klicka på **Spara**.

### 2. Uppdatera arbetsscheman
När du har aktiverat nettosemester behöver plattformen veta vad som räknas som heltid på företaget för att beräkningen ska bli korrekt.

1. Gå till **Inställningar - Löneinställningar - Arbetsscheman**.
2. Öppna de scheman som används.
3. Kontrollera eller fyll i fältet **Företagets ordinarie veckoarbetsdagar vid heltid**. Som standard är detta ofta 5 dagar.
4. Värdet i detta fält används för att räkna ut den anställdes "nettofaktor" (den anställdes arbetsdagar delat med företagets heltidsdagar).

### 3. Hantera semester i anställningsregistret
I anställningsregistret kan du nu se hur nettosemestern påverkar de anställda.

1. Gå till **Personal - Anställda** och välj en anställd.
2. Under fliken **Semester** ser du nu märkningen **Intermittent anställd** om personens schema innebär färre arbetsdagar än heltid.
3. Du ser även en ny kolumn för **Nettovärde**. Här visas hur många faktiska semesterdagar den anställde har att ta ut baserat på sitt schema.
4. Om du har gjort manuella ändringar av semesterdagar som du vill ångra, kan du klicka på ikonen **Återställ till standard** (en pil som snurrar) för att återgå till systemets beräknade värden.

## Hur beräkningen fungerar
När nettosemester används räknas antalet betalda semesterdagar om enligt formeln:
*Bruttosemesterdagar x (Genomsnittlig veckoarbetstid i dagar / Veckoarbetsdagar vid heltid)*

**Exempel:**
En anställd har rätt till 25 semesterdagar (brutto) men arbetar 4 dagar i veckan på ett företag där heltid är 5 dagar.
*25 x (4 / 5) = 20 nettosemesterdagar.*

Den anställde har då 20 dagar att ta ut, men varje dag är värd mer pengar än en bruttodag, så att den totala semesterlönen för året blir densamma.

## Tips
> Om du byter från bruttosemester till nettosemester i ett pågående år rekommenderar vi att du går igenom företagets alla arbetsscheman. Kontrollera att fältet för ordinarie veckoarbetsdagar vid heltid är korrekt ifyllt för att säkerställa att alla framtida beräkningar blir rätt.

## Mer information
- **Semesterskuldlistan:** Rapporten visar nu nettovärden för både dagar och belopp för att ge en korrekt bild av företagets skuld.
- **Lönespecifikation:** På den anställdes lönespecifikation visas semesterbalansen i hela dagar (avrundat uppåt).
- **Ingångsvärden:** Om du lägger till en ny anställd och använder nettosemester, fyller du i bruttovärden så räknar Spiris automatiskt ut nettovärdet i kolumnen bredvid.
