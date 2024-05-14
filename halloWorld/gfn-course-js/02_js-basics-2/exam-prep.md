# JavaScript Grundlagen Teil 2

- Higher Order Funktionen von Arrays
- Scoping
- Rekursion
- Schleifen (deklarativen Stil mit Higher Order Functions und imperativen Stil mit Schleifen)
- Funktionen mit Defaultparameter (`const function = (name = 'Max') => {}`)
- Restparameter
- Mehrdimensionales Array (`const array = [ [], [ [] ], [] ]`)
- Objekte (Einführung => Object.keys(), Object.values(), Object.entries())
- JSON (.json) (JavaScript Object Notation) => Dateiformat wie .txt oder .doc

## Sollte man sich unbedingt anschauen

Alle Fragen aus den Büchern unbedingt anschauen, dann folgende Hinweise:

```js
// Higher Order Funktionen für Arrays
.map()
.reduce()
.every()
.some()
.filter()
.forEach()

// Stolperfallen, die in der Prüfung vorkommen können
[10, 20, 30].map(() => 8); // => [8, 8, 8]
[10, 20, 30].map((x) => x); // => [10, 20, 30]
[10, 20, 30].map(x => x); // => [10, 20, 30]

// Higher Order Funktionen für Strings
.split() // => Text zu Array
.join()

// Beispiel für split und join()
const text = 'Hallo';
const textArray = text.split(''); // => ['H', 'a', 'l', 'l', 'o']
console.log(textArray.join('-')); // => 'H-a-l-l-o'
```

- 'use strict' Auswirkungen auf Variablen und Funktionen
- Definition von Rekursion: Funktionen können sich selbst aufrufen

```js
const multiply = (x) => multiply(x) + 100;
console.log(multiply(10)); // => Programm bricht ab, weil es immer wieder ausgeführt wird ohne ein Ende, wir kriegen KEIN infinity
```

- for loop anschauen (loops sind nicht prüfungsrelevant wie for in, for of und while loops sind optional)

- Object.keys(), Object.values(), Object.entries()
