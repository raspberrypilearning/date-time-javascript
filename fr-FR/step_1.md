JavaScript dispose d'une fonction `Date()` qui renvoie la date et l'heure actuelles, en utilisant le fuseau horaire du navigateur.

Par exemple :

`Lundi 19 février 2024 16:15:20 GMT+0000 (Greenwich Mean Time)`

Un appel à `Date()` renvoie une chaîne de caractères.

Voici le résultat de l'appel à `Date()` lorsque cette page a été chargée :

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/comic-character-date" width="100%" height="100" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

### Créer un objet Date

This example creates a new Date object, representing the current date and time. Il est contenu dans la constante `currentDate`.

## --- code ---

language: js
filename:
line_numbers: false
--------------------------------------------------------

```
// Mise à jour de la fonction Copyright Year
 const currentDate = new Date();
```

\--- /code ---

### Récupérer des composants de la date

Ces fonctions récupèrent des composants spécifiques de la date et de l'heure :

## --- code ---

language: js
filename:
line_numbers:
line_number_start:
line_highlights:
-----------------------------------------------------

```
const year = currentDate.getFullYear();
const month = currentDate.getMonth(); // 0-indexed (0 = Janvier, 11 = Décembre)
const day = currentDate.getDate();
const hours = currentDate.getHours();
const minutes = currentDate.getMinutes();
const seconds = currentDate.getSeconds();
const milliseconds = currentDate.getMilliseconds();
```

\--- /code ---
