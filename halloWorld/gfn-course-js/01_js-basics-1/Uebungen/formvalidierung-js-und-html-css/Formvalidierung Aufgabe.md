# Formularvalidierung

In dieser Aufgabe geht es um die Validierung von Nutzerdaten bei einer Registrierung. Deine Aufgabe ist es zu prüfen, ob die Nutzerdaten den vorgegebenen Kriterien entsprechen. Konkret müssen ein Nutzername, ein Passwort und die E-Mail-Adresse eines Nutzers überprüft werden. Verwende als Grundlage deiner Aufgabe den folgenden Codeausschnitt.

```js
// Beispiel Form Daten
const USERNAME = 'CodingMaster42';
const EMAIL = 'coding@master.com';
const PASSWORD = 'TopSecret123!';
const PASSWORD_CONFIRMATION = 'TopSecret123!s';

// Beispiel Daten für User, die schon registriert sind
const users = [
  'Webmaster1', // username
  '123JS456', // password
  'mastercoder@js.com', // email
];

const validateForm = (username, password, email, emailConfirmation) => {};

console.log(validateForm(USERNAME, PASSWORD, EMAIL, EMAIL_CONFIRMATION));
```

## Technologien / Anforderungen

Benutze JavaScript - ECMAScript 2015 (ES6) oder höher. Du musst keine grafische Benutzeroberfläche (GUI) entwickeln.

Wenn du möchtest, kannst du aber versuchen, die Aufgabe mit den verfügbaren HTML- und CSS-Vorlagen mit Bootstrap zu lösen oder dein eigenes Design mit HTML und CSS zu entwickeln.

Wenn du die Aufgabe ohne HTML und CSS lösen möchtest, gib die Ausgabe der Funktion `validateForm` in die Konsole aus. Wenn du HTML und CSS verwendest, gib das Resultat als eigenes HTML-Element aus.

Nutze alle Hilfsmittel, die dir auch in deinen eigenen Projekten zur Verfügung stehen, also Internet, Artikel, Tutorials und auch KI. Versuche Probleme selbst zu lösen, bevor du Hilfe suchst.

## Anforderungen

### Username / Nutzername

Für den Nutzernamen gibt es folgende Vorgaben:

Der Nutzername...

- darf weder mit einem Leerzeichen beginnen, noch enden.
- muss mindestens vier Zeichen enthalten.
- darf Zahlen enthalten aber muss mit einem Buchstaben beginnen. darf nicht von einem anderen Nutzer verwendet werden.

### Passwort

Für das Passwort gibt es folgende Vorgaben:

Das Passwort...

- darf weder mit einem Leerzeichen beginnen, noch enden muss mindestens zehn Zeichen enthalten
- muss mindestens einen Großbuchstaben enthalten
- muss mindestens einen Kleinbuchstaben enthalten
- muss mindestens eines der folgenden Sonderzeichen enthalten: ! , ? , $
- muss mit der Passwortbestätigung übereinstimmen

### E-Mail-Adresse

Für die E-Mail-Adresse gibt es folgende Vorgaben:

Die E-Mail-Adresse...

- darf weder mit einem Leerzeichen beginnen noch enden
- darf Zahlen enthalten, aber muss mit einem Buchstaben beginnen
- muss die Form einer E-Mail-Adresse einhalten. Dazu muss sowohl ein @ als auch ein . enthalten sein

## Implementierung

Nutze die gegebenen Konstanten als Werte des zu überprüfenden Formulars. Greife dabei in deinen Funktionen nicht direkt auf die Konstanten zu, sondern übergib diese als Parameter.

Weiterhin ist ein Array `users` gegeben. Dieses enthält beispielhafte Daten für einen Nutzer. Verwende diesen Nutzer stellvertretend für alle Nutzer, um zu prüfen, ob ein Nutzername bereits vergeben ist.

Teile deinen Programmcode in mehrere Funktionen auf. Die Funktion `validateForm()` stellt dabei den Einstiegspunkt in die Validierung dar.

Sie soll als Ergebnis einen String zurückgeben. Dieser enthält entweder eine Aufzählung aller Fehler der Formulardaten oder eine Meldung, dass alle Daten den Vorgaben entsprechen.

# Tipps

- Erstelle für jede Validierung (Nutzername, Passwort, E-Mail) eine eigene Funktion.
- Lagere identischen Code in eigene Funktionen aus.
- Nutze das Internet als Hilfe, wenn du nicht weiterkommst.
