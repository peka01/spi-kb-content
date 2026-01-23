---
title: BS
slug: General-bs
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-23T13:07:51.827Z'
updatedAt: '2026-01-23T13:07:51.827Z'
id: Ox9a7tk2HTEa6ymfaBOG
metadata:
  productId: H9lmIe7pbreUwWDp3K3X
  solution: Skatt & Bokslut
  area1: General
  area2: ''
  targetAudience: []
  tags:
    - update
    - General
    - instruction
  guidelineVersions:
    instruction: 1
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    tone_voice: 1
---
# Arbeta med översikten för balansavstämning

I den här artikeln lär du dig hur du använder översikten för balansavstämning i Spiris för att få full kontroll på företagets balanskonton vid period- och årsavslut. Du får en tydlig bild av transaktioner, bilagor och eventuella differenser.

## Introduktion
Översikten i **Balansavstämning** samlar alla balanskonton som har bokförda transaktioner fram till den period du arbetar med. Här kan du analysera enskilda konton på djupet, hantera bilagor och kvalitetssäkra arbetet steg för steg.

## Förutsättningar
För att kunna använda funktionen behöver du ha en aktiv period eller ett pågående årsavslut i Spiris där bokföringsdata har importerats.

## Steg för steg

### 1. Hitta och anpassa översikten
Du hittar översikten under menyvalen för både **Periodavslut** och **Årsavslut**.

1. Navigera till **Balansavstämning - Översikt**.
2. För att välja vilka kolumner som ska visas klickar du på knappen **Dölj/Lägg till kolumn** (kugghjulsikonen) i fönstrets övre del.
3. Markera de kolumner du vill se eller välj **Återställ till förvalda kolumner** för att gå tillbaka till standardvyn.
   * *Tips: Dina inställningar sparas per företag och gäller för alla perioder.*

### 2. Utöka detaljnivån med kontoanalys
Om du vill titta närmare på de verifikationer som ligger bakom ett saldo kan du använda drill down-funktionen.

1. Håll pekaren över ett belopp i översikten. Om beloppet blir blått och understruket är det klickbart.
2. Klicka på beloppet för att öppna fönstret **Kontoanalys**. Detta öppnas i en separat flik så att du kan ha flera analyser öppna samtidigt.
3. I listan ser du verifikationstext, förändring och saldo. Om bokföringen innehåller dimensioner som projekt eller kostnadsbärare visas de första fyra av dessa här.
4. Klicka på pilen bredvid en verifikation för att se exakta debet- och kreditkonteringar.

### 3. Hantera bilagor och dokument
Du kan enkelt koppla underlag direkt till kontona i översikten.

1. I kolumnen **Bilagor** ser du en gemikon. Om den är blå finns redan en bilaga, är den grå saknas underlag.
2. För att lägga till ett nytt underlag klickar du på den grå gemikonen och väljer **Lägg till bilaga**.
3. Om du befinner dig i fönstret **Kontoanalys** kan du klicka på gemet i kolumnen **Bifogade filer** för att se dokument som är kopplade till specifika verifikationer.
4. Du kan välja att ladda ner dokumentet eller klicka på **Lägg till bilaga** för att automatiskt skapa och länka en ny extern bilaga till kontot.

### 4. Kontrollera och klarmarkera
Använd de inbyggda verktygen för att säkerställa att allt är korrekt.

1. **Automatiska kontroller**: Granska symbolerna i kolumnen. Grön betyder ok, röd indikerar en avvikelse och orange betyder att kontrollen inte kunde köras. Klicka på symbolen för detaljer och använd knappen **Klarmarkera kontroll** när du har hanterat en avvikelse.
2. **Avstämningsdifferens**: Om det finns en differens mellan utgående balans och avstämningsbelopp kan du klicka på den blå symbolen i kolumnen **Avstämningsdifferens** för att skapa en bokslutsverifikation direkt.
3. **Status checklista**: Klicka på symbolen i kolumnen för att komma direkt till fliken **Checklista** och besvara kontrollfrågorna.
4. **Klarmarkera**: När du är helt färdig med ett konto markerar du det i kolumnen **Klart**.

### 5. Kvalitetssäkring (för byråer)
Om du arbetar på en redovisningsbyrå kan du använda kolumnen **Kvalitetssäkring** för att dokumentera granskningen.

1. Klicka på ikonen i kolumnen **Kvalitetssäkring**.
2. Välj **Godkänd** (blir grön) eller **Ej godkänd** (blir orange).
3. Om du väljer **Ej godkänd** kan du lämna en kommentar som visas i sidopanelen för den som ska åtgärda kontot.

## Resultat
När du har gått igenom listan är alla konton avstämda, dokumenterade med bilagor och kvalitetssäkrade. Du har nu ett korrekt och väl underbyggt underlag för ditt period- eller årsavslut i Spiris.

## Felsökning
* **Jag ser inte alla kolumner**: Om du arbetar på en mindre skärm döljs vissa kolumner automatiskt. Använd kugghjulsikonen för att manuellt välja vilka du vill prioritera.
* **Kontrollen är orange**: Detta beror ofta på att det saknas jämförelsetal, till exempel om det är företagets första period i plattformen.
* **Kontoanalysen öppnas inte**: Kontrollera om din webbläsare blockerar popup-fönster, då analysen öppnas i en ny flik.
