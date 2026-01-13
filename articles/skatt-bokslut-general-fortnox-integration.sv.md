---
title: Fortnox integration
slug: general-fortnox-integration
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-13T14:15:14.629Z'
updatedAt: '2026-01-13T14:15:14.629Z'
id: ZpWu9MI4GsOljbWRs7l0
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
# Anslut till Fortnox för automatisk dataöverföring

Genom att koppla ihop Spiris Skatt & Bokslut direkt med Fortnox via ett API kan du hämta bokföringsdata och skicka tillbaka bokslutshändelser helt sömlöst. Detta gör att du slipper ladda ner och ladda upp SIE-filer manuellt, vilket sparar tid och minskar risken för fel.

## Så här gör du

### Koppla ihop plattformarna och hämta data

1. Gå till **Startguiden** eller välj **Underhåll** – **Inställningar** – **Datakälla**.
2. Välj **Fortnox** som din datakälla.
3. Klicka på **Importera från Fortnox**. Du skickas nu till Fortnox inloggningssida.
4. Logga in med dina uppgifter från Fortnox och godkänn kopplingen.
5. När anslutningen är klar hämtas bokföringsdatan automatiskt till Skatt & Bokslut.

När importen är klar skapas automatiskt bilagor för **Kundfordringar (konto 1510)** och **Leverantörsskulder (konto 2440)** baserat på informationen från Fortnox.

### Exportera bokslutshändelser till Fortnox

När du är klar med dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutshändelserna (V- och S-verifikationer) direkt till Fortnox.

1. Navigera till vyn för export av bokslutshändelser.
2. Klicka på knappen **Exportera bokslutshändelser till Fortnox**.
3. I rutan som visas väljer du vilken **Verifikationsserie** i Fortnox som dina verifikationer ska hamna i.
4. Klicka på **Exportera** för att skicka över informationen.

## Tips
> **Säker anslutning:** Din inloggning är giltig i 30 dagar. Varje gång du gör en ny import eller export förnyas perioden automatiskt med 30 nya dagar. Om det har gått längre tid än så behöver du bara logga in på nytt för att återaktivera kopplingen.

## Mer information
- **Transaktionsanalys:** Precis som vid import av SIE-filer kan du använda funktionerna för transaktionsanalys och periodavslut på den data du hämtat från Fortnox.
- **Aktivitetslogg:** Du kan följa statusen för dina importer och exporter under fliken för aktivitetsloggen i vyn för underhåll.
