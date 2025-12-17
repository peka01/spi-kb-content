---
id: DAWh5QiBatBfx9M3OUWL
title: Balansavstämning
slug: general-balansavstamning
languages:
  - sv
  - en
format: md
status: draft
folderId: null
createdAt: '2025-12-17T06:56:11.985Z'
updatedAt: '2025-12-17T13:14:08.438Z'
publishedAt: null
pendingReview: true
reviewedAt: null
lastLLMUpdateAt: '2025-12-17T13:14:08.438Z'
currentVersion: 5
metadata:
  area2: ''
  solution: Skatt & Bokslut
  productId: Skatt & Bokslut
  area1: general
  targetAudience: []
  tags:
    - update
    - general
---
Här är den uppdaterade artikeln.

***

# Balansavstämning

## Översikt
Balansavstämningen ger dig en tydlig överblick över alla balanskonton som har bokförda transaktioner fram till den period du arbetar med. Här kan du effektivt stämma av konton, hantera bilagor och säkerställa att allt stämmer.

Du hittar översikten för balansavstämning under både **Periodavslut** och **Årsavslut**.

## Funktioner i översikten

### Sök och filtrera
För att snabbt hitta det du letar efter kan du använda sökfältet högst upp i vyn för att söka på både kontonummer och kontonamn. Du kan också använda filtermenyn för att begränsa listan, till exempel för att bara visa konton som inte är klarmarkerade eller konton med en avstämningsdifferens.

### Exportera till Excel
Du kan enkelt exportera hela översikten till en Excel-fil. Klicka på knappen **Exportera till Excel** uppe till höger i vyn för att ladda ner filen.

### Anpassa kolumner och vy
Vilka kolumner som visas i översikten anpassas automatiskt efter storleken på din skärm, där mindre skärmar visar de viktigaste kolumnerna.

*   **Välj kolumner:** Klicka på knappen **Dölj/Lägg till kolumn** för att själv välja vilka kolumner du vill se. Inställningen sparas för företaget och gäller för alla perioder. För att gå tillbaka till standardvyn, välj **Återställ till förvalda kolumner**.
*   **Välj innehåll:** Via inställningsknappen kan du göra ytterligare anpassningar. Här kan du välja om konton med nollsaldo ska visas och om kontogrupper utan underliggande konton ska inkluderas i listan.

### Fördjupad detaljnivå med drill down
För att titta närmare på verifikationerna som är bokförda på ett konto kan du använda drill down-funktionen. Belopp som du kan granska närmare är understrukna och blir blå när du för pekaren över dem.

Klicka på ett sådant belopp för att öppna dialogrutan **Kontoanalys**, där alla verifikationer för kontot visas. Fönstret öppnas separat, vilket gör att du kan ha flera kontoanalyser öppna samtidigt – perfekt om du arbetar med flera skärmar. Tänk på att om du stänger webbläsarfliken stängs även alla fönster som öppnats från den.

I fönstret **Kontoanalys** kan du:
*   Se ingående och utgående saldo för perioden.
*   Se verifikationsdatum, verifikationsnummer, periodens förändring, kontosaldo efter varje verifikation och transaktionstext.
*   Välja ett annat konto eller en annan period via menyerna högst upp.
*   Klicka på pilen bredvid en verifikation för att se alla detaljer, som motkonton och bokförda belopp.
*   Se eventuella resultatenheter, kostnadsbärare eller projekt som är kopplade till verifikationerna (upp till fyra dimensioner visas).

### Visa bifogade filer i kontoanalysen
Om en verifikation har en bifogad fil ser du en gem-symbol i kolumnen **Bifogade filer**. Klicka på gemet för att se och välja vilket dokument du vill förhandsgranska.

I förhandsgranskningen kan du ladda ner dokumentet via knappen **Ladda ner**. Du kan också skapa en ny extern bilaga som dokumentet automatiskt kopplas till genom att välja **Lägg till bilaga**.

## Bilagor i balansavstämning
Under **Balansavstämning - Bilagor** arbetar du med bilagor som underlättar beräkningar och avstämningar för dina konton. Du hittar funktionen under både **Periodavslut** och **Årsavslut**.

