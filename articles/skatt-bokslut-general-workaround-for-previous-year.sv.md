---
title: Workaround for previous year
slug: general-workaround-for-previous-year
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-15T11:56:38.796Z'
updatedAt: '2026-01-15T11:56:38.796Z'
id: Dynt1c1jaZoGdjRB4166
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - instruction
  guidelineVersions:
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
# Hantera saknade eller felaktiga jämförelsetal från föregående år

För att din årsredovisning ska vara komplett och följa årsredovisningslagen (ÅRL) krävs det att siffror från det föregående räkenskapsåret finns med som jämförelsetal. Om dessa uppgifter saknas i din ekonomiplattform eller om det uppstår fel vid import (till exempel att en SIE-fil inte balanserar), kan du använda denna guide för att lägga till uppgifterna manuellt.

## Så här gör du

Det finns två sätt att lösa detta på. Det vanligaste är att nollställa tjänsten och använda manuell inmatning för att låsa det föregående året.

### Alternativ 1: Manuell inmatning i Skatt & Bokslut

> **Viktigt:** När du nollställer tjänsten försvinner allt arbete du har gjort i den nuvarande perioden. Vi rekommenderar därför att du kontrollerar föregående års siffror det första du gör när du påbörjar ett nytt bokslut.

1.  Gå till inställningarna för tjänsten och välj att **Nollställ tjänsten**. Bekräfta att du vill radera befintlig data.
2.  Startguiden öppnas nu på nytt. Välj **Manuell inmatning** som datakälla.
3.  Skapa det räkenskapsår som saknas (föregående år) och mata in bokföringsuppgifterna manuellt så att de stämmer med föregående års fastställda årsredovisning.
4.  När siffrorna är korrekta väljer du att **Lås period** för det året.
5.  Gå nu till inställningarna för datakälla och byt tillbaka till **Spiris Bokföring** eller **SIE-fil**. 
6.  Du kommer få en varning om att data kan raderas, men eftersom du har låst föregående år kommer de siffrorna att sparas som jämförelsetal.
7.  Genomför importen för det innevarande året. Nu visas både det aktuella årets siffror och de korrekta jämförelsetalen i din årsredovisning.

### Alternativ 2: Komplettera i din löpande bokföring

Om du hellre vill att informationen ska finnas i din grundläggande bokföring kan du göra följande:

1.  Skapa det saknade räkenskapsåret direkt i ditt bokföringsprogram (t.ex. Spiris Bokföring eller Visma Administration).
2.  Bokför föregående års slutresultat och ställningar som en samlingsverifikation eller genom att importera en korrekt SIE-fil till bokföringsprogrammet.
3.  Gör en ny import till Skatt & Bokslut för den aktuella perioden.

## Tips
> Genom att kontrollera att föregående års siffror ser rätt ut direkt när du skapar årets bokslut slipper du göra om arbetet med balansavstämningar och bilagor om en nollställning skulle bli nödvändig senare.

## Mer information
- Kontrollera att SIE-filen balanserar innan import
- Byta datakälla i Skatt & Bokslut
