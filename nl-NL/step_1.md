JavaScript heeft een 'Date()' functie die de huidige datum en tijd weergeeft, met behulp van de tijdzone van de browser.

Bijvoorbeeld:

`maandag 19 feb 2024 16:15:20 GMT+0000 (Greenwich Mean Time)`

Een aanroep van `Date()` retourneert een string.

Dit is het resultaat van de aanroep van `Date()` toen deze pagina werd geladen:

<iframe src="https://editor.raspberrypi.org/nl-NL/embed/viewer/comic-character-date" width="100%" height="100" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

### Een datum-object maken

Dit voorbeeld maakt een nieuw datumobject aan dat de huidige datum en tijd weergeeft. Dit wordt opgeslagen in de constante `currentDate`.

--- code ---
---
language: js
filename: 
line_numbers: false
---

    // Update Copyright Jaar functie 
    const currentDate = new Date();

--- /code ---

### Datumcomponenten ophalen

Deze functies halen specifieke onderdelen van de datum en tijd op:

--- code ---
---
language: js
filename: 
line_numbers: 
line_number_start: 
line_highlights: 
---

    const year = currentDate.getFullYear();
    const month = currentDate.getMonth(); // 0-indexed (0 = Januari, 11 = December)
    const day = currentDate.getDate();
    const hours = currentDate.getHours();
    const minutes = currentDate.getMinutes();
    const seconds = currentDate.getSeconds();
    const milliseconds = currentDate.getMilliseconds();

--- /code ---