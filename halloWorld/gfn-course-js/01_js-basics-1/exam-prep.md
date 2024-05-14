# JavaScript Grundlagen Teil 1

- Konsolenausgaben mit console.log()
- Dialogfenster in JS prompt(), alert(), confirm()
- Kommentare in JS
- Rechnen in JS
- Datentyp String, Number, Boolean
- literal
- typeof
- Variablen und Konstanten in JS
- Prioritätsreihenfolge
- Zusammengesetzte Zuweisungsoperatoren
- Increment & Decrement
- Implizite und explizite Typkonvertierung
- Strings verketten mit +
- NaN
- Math Object (Math.random(), Math.floor(), Math.ceil())
- Number.toFixed()
- Relationale Operatoren (< >)
- Vergleichoperatoren (=== ==)
- Lexikographische Vergleiche; z.B. 'abc' < 'ABC' => true oder false raus?
- if Statements
- Ternärer Operator
- logische Operatoren UND und ODER
- unärer Operator (!)
- String Methoden
- Regex
- Funktionsdefinitionen in JS (function, () => {})
- Funktionen mit Übergabeparameter (Arguments)
- Funktionen mit Rückgabewerten (return)
- Guards (if Statement in der Funktion)
- Array + Array Methoden + Higher Order Functions (sort, split, join, map, forEach, reduce, some, every)

## Sollte man sich unbedingt anschauen

Alle Fragen aus den Büchern unbedingt anschauen, dann folgende Hinweise:

- JavaScript und Java sind unterschiedlich
- JavaScript hieß früher LiveScript

Kommentare in JavaScript

```js
// Kommentar
/* Kommentar */ // // //
/* // Kommentar */
*/ Kommentar /*
```

- ASI (Automatic Semicolon Insertion, auf Deutsch automatische Semikolon-Ergänzung)
- Werte von Variablen halbieren ("/= 2" ODER "\*= 0.5" etc.)
- Umlaute oder andere Schriftzeichen sind in der Variablendefinition erlaubt, sollten aber vermieden
- Backticks, z.B. console.log(`wird als JavaScript Code ausgeführt, wenn wir $ verwenden ${100 / 10}`)
- Zeilenumbrüche in einem String (\n)
- Math.sqrt(), Math.floor(), Math.round(), Math.ceil()
- Math.pow(2, 10) => 2^10 || Alternative: 2\*\*10
- toFixed(2)
- If Else Statements zu Ternären Operatoren umwandeln können

Operatoren in JavaScript

```js
// Gültige Zuweisungsoperatoren in JavaScript
+=
/=
*=
%=
>=
<=

// Gültige Operatoren in JavaScript
&&
||
!
```

Folgende String Methoden

```js
// String Methoden

.includes()
.substr() // kein .substring() kennen für Prüfung
.trim()
.indexOf() // erster Suchtreffer
.lastIndexOf() // letzter Suchtreffer
.toLowerCase()
.toUpperCase()
.charAt().repeat()
.length // Attribut/Eigenschaft
```

- Regex (nur die aus dem Buch)
- Signatur von einer Funktion sollte folgende Sachen IMMER haben: Name der Funktion, Namen der Parameter und optionale Parameter

Funktionen

```js
// prettier-ignore
let funktion = x => x

// prettier-ignore
let funktion2 = (x) => x

// prettier-ignore
let funktion3 = x => { return x }
```

- Indexoperator bei Arrays
- Die anderen Array Methoden sind bei JavaScript Grundlagen Teil 2 zu finden