Du kan arbeta med huvudbilagor, underbilagor, externa bilagor och automatiskt genererade bilagor. I översiktsfönstret till vänster kan du via listan **Visa** välja om du vill se en lista över **Konton** med kopplade bilagor eller en lista över alla **Bilagor**.

Du kan enkelt ändra ordningen på bilagor i öppna perioder genom att dra och släppa dem. Ordningen följer sedan med när du skapar nya perioder.

## Fältförklaringar

*   **Avstämningsbelopp:** Fyll i avstämningsbeloppet direkt i översikten eller på en bilaga. Om du har en koppling till Bokföring & Fakturering fylls vissa belopp i automatiskt när du importerar bokföringsdata.
*   **Avstämningsdifferens:** Om det finns en skillnad mellan utgående balans och avstämningsbeloppet visas den här. Du kan klicka på den blå symbolen i kolumnen för att skapa en bokslutsverifikation för differensen.
*   **Bilagor:** En blå gem-ikon visar att det finns en bilaga kopplad till kontot eller kontogruppen. Klicka på den för att se en lista över bilagorna. En grå ikon betyder att inga bilagor finns. Klicka på den för att lägga till en ny bilaga.
*   **Automatiska kontroller:** Denna kolumn visar resultatet från automatiska kontroller.
    *   **Röd symbol:** Kontrollen har hittat en avvikelse. Klicka för mer information.
    *   **Orange symbol:** Kontrollen kunde inte köras, till exempel om data från tidigare perioder saknas.
    *   **Grön symbol:** Kontrollen har körts utan att hitta några avvikelser.
    Du kan klarmarkera en avvikelse med knappen **Klarmarkera kontroll**. Klarmarkeringen försvinner om en förändring sker som påverkar kontrollresultatet.
*   **Status checklista:** Visar status för kontrollfrågorna på kontot. Symbolen är också en genväg till fliken **Checklista**.
    *   **Grå symbol:** Inga frågor klarmarkerade.
    *   **Blå symbol:** Några frågor klarmarkerade.
    *   **Grön symbol:** Alla frågor klarmarkerade.
*   **Klart:** Markera här när du är klar med avstämningen för ett konto, en kontogrupp eller samtliga konton.
*   **Kvalitetssäkring:** Här kan en ansvarig granskare dokumentera kvalitetssäkringen av arbetet. Klicka på ikonen för att ändra status till **Godkänd** (grön) eller **Ej godkänd** (orange). Du kan även lämna en kommentar vid underkänt och återställa statusen vid behov.

## Relaterade artiklar
*   [Kom igång med Skatt & Bokslut]
*   [Att arbeta med bokslut]
*   [Bokslutsverifikationer]
*   [Automatiska kontroller]

## New Screenshots

