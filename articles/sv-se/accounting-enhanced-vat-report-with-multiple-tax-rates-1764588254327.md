---
title: Enhanced VAT Report with Multiple Tax Rates
slug: accounting-enhanced-vat-report-with-multiple-tax-rates-1764588254327
format: md
status: draft
folderId: null
publishedAt: null
id: article-1764588269562-xofwxzm1b
createdAt: '2025-12-01T11:24:29.562Z'
updatedAt: '2025-12-01T11:24:29.562Z'
metadata:
  productId: Bokföring & Fakturering
  area1: accounting
  area2: vat-reporting
  tags:
    - update
    - accounting
---
# Förbättrad Momsrapport med Flera Skattesatser

Denna artikel finns även tillgänglig på engelska nedan.

## Översikt
Denna artikel beskriver den uppdaterade momsrapporteringsfunktionen i Visma Bokföring & Fakturering, som nu stöder hantering av flera skattesatser inom samma rapporteringsperiod. Du kan nu enkelt generera korrekta momsrapporter även när du har transaktioner med olika momssatser (t.ex. 6%, 12%, 25%) i samma period. Rapporten kategoriserar automatiskt transaktioner per skattesats, vilket ger en tydligare överblick och mer exakta underlag för redovisningen.

## Förutsättningar
- Aktiv prenumeration på Visma Bokföring & Fakturering.
- Tillgång till modulen för momsrapportering.
- Bokförda transaktioner med varierande momssatser inom samma period.

## Steg

1.  ### Navigera till Momsrapporten
    *   Gå till menyn `{{Menu.Redovisning}}` > `{{Momsrapportering}}`.
    *   Välj den period för vilken du vill generera en momsrapport.

2.  ### Granska den förbättrade rapporten
    *   I rapportformuläret (`{{VATReportForm}}`) kommer du nu att se ett nytt avsnitt som bryter ner transaktionerna per momssats. Detta ger en detaljerad bild av hur varje skattesats bidrar till den totala momsen.
    *   Granska sammanfattningen (`{{VATSummary}}`) som nu visar delsummor för varje momssatskategori (t.ex. 6%, 12%, 25%).
    *   *Exempel:* Om ditt företag har sålt både böcker (6% moms) och konsulttjänster (25% moms) under samma månad, kommer rapporten tydligt att visa intäkter och utgående moms separat för varje skattesats.

3.  ### Exportera rapporten (Valfritt)
    *   Klicka på `{{Button.Exportera}}` eller välj `{{ExportOptions}}`.
    *   Välj önskat format (Excel, PDF). Den
