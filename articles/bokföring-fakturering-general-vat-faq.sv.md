---
title: VAT (Faq)
slug: general-vat-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2025-12-22T13:06:55.129Z'
updatedAt: '2025-12-22T13:06:55.129Z'
id: GFVhZcQzISCRztaZfQZt
metadata:
  productId: Bokföring & Fakturering
  solution: Bokföring & Fakturering
  area1: general
  area2: ''
  targetAudience: []
  tags:
    - update
    - general
    - faq
  guidelineVersions:
    faq: 1
    constitution: 1
    getting_started: 2
    news: 3
    article_matching: 1
    instruction: 7
    tone_voice: 1
---
# Vanliga frågor: Tydligare momsredovisning i Spiris

Här hittar du svar på de vanligaste frågorna om den senaste uppdateringen av momsdeklarationen i Spiris. Vi har gjort det enklare för dig att snabbt förstå resultatet av din momsredovisning.

### Vad innebär uppdateringen av momsdeklarationen?
Vi har förbättrat logiken i momsdeklarationen för att göra det ännu tydligare för dig som användare. Nu räknar plattformen automatiskt ut om det slutgiltiga beloppet innebär att du ska betala in moms eller om du ska få moms tillbaka. Texten i rapporten anpassas dynamiskt baserat på dina siffror, vilket minskar risken för missförstånd när du läser av din deklaration.

### Hur ser jag om jag ska betala eller få pengar tillbaka?
I fältet för den slutgiltiga momssumman, **Fält 49**, visas nu en tydlig beskrivning. 
*   Om den ingående momsen (den moms du betalat på inköp) är högre än den utgående momsen (den moms du tagit betalt för), kommer det framgå att beloppet är moms att få tillbaka.
*   Om den utgående momsen är högre, ändras texten så att det tydligt framgår att beloppet är moms att betala.

### Vilka uppgifter ligger till grund för beräkningen?
Spiris sammanställer automatiskt information från flera olika delar av din bokföring för att beräkningen ska bli korrekt. Plattformen tittar på:
*   **Utgående moms på försäljning:** Beloppen i **Fält 10, 11 och 12**.
*   **Utgående moms på inköp:** Beloppen i **Fält 30, 31 och 32**.
*   **Utgående moms på import:** Beloppen i **Fält 60, 61 och 62**.
*   **Ingående moms:** Det totala beloppet i **Fält 48**.

Genom att jämföra summan av all utgående moms med den ingående momsen i **Fält 48**, kan systemet fastställa exakt vad som ska stå vid **Fält 49**.

### Varför är denna ändring bra för mig?
Syftet är att ge dig en mer lätthanterlig ekonomiplattform där du slipper fundera på om ett belopp är en skuld eller en fordran. Genom att vi förtydligat rubrikerna i själva formuläret och i den utskrivna rapporten får du bättre kontroll och sparar tid i din vardagliga administration.

**Relaterade länkar:**
*   Skapa momsdeklaration
*   Kontrollera din bokföring inför momsredovisning
