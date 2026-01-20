---
title: Fortnoxintegrationen (Faq)
slug: general-fortnoxintegrationen-faq
languages:
  - sv
format: md
status: draft
folderId: null
publishedAt: null
createdAt: '2026-01-20T14:31:11.573Z'
updatedAt: '2026-01-20T14:31:11.573Z'
id: 4phkM1coMENAp6FdgpMg
metadata:
  productId: Skatt & Bokslut
  solution: Skatt & Bokslut
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
# Integration med Fortnox i Skatt & Bokslut

Nu kan du koppla ihop Fortnox direkt med din ekonomiplattform Spiris. Genom denna API-baserade integration kan du hämta bokföringsdata och skicka tillbaka bokslutsverifikationer helt sömlöst, utan att behöva hantera SIE-filer manuellt.

## Översikt
Integrationen med Fortnox gör ditt arbete i Skatt & Bokslut betydligt smidigare. Istället för att ladda ner och upp SIE-filer skapas en direktlänk mellan plattformarna. 

**Detta ingår i integrationen:**
*   Direktimport av bokföringsdata (motsvarande SIE4-format).
*   Automatisk skapande av bilagor för Kundfordringar (konto 1510) och Leverantörsskulder (konto 2440).
*   Export av bokslutsverifikationer (V- och S-serier) direkt till Fortnox.
*   Möjlighet att välja specifik verifikationsserie vid export.

---

## Kom igång med Fortnox-koppling

För att börja använda integrationen behöver du först ansluta ditt Fortnox-konto som datakälla i Spiris.

1.  Gå till **Underhåll** och välj **Inställningar**.
2.  Klicka på **Datakälla**.
3.  Välj **Fortnox** i listan över tillgängliga källor.
4.  Klicka på knappen för att importera från Fortnox. Du skickas då till Fortnox inloggningsportal.
5.  Logga in med dina Fortnox-uppgifter och godkänn kopplingen.

När kopplingen är klar skapas en säkerhetsnyckel (token) som är giltig i 30 dagar. Varje gång du importerar eller exporterar data förnyas dessa 30 dagar automatiskt.

---

## Importera data och automatiska bilagor

När du väljer att hämta data från Fortnox läser Spiris in alla verifikationer och saldon. En stor fördel är att plattformen automatiskt skapar och förbereder bilagor för dina reskontrakonton:
*   **Konto 1510:** Bilaga för kundreskontra skapas automatiskt.
*   **Konto 2440:** Bilaga för leverantörsreskontra skapas automatiskt.

Detta sparar tid och minskar risken för manuella fel vid periodavslut och årsbokslut.

---

## Exportera bokslutsverifikationer till Fortnox

När du är klar med dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutsverifikationerna direkt till Fortnox.

1.  Gå till vyn för **Bokslutsverifikationer**.
2.  Välj alternativet för att exportera till Fortnox.
3.  En ruta visas där du får välja vilken verifikationsserie i Fortnox som dina V- och S-verifikationer ska tillhöra.
4.  Klicka på **Exportera**.

*Observera: Om det har gått mer än 30 dagar sedan din senaste import kan du behöva logga in på nytt för att återaktivera kopplingen innan du kan exportera.*

---

## Vanliga frågor (FAQ)

### Hur vet jag om min koppling till Fortnox är aktiv?
Om knappen för export är gråmarkerad eller om du ser ett meddelande om att nyckeln har gått ut, behöver du bara genomföra en ny import. Då loggar du in på nytt och anslutningen förnyas i 30 dagar.

### Vilken data hämtas vid en import?
Integrationen hämtar all bokföringsdata som normalt ingår i en SIE4-fil. Det innebär att du får med dig alla verifikationer, kontoplaner och saldon som behövs för ditt bokslutsarbete.

### Kan jag byta från SIE-fil till Fortnox-integration under pågående år?
Ja, det går bra att byta datakälla under **Underhåll** > **Datakälla**. Logiken för att byta källa fungerar på samma sätt som när du byter mellan olika filtyper.

### Skapas bilagorna för kund- och leverantörsreskontra varje gång?
Ja, vid varje import från Fortnox genereras dessa bilagor automatiskt baserat på den data som finns i Fortnox vid importtillfället.

### Kan jag välja vilken serie verifikationerna hamnar i hos Fortnox?
Ja, vid exporten får du upp en lista med de verifikationsserier som finns upplagda i ditt Fortnox-abonnemang, så att du kan styra bokslutsjusteringarna till rätt serie.

---

**Relaterade länkar:**
*   [Läs mer om periodavslut i Spiris](#)
*   [Hantering av bilagor och kontoavstämning](#)
