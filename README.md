# JS-Fallabfrage-Segment-3

## Szenario
Wir sollen unsere Nutzer auf eine Webseite einer luxuriösen Bar in New York weiterleiten.

Allerdings müssen wir in einem ersten Schritt das Alter der Nutzer abfragen.

Der Nutzer wird auf die Seite nur weitergeleitet, wenn sein Alter mindestens **21 Jahre** beträgt.

## HTML
Deine Seite besteht aus einem einzigen Formular zur Alterabfrage.

Das Formular hat ein Eingabefeld für:

* Alter (number, eingabepflichtig, Minumum 1)

und einen Button zum Absenden.

## Style
Platziere das Formular in die Mitte der Seite.

Gib dem body eine Hintergrundfarbe.

## JavaScript
Prüfe das Alter nun mit JavaScript.

Schreibe dazu eine Funktion `run` und verlinke sie im `action` Tag im Formular.

In der Funktion greifst du nun auf die Alterseingabe mittels `querySelector` zu.

Als letztes brauchst du eine `if-else` Fallabfrage.

Falls die Eingabe **größer** oder **gleich** `21` ist,

leitest du den Nutzer mit der folgenden JavaScript Anweisung weiter:

`location.replace("https://www.goldbarnewyork.com/");`

Im `else` Fall gibst du ein `alert` mit der Meldung "You have to be at least 21 years old." aus.
