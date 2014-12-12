# Mitmachen!
Ziel dieses Projekts ist es, mit überschaubarem Arbeitsaufwand für jeden einzelnen ein Skriptum der Algebra-Vorlesung im WS 14/15 zu erstellen.

## Aufgabenverteilung
 * Die Aufgabenverteilung wird online unter https://www.ethercalc.org/xvx50sf070 vorgenommen.
 * Man trägt sich dort mit Klarnamen oder Pseudonymen ein.
 * Die Seite wird "extern" gehostet, aus diesem Grund wird nicht empfohlen, persönliche Daten wie eine E-Mail-Adresse anzugeben. (Spam!)

## Beiträge
 * Einzureichen sind (mindestens) ein `tex`-File und ein kompiliertes `pdf`-File. :-)
 * Als Ausgangspunkt verwendet man die aktuelle Version des Skriptes und fügt an die passende Stelle seinen Code ein. Gegebenenfalls kann man die Input-Befehle entfernen und bekommt dann die korrekte Nummerierung der Abschnitte nach dem in die gesamte Version.
 * Es genügt, den eigenen Code einzureichen, solange dieser kompiliert. Das Zusammenfügen übernimmt der/die Editor/en.
 * Dies kann per Mail an Robert Seidel (kanonische Uni-Mailadresse) oder per Push Request an dieses Repository gesendet werden.

## GIT und diese Seite
 * Die aktuelle Version des Skriptes wird auf dieser Seite veröffentlicht.
 * Wer sich dafür interessiert, kann Beiträge gerne direkt in dieses Repository pushen.
 * Sehr gute Anleitungen zu GIT finden sich leicht online, zum Beispiel http://rogerdudler.github.io/git-guide/index.de.html oder https://www.atlassian.com/git/tutorials/.

# Coding conventions
Richtlinien für die Erzeugung des `LaTeX`-Codes.

## Mathematische Notation
 * Die Zeichen für Mengen sind im Header mittels `\newcommand` einzuführen.
 * Die Zeichen für Operatoren sind im Header mittels `\DeclareMathOperator` einzuführen.
 * Bei mehreren aufeinanderfolgenden Quantoren wie `\forall` und `\exists` verwendet man `~` als Platzhalter. Ebenso vor oder nach `\text`-Elementen im Mathematikmodus.

## Verweise und Index
 * Bei Verweisen auf das LA-Skript, verwendet man den Befehl `\LAref`.
 * Alle wichtigen Begriffe (also insbesondere Definitionen und Sätze mit Namen) sind mit `\index` zu indexieren.

## Beweise
 * Ein Beweis wird mit dem Befehl `\bew` begonnen und mit `\qed` beendet.
