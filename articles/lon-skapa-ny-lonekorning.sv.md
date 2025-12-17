---
lastLLMUpdateAt: '2025-12-11T10:31:26.115Z'
reviewedAt: '2025-12-11T10:32:14.970Z'
slug: skapa-ny-lonekorning
status: draft
updatedAt: '2025-12-17T07:51:35.620Z'
folderId: S0n4lfJ2K5VQ3piaOGtw
title: Skapa ny lönekörning
createdAt: '2025-12-17T07:51:35.620Z'
publishedAt: null
pendingReview: false
languages:
  - sv
  - en
format: md
currentVersion: 5
id: article-1765957895620-jamzy8nx9
metadata:
  targetAudience: []
  tags:
    - update
  area1: ''
  solution: Lön
  productId: Lön
  area2: ''
---
# Skapa en ny lönekörning i Spiris **{{resource:Common_Product_Name_Variable_eAccCloudPayroll}}**

## Översikt
Den här artikeln beskriver hur du skapar en ny lönekörning i Spiris Lön. Genom att följa stegen nedan kan du enkelt initiera en lönekörning för att hantera ordinarie löneutbetalningar eller extra utbetalningar.

## Förutsättningar
*   Du har åtkomst till Spiris **{{resource:Common_Product_Name_Variable_eAccCloudPayroll}}**.
*   Alla obligatoriska fält i anställningsregistret för de anställda som ska ingå i lönekörningen är ifyllda. För att en anställd ska visas i listan när du skapar en ny lönekörning måste alla obligatoriska fält i anställningsregistret vara ifyllda.
*   Anställningsdatumet för de anställda är tidigare än eller inom den aktuella löneperioden.
*   Om anställda har gjort registreringar i Resor & Utlägg, se till att alla utlägg för perioden är sammanställda innan du skapar lönekörningen.

## Steg för att skapa en ny lönekörning

1.  **Navigera till Lönekörningar:**
    *   Välj **Lön** i menyn.
    *   Klicka sedan på **Lönekörningar**.

2.  **Starta en ny lönekörning:**
    *   Klicka på knappen **Ny lönekörning**.

3.  **Välj typ av lönekörning:**
    *   Välj antingen **Ordinarie lön** eller **Extra utbetalning** i listrutan.
        *   **Ordinarie lön:** Hämtar automatiskt alla registreringar för den aktuella perioden och uppgifter från "Återkommande lönerader" i anställningsregistret. Du kan även importera registreringar från funktioner som Anställd, Tid & Projektplanering och Resor & Utlägg genom att markera "Importera registreringar".
        *   **Extra utbetalning:** Skapar tomma lönebesked för valda anställda. Detta är användbart för till exempel bonusutbetalningar.

4.  **Ange beskrivning (valfritt):**
    *   Du kan lägga till en beskrivning för lönekörningen om du vill.

5.  **Ange utbetalningsdatum:**
    *   Välj det datum då lönen ska betalas ut till de anställda under **Utbetalningsdatum**. Systemet föreslår ett datum baserat på föregående lönekörning, men du kan ändra det.
    *   **Observera:** Om det valda datumet infaller på en helgdag eller helg, eller ligger långt fram i tiden, visas en varning. Se till att betalningsfilen skickas till banken i tid för att utbetalningen ska ske på valt datum. Om datumet du vanligtvis betalar ut lönerna infaller på en röd dag, väljer du närmaste bankdag som utbetalningsdatum.

6.  **Importera registreringar (vid behov):**
    *   Om du vill importera registreringar från andra delar av Spiris (t.ex. Anställd, Tid & Projektplanering, Resor & Utlägg eller Byråstöd) markerar du rutan **Importera registreringar**.
    *   Om du i dina löneinställningar har valt att registreringar alltid ska importeras vid lönekörning, är denna ruta redan markerad. Du kan avmarkera den om du inte vill importera registreringar för just denna körning. Du kan även importera registreringar efter att lönekörningen har skapats.

7.  **Välj anställda:**
    *   Kontrollera att alla anställda som ska ingå i lönekörningen har en markering i rutan till vänster om deras namn i listan.

8.  **Skapa lönekörningen:**
    *   Klicka på knappen **Skapa**.

Nu är lönekörningen skapad och du kan fortsätta med att registrera och komplettera uppgifterna på de anställdas lönebesked.

## Fältförklaringar

### Typ av lönekörning
*   **Ordinarie lön:** När du väljer **Ordinarie lön** hämtas alla registreringar i kalendern för den aktuella perioden, samt de uppgifter som finns under **Återkommande lönerader** på fliken **Lön** i anställningsregistret. Registreringar gjorda i funktionerna Anställd, Tid & Projektplanering och Resor & Utlägg kan importeras till en lönekörning av typen **Ordinarie lön**. Du hämtar dessa registreringar genom att klicka på **Importera registreringar**.
*   **Extra utbetalning:** Om du väljer **Extra utbetalning** skapas tomma lönebesked för anställda som har en markering i rutan till vänster. Det är exempelvis användbart om du en eller ett par gånger per år betalar ut en bonus till alla eller några anställda.

### Beskrivning
Det är valfritt att ange beskrivning för lönekörningen.

### Utbetalningsdatum
Om föregående lönekörning är avslutad föreslås utbetalningsdatum, men du kan välja annat datum. En varning visas om datumet infaller på en lördag, söndag, helgdag, eller om det är ett datum långt fram i tiden. Se till att betalningsfilen skickas till banken i tid för att utbetalningen ska ske på valt datum.

### Importera registreringar
Markera **Importera registreringar** om du vill importera registreringar gjorda i Anställd, Tid & Projektplanering, Resor & Utlägg eller Byråstöd när lönekörningen skapas. Om du i löneinställningarna har valt att registreringar ska importeras vid varje lönekörning är rutan **Importera registreringar** markerad. Du kan avmarkera rutan om du inte vill att importen ska göras till denna lönekörningen. Du kan även importera registreringarna efter att lönekörningen är skapad.

Vill du alltid importera registreringar från tilläggstjänster när ny lönekörning skapas kan du välja **Inställningar - Löneinställningar**, fliken **Löner och utbetalningar** och markera rutan **Importera registreringar när lönekörning skapas**.

### Månadslön
Här visas löne- och avvikelseperiod utifrån de inställningar som är gjorda för företaget under **Inställningar - Löneinställningar**, fliken **Löner och utbetalningar**. Läs mer i avsnittet Löneinställningar.

### Timlön
Här visas löne- och avvikelseperiod utifrån de inställningar som är gjorda för företaget under **Inställningar - Löneinställningar**, fliken **Löner och utbetalningar**. Läs mer i avsnittet Löneinställningar.

### Löneform
Här kan du filtrera urvalet på anställda med månadslön eller timlön. Du kan kombinera detta val med personalkategori så att exempelvis endast tjänstemän med månadslön tas med på lönekörningen.

### Personalkategori
Här kan du filtrera urvalet på tjänstemän eller arbetare. Du kan kombinera detta val med löneform så att exempelvis endast tjänstemän med månadslön tas med på lönekörningen.

## Relaterade artiklar
*   [Hantera rapporter i Resor & Utlägg]
*   [Löneinställningar]
