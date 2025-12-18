---
id: xUYgEGpkq9Hf6P1jkvgS
title: Dölj korrigeringsverifikationer
slug: dolj-korrigeringsverifikationer
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2025-12-16T08:45:06.743Z'
updatedAt: '2025-12-18T10:32:54.250Z'
publishedAt: null
pendingReview: false
reviewedAt: '2025-12-18T10:30:11.880Z'
lastLLMUpdateAt: '2025-12-18T10:29:34.119Z'
translationBase:
  en: >-
    # Dölj korrigeringsverifikationer i bokföringen


    ## Overview

    I Spiris är det enkelt att hålla din bokföring ren och överskådlig. Genom
    att dölja verifikationer som skapats enbart för att korrigera tidigare
    bokföringsposter slipper du onödigt "brus" i dina listor. Det gör att du kan
    fokusera på de faktiska affärshändelserna och snabbare hitta det du letar
    efter i din ekonomiplattform.


    Denna funktion döljer automatiskt direkta korrigeringar (1:1) i både
    verifikatlistan, kontospecifikationer och i flera av dina rapporter,
    inklusive reskontra för jordbruksföretag.


    ## Steps

    Följ dessa steg för att aktivera eller inaktivera visningen av
    korrigeringsverifikationer:


    1. Gå till **Inställningar** i huvudmenyn.

    2. Välj **Företagsinställningar** och klicka på fliken **Bokföring**.

    3. Markera eller avmarkera rutan för att dölja korrigeringsverifikationer. 

    4. Klicka på **Spara**.


    När inställningen är aktiverad kommer systemet automatiskt att filtrera bort
    de verifikat som är markerade som korrigeringar i dina vyer och rapporter.


    ### Bra att veta

    *   **Krav för att döljas:** Endast direkta korrigeringar där ett verifikat
    rättar ett annat i sin helhet (1:1) döljs. Om en korrigering görs på ett
    annat datum än originalet, eller om den delas upp på flera rader, kommer
    verifikaten fortfarande att visas. Detta är för att säkerställa att dina
    saldon alltid är korrekta i analyser.

    *   **Periodiseringar:** Funktionen omfattar även korrigeringar av
    periodiseringsverifikat.

    *   **Projekt och kostnadsställen:** Om du filtrerar din vy på specifika
    projekt eller kostnadsställen påverkas inte visningen av denna inställning.

    *   **Saldon:** Dina beräknade saldon i rapporter och analyser förblir
    korrekta även när korrigeringarna är dolda.


    ### Här döljs korrigeringarna

    När funktionen är påslagen döljs verifikaten på följande ställen:


    **I vyer:**

    *   **Bokföring** - **Verifikat**

    *   **Kontospecifikationer** - **Reskontra**

    *   **Kontospecifikationer** - **Balans- och Resultaträkning**


    **I rapporter:**

    *   **Verifikatlista**

    *   **Reskontra**

    *   **Reskontra konton** (specifikt för jordbruksföretag)

    *   **Kundreskontra** och **Leverantörsreskontra** (när en hel faktura har
    makulerats)


    ### Processer som stödjer döljning

    Funktionen fungerar vid flera olika typer av korrigeringar, till exempel när
    du väljer **Skapa korrigeringsverifikat** under **Åtgärder** i
    verifikatlistan, eller när du makulerar kund- och leverantörsfakturor. Det
    gäller även vid återkallande av autogiro och när du kvittar
    leverantörsfakturor mot ett konto.


    ## Related Articles

    * [Hantera verifikat i bokföringen]

    * [Inställningar för bokföring]

    * [Korrigera ett bokfört verifikat]
currentVersion: 19
languageUpdatedAt:
  sv: '2025-12-18T10:03:58.543Z'
  en: '2025-12-18T10:03:58.543Z'
metadata:
  targetAudience: []
  area1: Bokföring
  productId: Bokföring & Fakturering
  tags:
    - update
    - general
  area2: ''
  solution: Bokföring & Fakturering
---
# Dölj korrigeringsverifikationer i bokföringen

## Overview
I Spiris är det enkelt att hålla din bokföring ren och överskådlig. Genom att dölja verifikationer som skapats enbart för att korrigera tidigare bokföringsposter slipper du onödigt "brus" i dina listor. Det gör att du kan fokusera på de faktiska affärshändelserna och snabbare hitta det du letar efter i din ekonomiplattform.

Denna funktion döljer automatiskt direkta korrigeringar (1:1) i både verifikatlistan, kontospecifikationer och i flera av dina rapporter, inklusive reskontra för jordbruksföretag.

## Steps
Följ dessa steg för att aktivera eller inaktivera visningen av korrigeringsverifikationer:

1. Gå till **Inställningar** i huvudmenyn.
2. Välj **Företagsinställningar** och klicka på fliken **Bokföring**.
3. Markera eller avmarkera rutan för att dölja korrigeringsverifikationer. 
4. Klicka på **Spara**.

När inställningen är aktiverad kommer systemet automatiskt att filtrera bort de verifikat som är markerade som korrigeringar i dina vyer och rapporter.

### Bra att veta
*   **Krav för att döljas:** Endast direkta korrigeringar där ett verifikat rättar ett annat i sin helhet (1:1) döljs. Om en korrigering görs på ett annat datum än originalet, eller om den delas upp på flera rader, kommer verifikaten fortfarande att visas. Detta är för att säkerställa att dina saldon alltid är korrekta i analyser.
*   **Periodiseringar:** Funktionen omfattar även korrigeringar av periodiseringsverifikat.
*   **Projekt och kostnadsställen:** Om du filtrerar din vy på specifika projekt eller kostnadsställen påverkas inte visningen av denna inställning.
*   **Saldon:** Dina beräknade saldon i rapporter och analyser förblir korrekta även när korrigeringarna är dolda.

### Här döljs korrigeringarna
När funktionen är påslagen döljs verifikaten på följande ställen:

**I vyer:**
*   **Bokföring** - **Verifikat**
*   **Kontospecifikationer** - **Reskontra**
*   **Kontospecifikationer** - **Balans- och Resultaträkning**

**I rapporter:**
*   **Verifikatlista**
*   **Reskontra**
*   **Reskontra konton** (specifikt för jordbruksföretag)
*   **Kundreskontra** och **Leverantörsreskontra** (när en hel faktura har makulerats)

### Processer som stödjer döljning
Funktionen fungerar vid flera olika typer av korrigeringar, till exempel när du väljer **Skapa korrigeringsverifikat** under **Åtgärder** i verifikatlistan, eller när du makulerar kund- och leverantörsfakturor. Det gäller även vid återkallande av autogiro och när du kvittar leverantörsfakturor mot ett konto.

## Related Articles
* [Hantera verifikat i bokföringen]
* [Inställningar för bokföring]
* [Korrigera ett bokfört verifikat]
