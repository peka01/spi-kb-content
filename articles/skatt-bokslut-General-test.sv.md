---
title: test
slug: General-test
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-23T12:19:34.425Z'
updatedAt: '2026-01-23T12:19:34.425Z'
id: tFFPVfJ5ukObQHqAFgVP
metadata:
  productId: Skatt & Bokslut
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
# Koppla Spiris Skatt & Bokslut till Fortnox

Nu kan du smidigt hämta bokföringsdata direkt från Fortnox till Spiris Skatt & Bokslut. Genom att koppla ihop plattformarna slipper du exportera och importera SIE-filer manuellt, vilket sparar tid och minskar risken för fel.

## Förutsättningar

För att använda kopplingen behöver du:
- Ett aktivt abonnemang på Spiris Skatt & Bokslut.
- Inloggningsuppgifter till Fortnox med behörighet att hämta och skicka data via API.

## Så här gör du

### 1. Aktivera kopplingen i Startguiden
När du skapar ett nytt år eller startar ett nytt uppdrag använder du **Startguiden** för att välja varifrån datan ska hämtas.

1. Gå till **Startguiden**.
2. Under valet av datakälla, välj **Fortnox**.
3. Klicka på **Importera från Fortnox**. 
4. Ett fönster öppnas där du får logga in med dina uppgifter för Fortnox. 
5. Godkänn att Spiris får läsa och skriva data till ditt Fortnox-konto.

*Kopplingen är giltig i 30 dagar. Varje gång du importerar eller exporterar data förnyas perioden automatiskt med 30 nya dagar.*

### 2. Importera data och bilagor
När kopplingen är upprättad hämtas bokföringsdatan automatiskt. Som en extra hjälp skapar plattformen automatiskt två viktiga bilagor baserat på din data från Fortnox:
- **Kundfordringar** (konto 1510)
- **Leverantörsskulder** (konto 2440)

Dessa bilagor fylls i med aktuell information från ditt kund- och leverantörsreskontra i Fortnox, vilket gör avstämningen betydligt snabbare.

### 3. Exportera bokslutsverifikationer till Fortnox
När du är klar med dina bokslutsdispositioner och periodiseringar kan du skicka tillbaka dessa som verifikationer till Fortnox.

1. Gå till vyn för bokslutsverifikationer.
2. Klicka på knappen **Exportera bokslutsverifikationer till Fortnox**.
3. En dialogruta visas. Välj i rullistan vilken **Verifikationsserie** som verifikationerna ska bokföras på i Fortnox (exempelvis serie V eller S).
4. Klicka på **Exportera**.

### 4. Hantera datakälla under Underhåll
Om du behöver ändra datakälla i ett pågående ärende kan du göra detta under inställningarna.

1. Navigera till **Underhåll**.
2. Välj **Inställningar** och därefter **Datakälla**.
3. Här kan du välja att byta till **Fortnox** eller se status för din nuvarande koppling.

## Resultat
Dina bokföringsuppgifter hämtas nu direkt in i bokslutsarbetet och dina reskontrabilagor förbereds automatiskt. När arbetet är klart skickas bokslutsverifikationerna direkt in i Fortnox bokföring, helt utan manuella mellansteg.

## Felsökning
**Knappen för export är gråmarkerad:**
Detta beror oftast på att din säkerhetsnyckel (token) har löpt ut. Detta händer om det gått mer än 30 dagar sedan din senaste import eller export. För att lösa detta, genomför en ny import från Fortnox för att legitimera dig på nytt.
