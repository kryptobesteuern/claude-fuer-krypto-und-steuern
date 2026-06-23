---
name: haltefrist-anschaffung-veraeusserung
description: "Ermittelt Anschaffungszeitpunkt und Haltefrist bei mehreren Krypto-Kaeufen und Teilverkaeufen. Methodik Zuordnung einzelner Tranchen Pruefung Fristverlaengerung durch Ertraege. Output Haltefristtabelle mit ausformulierter Einordnung je Tranche."
---

> Dieser Skill ersetzt keine Steuerberatung nach Paragraf 3 StBerG und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Die Ausgabe ist
> eine Arbeitshilfe ohne Gewaehr. Im Einzelfall ist eine Steuerberaterin,
> ein Steuerberater oder eine Rechtsanwaeltin/ein Rechtsanwalt zu
> konsultieren.

# Haltefrist-Ermittlung bei mehreren Anschaffungs- und Veraeusserungsvorgaengen

## Zweck / Anwendungsfall

Bei mehreren Kaeufen derselben Kryptowaehrung zu unterschiedlichen
Zeitpunkten und nur teilweiser Veraeusserung muss zugeordnet werden, welche
Tranche veraeussert wurde, um die Haltefrist nach Paragraf 23 EStG korrekt
zu bestimmen.

## Eingaben

- Liste aller Anschaffungsvorgaenge mit Datum, Menge, Kosten.
- Liste aller Veraeusserungsvorgaenge mit Datum, Menge, Erloes.
- Angabe, ob eine Zuordnungsmethode (z. B. FIFO) bereits konsistent
  angewendet wurde.
- Angaben zu zwischenzeitlicher Nutzung fuer Staking/Lending je Tranche.

## Ablauf / Checkliste

1. Alle Anschaffungs- und Veraeusserungsvorgaenge chronologisch ordnen.
2. Zuordnungsmethode festlegen (siehe Skill
   `fifo-lifo-bewertungsmethode`) und konsistent fuer den gesamten
   Veranlagungszeitraum anwenden.
3. Jede Veraeusserung einer konkreten Anschaffungstranche zuordnen.
4. Haltefrist je Tranche berechnen (Anschaffungsdatum bis
   Veraeusserungsdatum).
5. Pruefen, ob fuer einzelne Tranchen eine Fristverlaengerung durch
   Einkuenfteerzielung in Betracht kommt.
6. Tabelle mit Tranche, Haltefrist, Ergebnis (steuerpflichtig/nicht
   steuerpflichtig) erstellen.
7. Gesamtergebnis ausformulieren.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`.

## Ausgabeformat

- Tabelle je Tranche zulaessig, ergaenzt durch ausformulierten
  Pruefungstext.
- Rechtsstand-Datum angeben.
- Gesamtergebnis am Ende klar benennen.

## Beispiele

Beispiel (fiktiv): Anschaffung von 1 ETH am 1. Maerz 2023 und weiteren
1 ETH am 1. Juni 2024. Veraeusserung von 1 ETH am 1. Mai 2024. Bei FIFO
wird die Tranche vom 1. Maerz 2023 als veraeussert behandelt; Haltefrist
ueber ein Jahr, damit grundsaetzlich nicht steuerbar nach Paragraf 23 EStG
(vorbehaltlich Fristverlaengerung).

## Normen und Rechtsprechung

- Paragraf 23 Abs. 1 Satz 1 Nr. 2 EStG.
- Aktuelles BMF-Schreiben zur ertragsteuerlichen Behandlung von virtuellen
  Waehrungen (Verbrauchsfolgefiktion, Datum verifizieren).
