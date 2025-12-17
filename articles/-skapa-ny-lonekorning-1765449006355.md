---
reviewedAt: '2025-12-11T10:32:14.970Z'
updatedAt: '2025-12-17T07:19:10.980Z'
slug: '-skapa-ny-lonekorning-1765449006355'
pendingReview: false
title: Skapa ny lönekörning
createdAt: '2025-12-17T07:19:10.980Z'
folderId: S0n4lfJ2K5VQ3piaOGtw
format: md
publishedAt: null
currentVersion: 4
status: draft
languages:
  - sv
  - en
lastLLMUpdateAt: '2025-12-11T10:31:26.115Z'
id: article-1765955950980-99t6wpm0q
metadata:
  area2: ''
  solution: Lön
  tags:
    - update
  productId: Lön
  area1: ''
  targetAudience: []
contentByLanguage:
  en: >-
    # Create a New Payroll Run in Spiris Payroll


    ## Overview

    This article describes how to create a new payroll run in Spiris Payroll. By
    following the steps below, you can easily initiate a payroll run to manage
    regular salary payments or extra payments.


    ## Prerequisites

    *   You have access to Spiris Payroll.

    *   All mandatory fields in the employment record for the employees to be
    included in the payroll run are filled in. For an employee to appear in the
    list when you create a new payroll run, all mandatory fields in their
    employment record must be completed.

    *   The employment date for the employees is earlier than or within the
    current payroll period.

    *   If employees have made registrations in Travel & Expenses, ensure that
    all expenses for the period are compiled before you create the payroll run.


    ## Steps to Create a New Payroll Run


    1.  **Navigate to Payroll Runs:**
        *   Select **Payroll** from the menu.
        *   Then click on **Payroll Runs**.

    2.  **Start a New Payroll Run:**
        *   Click the **New Payroll Run** button.

    3.  **Select Payroll Run Type:**
        *   Choose either **Regular Salary** or **Extra Payment** from the dropdown list.
            *   **Regular Salary:** Automatically retrieves all registrations for the current period and data from "Recurring Salary Lines" in the employment record. You can also import registrations from functions such as Employee, Time & Project Planning, and Travel & Expenses by checking "Import Registrations".
            *   **Extra Payment:** Creates blank payslips for selected employees. This is useful for, for example, bonus payments.

    4.  **Enter Description (Optional):**
        *   You can add a description for the payroll run if you wish.

    5.  **Enter Payment Date:**
        *   Select the date when the salary should be paid to the employees under **Payment Date**. The system suggests a date based on the previous payroll run, but you can change it.
        *   **Note:** If the selected date falls on a public holiday or weekend, or is far in the future, a warning will be displayed. Ensure the payment file is sent to the bank in time for the payment to be made on the selected date. If the date you normally pay salaries falls on a non-working day, choose the nearest banking day as the payment date.

    6.  **Import Registrations (If Needed):**
        *   If you want to import registrations from other parts of Spiris (e.g., Employee, Time & Project Planning, Travel & Expenses, or Agency Support), check the **Import Registrations** box.
        *   If you have selected in your payroll settings that registrations should always be imported during a payroll run, this box is already checked. You can uncheck it if you do not want to import registrations for this specific run. You can also import registrations after the payroll run has been created.

    7.  **Select Employees:**
        *   Verify that all employees to be included in the payroll run have a checkmark in the box to the left of their name in the list.

    8.  **Create Payroll Run:**
        *   Click the **Create** button.

    The payroll run is now created, and you can proceed with registering and
    completing the information on the employees' payslips.


    ## Field Explanations


    ### Payroll Run Type

    *   **Regular Salary:** When you select **Regular Salary**, all
    registrations in the calendar for the current period are retrieved, as well
    as the data found under **Recurring Salary Lines** on the **Salary** tab in
    the employment record. Registrations made in the Employee, Time & Project
    Planning, and Travel & Expenses functions can be imported into a **Regular
    Salary** type payroll run. You retrieve these registrations by clicking
    **Import Registrations**.

    *   **Extra Payment:** If you select **Extra Payment**, blank payslips are
    created for employees who have a checkmark in the box to the left. This is
    useful, for example, if you pay out a bonus to all or some employees once or
    twice a year.


    ### Description

    It is optional to provide a description for the payroll run.


    ### Payment Date

    If the previous payroll run is completed, the payment date is suggested, but
    you can choose another date. A warning appears if the date falls on a
    Saturday, Sunday, public holiday, or if it is a date far in the future.
    Ensure the payment file is sent to the bank in time for the payment to be
    made on the selected date.


    ### Import Registrations

    Check **Import Registrations** if you want to import registrations made in
    Employee, Time & Project Planning, Travel & Expenses, or Agency Support when
    the payroll run is created. If you have selected in the payroll settings
    that registrations should be imported with each payroll run, the **Import
    Registrations** box is checked. You can uncheck the box if you do not want
    the import to be made for this payroll run. You can also import the
    registrations after the payroll run has been created.


    If you always want to import registrations from add-on services when a new
    payroll run is created, you can select **Settings - Payroll Settings**, the
    **Salaries and Payments** tab, and check the box **Import registrations when
    payroll run is created**.


    ### Monthly Salary

    This displays the salary and deviation period based on the settings made for
    the company under **Settings - Payroll Settings**, **Salaries and Payments**
    tab. Read more in the Payroll Settings section.


    ### Hourly Wage

    This displays the salary and deviation period based on the settings made for
    the company under **Settings - Payroll Settings**, **Salaries and Payments**
    tab. Read more in the Payroll Settings section.


    ### Salary Form

    Here you can filter the selection by employees with monthly salary or hourly
    wage. You can combine this choice with personnel category so that, for
    example, only salaried employees with a monthly salary are included in the
    payroll run.


    ### Personnel Category

    Here you can filter the selection by salaried employees or hourly workers.
    You can combine this choice with salary form so that, for example, only
    salaried employees with a monthly salary are included in the payroll run.


    ## Related Articles

    *   [Manage Reports in Travel & Expenses]

    *   [Payroll Settings]
  sv: >-
    # Skapa en ny lönekörning i Spiris
    **{{resource:Common_Product_Name_Variable_eAccCloudPayroll}}**


    ## Översikt

    Den här artikeln beskriver hur du skapar en ny lönekörning i Spiris Lön.
    Genom att följa stegen nedan kan du enkelt initiera en lönekörning för att
    hantera ordinarie löneutbetalningar eller extra utbetalningar.


    ## Förutsättningar

    *   Du har åtkomst till Spiris
    **{{resource:Common_Product_Name_Variable_eAccCloudPayroll}}**.

    *   Alla obligatoriska fält i anställningsregistret för de anställda som ska
    ingå i lönekörningen är ifyllda. För att en anställd ska visas i listan när
    du skapar en ny lönekörning måste alla obligatoriska fält i
    anställningsregistret vara ifyllda.

    *   Anställningsdatumet för de anställda är tidigare än eller inom den
    aktuella löneperioden.

    *   Om anställda har gjort registreringar i Resor & Utlägg, se till att alla
    utlägg för perioden är sammanställda innan du skapar lönekörningen.


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

    Nu är lönekörningen skapad och du kan fortsätta med att registrera och
    komplettera uppgifterna på de anställdas lönebesked.


    ## Fältförklaringar


    ### Typ av lönekörning

    *   **Ordinarie lön:** När du väljer **Ordinarie lön** hämtas alla
    registreringar i kalendern för den aktuella perioden, samt de uppgifter som
    finns under **Återkommande lönerader** på fliken **Lön** i
    anställningsregistret. Registreringar gjorda i funktionerna Anställd, Tid &
    Projektplanering och Resor & Utlägg kan importeras till en lönekörning av
    typen **Ordinarie lön**. Du hämtar dessa registreringar genom att klicka på
    **Importera registreringar**.

    *   **Extra utbetalning:** Om du väljer **Extra utbetalning** skapas tomma
    lönebesked för anställda som har en markering i rutan till vänster. Det är
    exempelvis användbart om du en eller ett par gånger per år betalar ut en
    bonus till alla eller några anställda.


    ### Beskrivning

    Det är valfritt att ange beskrivning för lönekörningen.


    ### Utbetalningsdatum

    Om föregående lönekörning är avslutad föreslås utbetalningsdatum, men du kan
    välja annat datum. En varning visas om datumet infaller på en lördag,
    söndag, helgdag, eller om det är ett datum långt fram i tiden. Se till att
    betalningsfilen skickas till banken i tid för att utbetalningen ska ske på
    valt datum.


    ### Importera registreringar

    Markera **Importera registreringar** om du vill importera registreringar
    gjorda i Anställd, Tid & Projektplanering, Resor & Utlägg eller Byråstöd när
    lönekörningen skapas. Om du i löneinställningarna har valt att
    registreringar ska importeras vid varje lönekörning är rutan **Importera
    registreringar** markerad. Du kan avmarkera rutan om du inte vill att
    importen ska göras till denna lönekörningen. Du kan även importera
    registreringarna efter att lönekörningen är skapad.


    Vill du alltid importera registreringar från tilläggstjänster när ny
    lönekörning skapas kan du välja **Inställningar - Löneinställningar**,
    fliken **Löner och utbetalningar** och markera rutan **Importera
    registreringar när lönekörning skapas**.


    ### Månadslön

    Här visas löne- och avvikelseperiod utifrån de inställningar som är gjorda
    för företaget under **Inställningar - Löneinställningar**, fliken **Löner
    och utbetalningar**. Läs mer i avsnittet Löneinställningar.


    ### Timlön

    Här visas löne- och avvikelseperiod utifrån de inställningar som är gjorda
    för företaget under **Inställningar - Löneinställningar**, fliken **Löner
    och utbetalningar**. Läs mer i avsnittet Löneinställningar.


    ### Löneform

    Här kan du filtrera urvalet på anställda med månadslön eller timlön. Du kan
    kombinera detta val med personalkategori så att exempelvis endast tjänstemän
    med månadslön tas med på lönekörningen.


    ### Personalkategori

    Här kan du filtrera urvalet på tjänstemän eller arbetare. Du kan kombinera
    detta val med löneform så att exempelvis endast tjänstemän med månadslön tas
    med på lönekörningen.


    ## Relaterade artiklar

    *   [Hantera rapporter i Resor & Utlägg]

    *   [Löneinställningar]
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
