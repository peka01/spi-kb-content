---
id: 4phkM1coMENAp6FdgpMg
title: Fortnoxintegrationen (Faq)
slug: general-fortnoxintegrationen-faq
languages:
  - sv
format: md
status: draft
folderId: null
createdAt: '2026-01-20T14:31:11.573Z'
updatedAt: '2026-01-20T14:47:58.854Z'
publishedAt: null
pendingReview: true
reviewedAt: null
lastLLMUpdateAt: '2026-01-20T14:47:58.854Z'
metadata:
  area2: ''
  solution: Skatt & Bokslut
  productId: Skatt & Bokslut
  area1: general
  targetAudience: []
  tags:
    - update
    - general
    - faq
  guidelineVersions:
    news: 3
    getting_started: 2
    faq: 1
    instruction: 7
    article_matching: 1
    constitution: 1
    tone_voice: 1
---
# Integration med Fortnox i Skatt & Bokslut

Nu kan du koppla ihop Fortnox direkt med din ekonomiplattform Spiris. Genom denna integration kan du hämta bokföringsdata och skicka tillbaka bokslutsverifikationer helt sömlöst. Det skapar ett sammanhängande arbetsflöde där du slipper hantera SIE-filer manuellt, vilket minskar risken för fel och ger dig mer tid till annat.

## Översikt
Integrationen med Fortnox gör ditt arbete i Skatt & Bokslut betydligt smidigare genom att automatisera överföringen av ekonomisk information. Istället för att ladda ner och ladda upp filer skapas en direktlänk mellan plattformarna för ett effektivt och säkert datautbyte.

**Detta ingår i integrationen:**
*   **Direktimport av bokföringsdata:** Hämtar all data som motsvarar SIE4-formatet.
*   **Automatiska bilagor:** Bilagor för **Kundfordringar** (konto 1510) och **Leverantörsskulder** (konto 2440) skapas och förbereds automatiskt.
*   **Export av bokslutsverifikationer:** Skicka V- och S-serier direkt till Fortnox.
*   **Flexibel export:** Du väljer själv vilken verifikationsserie i Fortnox som bokslutsjusteringarna ska hamna i.

---

## Kom igång med Fortnox-koppling

För att börja använda dessa funktioner behöver du ansluta ditt Fortnox-konto som datakälla i Spiris.

1.  Gå till **Underhåll** och välj **Inställningar**.
2.  Klicka på **Datakälla**.
3.  Välj **Fortnox** i listan över tillgängliga källor.
4.  Klicka på knappen för att importera från Fortnox. Du skickas då till Fortnox inloggningsportal.
5.  Logga in med dina Fortnox-uppgifter och godkänn kopplingen.

När kopplingen är klar skapas en säkerhetsnyckel (token) som är giltig i 30 dagar. Varje gång du väljer att hämta eller skicka data förnyas dessa 30 dagar automatiskt, vilket gör att kopplingen håller sig levande så länge du arbetar aktivt.

---

## Importera data och automatiska bilagor

När du hämtar data från Fortnox läser Spiris in alla verifikationer och saldon på ett ögonblick. En stor fördel för dig är att plattformen automatiskt förbereder bilagor för dina reskontrakonton:
*   **Konto 1510:** Bilaga för kundreskontra skapas automatiskt.
*   **Konto 2440:** Bilaga för leverantörsreskontra skapas automatiskt.

Detta automatiserade steg minskar det manuella arbetet vid periodavslut och årsbokslut avsevärt.

---

## Exportera bokslutsverifikationer till Fortnox

När du är klar med dina justeringar i Skatt & Bokslut kan du skicka tillbaka bokslutsverifikationerna direkt till Fortnox för att säkerställa att bokföringen är synkroniserad.

1.  Gå till vyn för **Bokslutsverifikationer**.
2.  Välj alternativet för att exportera till Fortnox.
3.  En ruta visas där du får välja vilken verifikationsserie i Fortnox som dina verifikationer ska tillhöra.
4.  Klicka på **Exportera**.

*Bra att veta: Om det har gått mer än 30 dagar sedan din senaste import kan du behöva logga in på nytt för att återaktivera kopplingen innan du kan genomföra exporten.*

---

## Vanliga frågor (FAQ)

### Hur vet jag om min koppling till Fortnox är aktiv?
Om knappen för export är gråmarkerad eller om du ser ett meddelande om att nyckeln har gått ut, behöver du bara genomföra en ny import. När du loggar in på nytt förnyas anslutningen i 30 dagar.

### Vilken data hämtas vid en import?
Integrationen hämtar all bokföringsdata som normalt ingår i en SIE4-fil. Det innebär att du får med dig alla verifikationer, kontoplaner och saldon som behövs för ditt bokslutsarbete.

### Kan jag byta från SIE-fil till Fortnox-integration under pågående år?
Ja, det går utmärkt. Du ändrar enkelt datakälla under **Underhåll** > **Inställningar** > **Datakälla**. Logiken för att byta källa fungerar på samma sätt som när du byter mellan olika filtyper.

### Skapas bilagorna för kund- och leverantörsreskontra varje gång?
Ja, vid varje import från Fortnox genereras dessa bilagor automatiskt baserat på den dagsaktuella datan som finns i Fortnox vid importtillfället.

### Kan jag välja vilken serie verifikationerna hamnar i hos Fortnox?
Ja, vid exporten får du upp en lista med de verifikationsserier som finns upplagda i ditt Fortnox-abonnemang, så att du har full kontroll på var dina bokslutsjusteringar landar.

---

**Relaterade länkar:**
*   [Läs mer om periodavslut i Spiris](#)
*   [Hantering av bilagor och kontoavstämning](#)
