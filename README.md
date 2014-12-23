# Mitmachen!
Ziel dieses Projekts ist es, mit überschaubarem Arbeitsaufwand für jeden einzelnen ein Skriptum der Algebra-Vorlesung im WS 14/15 zu erstellen.

## Aufgabenverteilung
 * Die Aufgabenverteilung wird online unter https://www.ethercalc.org/xvx50sf070 vorgenommen.
 * Man trägt sich dort mit Klarnamen oder Pseudonymen ein.
 * Die Seite wird "extern" gehostet, aus diesem Grund wird nicht empfohlen, persönliche Daten wie eine E-Mail-Adresse anzugeben. (Spam!)

## Beiträge
 * Einzureichen sind (mindestens) ein `tex`-File und ein kompiliertes `pdf`-File. :-)
 * Als Ausgangspunkt verwendet man das Template aus `template.tex` und fügt dort seinen Code ein. Falls nötig, kann natürlich auch die Präambel verändert werden. Die Nummerierung der Abschnitte wird im Template noch nicht korrekt sein, das macht aber nichts.
 * Die eingereite Datei sollte kompilieren. Das Zusammenfügen der einzelnen Vorlesungen übernimmt der/die Editor/en.
 * Die fertige Vorlesung kann per Mail an Robert Seidel (kanonische Uni-Mailadresse) oder per Push Request an dieses Repository gesendet werden.
 * TeXen ist wichtig - das Skript gegenzulesen aber auch. Dies sollte erst gemacht werden, wenn die Vorlesung ins Skript eingefügt wurde. Eventuelle Fehler können dann direkt an Robert Seidel (kanonische Uni-Mailadresse) oder per Push Request mitgeteilt werden.

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

## thm-Umgebung
 * Um den Quellcode möglichst einfach zu halten, wird auf den Einsatz der `proof`- und `thm`-Umgebungen verzichtet und die Nummern im Skript durch `\subsection` gegliedert.
 * Für größere Projekte mag dies nicht sinnvoll erscheinen - hier gilt aber: KISS (Keep it simple, stupid) ...
