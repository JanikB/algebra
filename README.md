# Coding conventions

## Mathematische Notation
 * Die Zeichen für Mengen sind im Header mittels `\newcommand` einzuführen.
 * Die Zeichen für Operatoren sind im Header mittels `\DeclareMathOperator` einzuführen.
 * Bei mehreren aufeinanderfolgenden Quantoren wie `\forall` und `\exists` verwendet man `~` als Platzhalter. Ebenso vor oder nach `\text`-Elementen im Mathematikmodus.

## Verweise und Index
 * Bei Verweisen auf das LA-Skript, verwendet man den Befehl `\LAref`.
 * Alle wichtigen Begriffe (also insbesondere Definitionen und Sätze mit Namen) sind mit `\index` zu indexieren.

## Beweise
 * Ein Beweis wird mit dem Befehl `\bew` begonnen und mit `\qed` beendet.
