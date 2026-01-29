---
id: gTVIxgs0Yt1qKUYnsniS
title: Exportera data för arkivering i Skatt & Bokslut
slug: General-exportera-data-för-arkivering-i-skatt-bokslut
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2026-01-29T10:12:33.357Z'
updatedAt: '2026-01-29T10:13:51.755Z'
publishedAt: null
reviewedAt: null
lastLLMUpdateAt: null
updatedBy: per.karlsson@visma.com
languageUpdatedAt:
  sv: '2026-01-29T10:13:27.521Z'
  en: '2026-01-29T10:12:33.357Z'
currentVersion: 1
translationBase: {}
updatedByName: Per Karlsson
metadata:
  solution: Skatt & Bokslut
  tags:
    - instruction
    - update
    - General
  area2: ''
  targetAudience: []
  visibility: public
  area1: General
  guidelineVersions:
    tone_voice: 1
    instruction: 1
    article_matching: 1
    news: 9
    constitution: 1
    faq: 1
    getting_started: 2
  productId: H9lmIe7pbreUwWDp3K3X
---
# Exportera data för arkivering

I Spiris är det enkelt att spara din bokförings- och bokslutsdata för framtiden. Genom den nya exportfunktionen kan du ladda ner all dokumentation för ditt företag i ett strukturerat format, vilket gör det smidigt att arkivera underlag enligt gällande lagkrav.

## Introduktion
Denna funktion skapar en komprimerad fil (ZIP) som innehåller PDF-dokument för de räkenskapsår du väljer. Dokumentationen organiseras automatiskt i mappar baserat på år och period, så att du snabbt kan hitta rätt underlag i efterhand.

Exporten inkluderar perioder där det finns:
* Automatiska kontroller.
* Konton markerade som klara.
* Kommentarer.

## Förutsättningar
För att kunna exportera data behöver du:
* Ha ett aktivt abonnemang eller ha din plattform i läsläge (Read-only).
* Ha behörighet att komma åt menyn för **{{resource:Menu_title_Maintenance}}**.

## Så här gör du
Följ dessa steg för att generera din export:

1. Navigera till menyn ****{{resource:Menu_title_Maintenance}}**** och välj **Exportera data**.
2. Markera alternativet **Dokumentation**.
   * *Tips: Du kan föra muspekaren över informationssymbolen bredvid texten för att se detaljerad information om vad exporten innehåller, såsom skatteberäkningar, årsredovisningsunderlag och avstämningar.*
3. Under rubriken **Räkenskapsår**, klicka i rullistan och markera de år du vill inkludera. Om du vill exportera all tillgänglig data väljer du **Alla år**.
4. Klicka på knappen **Exportera**.
5. En förloppsindikator visas nu som håller dig uppdaterad om hur exporten fortskrider. Medan exporten pågår är knappen inaktiverad.
6. När filen är färdig visas en bekräftelse. Klicka på länken **Ladda ner** i notisen för att spara ZIP-filen på din dator.

## Resultat
När du packar upp den nedladdade ZIP-filen hittar du en tydlig mappstruktur:
* **Huvudnivå**: En mapp för varje valt räkenskapsår.
* **Undermappar**: Inuti varje år finns mappar för respektive period.
* **Filer**: I periodmapparna ligger alla relevanta dokument sparade som PDF-filer, redo för digital arkivering eller utskrift.

## Felsökning
Om något går fel under exporten får du ett meddelande om detta:

* **Delvis lyckad export**: Om en specifik fil inte kan genereras (exempelvis på grund av ett ovanligt format) kommer resten av exporten ändå att slutföras. Du får då en notis om att exporten lyckades delvis.
* **Felmeddelande**: Om exporten misslyckas helt visas ett felmeddelande. Om en specifik PDF orsakar felet kommer en vit sida att visas med information om vilket dokument det gäller och vad som gick fel. Prova då att starta om exporten eller kontrollera det specifika underlaget i plattformen.
