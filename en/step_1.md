JavaScript provides a Date function using the syntax `new Date()`.

This function lets you work with dates automatically. JavaScript will use the browser's time zone and return the current date and time. For example:

`Mon Feb 19 2024 16:15:20 GMT+0000 (Greenwich Mean Time)`

+ Creating a Date Object: creates a new Date representing the current date and time:

--- code ---
---
language: js
filename: script.js
line_numbers: true
line_number_start: 1
line_highlights: 2
---
     
     // Update Copyright Year function 
     const currentYear = new Date();
    
--- /code ---

+ Setting a Specific Date - creates a Date object for the specified date (year, month, day).
    const specificDate = new Date("2022-01-09");

+ Getting Various Components - these functions retrieve specific components of the date and time:

    const year = currentDate.getFullYear();
    const month = currentDate.getMonth(); // 0-indexed (0 = January, 11 = December)
    const day = currentDate.getDate();
    const hours = currentDate.getHours();
    const minutes = currentDate.getMinutes();
    const seconds = currentDate.getSeconds();
    const milliseconds = currentDate.getMilliseconds();

+ Setting Date Components - these functions allow you to set specific components of the date:

    currentDate.setFullYear(2023);
    currentDate.setMonth(5); // 0-indexed (5 = June)
    currentDate.setDate(15);