![Screenshot (png)](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABgEAAAMzCAIAAAAAmCWmAAAQAElEQVR4AeydB0BTxx/HL2GE7cRRxQW4cIMLR8XWvzhacFRR66h7b3FhtZWqde9d98BRwVYFR8EJDsCJC1AUBwKiRhmRkPy/Lw9CgBCGTPnFy+Pe3e9+97vPjffu95IoFIvF0dHR79+/l9OLCBCBr5HA3X/lFLJP4GscAtQmIkAEiAARIAJEgAgQASLAEaB3ySTw7t27yMhIOH/i4uKEnz9/LqV4MXoRASJABIgAESACRIAIEAEiQASIwFdKgJpFBIhAySRQunTpMmXKwPmTlJQkxEtbW7tkgqBWEwEiQASIABEgAkSACBCBEkKAmkkEiAARIAIllgDcPnD+wA0khDeoxFKghhMBIkAEiAARIAJEoIQQoGYSASJABIgAESACJZkAnD8ymUxYkhFQ24kAESACRIAIlBAC1EwiQASIABEgAkSACBCBEk5AV1eXfEAlfAxQ84kAESgRBKiRRIAIEAEiQASIABEgAkSACJRwAjo6OuQDKuFjgJpfIghQI4kAESACRIAIEAEiQASIABEgAkSghBOgzwGViAFAjSQCRIAIEAEiQASIABEgAkSACBABIkAEvn4CGluopaVFnwPSSIgyiQARIAJEgAgQASJABIgAESACRIAIFAsCZCQRyIoA+YCyIkT5RIAIEAEiQASIABEgAkSACBCBok+ALCQCRIAIZEWAfEBZEaJ8IkAEiAARIAJEgAgQASJQ9AmQhUSACBABIkAEsiJAPqCsCFE+ESACRIAIEAEiQASKPgGykAgQASJABIgAESACWREgH1BWhCifCBABIkAEiEDRJ0AWEgEiQASIABEgAkSACBCBrAiQDygrQpRPBIgAESj6BMhCIkAEiAARIAJEgAgQASJABIhAVgTIB5QVIconAkWfAFlIBIgAESACRIAIEAEiQASIABEgAkQgKwLFwAf06NGjwYMHd1C8ZsyY8enTp6walSbfy8vLwcEBpTt16rR27do0eV/HCbWCCBABIkAEiAARIAJEgAgQASJABIgAEfj6CXxpC/PMBxQREXHz5s3z589fu3YtPj7+S+1KKX/jxo26devu2bPnguK1fPnyli1bZl//X3/91aVLl3/++Qelz507N2nSpIEDB6bopr9EgAgQASJABIgAESACRIAIEAEiQASKCwGykwh8KYEv9QFdunRp8ODBxsbGlStXbtasmZ2dXatWrQwMDOrXrz9t2rTIyMgvNHDz5s3pNNy/f9/T0zNdYmanK1asSJe1b9++169fp0ukUyJABIgAESACRIAIEAEiQASIQNEmQNYRASJABL6UQO59QHFxcaNGjWrfvv2ePXsyfj/rwYMHK1euvH79+hca+PHjx4waxGJxxkS1KWqLq01UW5wSiQARIAJEgAgQASJABIhA0SBAVhABIkAEiAAR+FICufQBxcTEtGnTZuvWrV9af1ble/bsmU7E0NDQ3t4+XWJmpz169EiX1bhx49q1a6dLpFMiQASIABEgAkSACBRtAmQdESACRIAIEAEiQAS+lEAufUB9+/a9devWl1aejfJOTk67d+82MzPjZVu0aOHr61upUiX+NMvj2rVrZ86caWJiwkvCJXTmzBk+TkciQASIABEgAsWHAFlKBIgAESACRIAIFAkCCQkJAQGBO3fu3Lt3782bNyUSSZEwK8WI8+fPr1K8EElJK3J/Q0NDT53y3K54IYLTImUi0CkQrkKkSBmWJ8bkxgcUEhJy7ty57FQvl8uzI6ZZZtCgQc+fP4cqhGvXrjVq1EizfLrcJUuWfPjwAWURjh07VqFChXQCdEoEiAARKPIEyEAiQASIABEgAkSACJQIAmFhYbVqmdvb2z9+/LioNRg7ym3btjVs2KhHjx7z5y+YO9fFwcGxadOmBw4cLAqmYp/+0099Bg0avGrVagREnJycnj59WhRs42349Cl28eIlzZpZ29l1HD169O+/L0RABKc2Ns2XLl0WFxfHSxbWsegz/HIyufEBHT58OGPFs2fP9lG8PD09//jjD95TIxAIeMn//vvv/fv3fBzHf//9F0c+YBYNHjy4S5cuI0aMgDOVT1Q9qgrDm3P27Fnk3rp1a0HaFz9c3r175+rq2rNnzx9++AFi4eHhV69eRYQPYWFhqqd84j///NOvX78OihfM+O2337y9vRMSEvhcOhKBIkCATCACRIAIEAEiQASIABEgAiWCwJo1a0uXLh0R8WbSpElFqsFSqXTIkCELF7paWzfz8PB4/vwZAiL161vNmjVrzJixMpmsEA0OCgrq2rXb69evt27deuvWTYTNmzc/e/YciaGhTwrRMGXV58+fb9u27aZNm2rUqDF37tzjxz3u3buLAIZwJlSpUmX9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)
