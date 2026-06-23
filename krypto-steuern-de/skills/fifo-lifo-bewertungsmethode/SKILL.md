---
name: fifo-lifo-bewertungsmethode
description: "Erlaeutert und wendet Bewertungsmethoden FIFO und LIFO fuer die Zuordnung veraeusserter Krypto-Einheiten zu Anschaffungstranchen an. Methodik Vergleich beider Methoden Konsistenzgebot. Output ausformulierter Vergleich mit empfohlener Methode und Berechnungstabelle."
---

> Dieser Skill ersetzt keine Steuerberatung nach Paragraf 3 StBerG und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Die Ausgabe ist
> eine Arbeitshilfe ohne Gewaehr. Im Einzelfall ist eine Steuerberaterin,
> ein Steuerberater oder eine Rechtsanwaeltin/ein Rechtsanwalt zu
> konsultieren.

# Bewertungsmethoden FIFO und LIFO bei Kryptowerten

## Zweck / Anwendungsfall

Wenn dieselbe Kryptowaehrung zu unterschiedlichen Zeitpunkten und Preisen
angeschafft wurde und nur ein Teil davon veraeussert wird, muss eine
Verbrauchsfolgefiktion (z. B. First In First Out oder Last In First Out)
angewendet werden, um zu bestimmen, welche Tranche als veraeussert gilt.

## Eingaben

- Vollstaendige Liste aller Anschaffungen (Datum, Menge, Kosten).
- Vollstaendige Liste aller Veraeusserungen (Datum, Menge, Erloes).
- Angabe, ob in der Vergangenheit bereits eine Methode angewendet wurde
  (Konsistenzgebot).

## Ablauf / Checkliste

1. Pruefen, welche Verbrauchsfolgefiktion nach aktueller
   Verwaltungsauffassung als sachgerecht gilt (in der Praxis regelmaessig
   First In First Out je Wallet/Verwahrstelle).
2. Anschaffungstranchen chronologisch auflisten.
3. Veraeusserungen den Tranchen nach der gewaehlten Methode zuordnen.
4. Gewinn/Verlust je zugeordneter Tranche berechnen.
5. Konsistenz mit fruehrer angewendeter Methode pruefen — ein Methoden-
   wechsel ohne sachlichen Grund ist kritisch zu hinterfragen.
6. Ergebnis als Tabelle plus ausformulierte Zusammenfassung darstellen.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`.

## Ausgabeformat

- Tabelle mit Tranchen-Zuordnung, ergaenzt durch ausformulierten Text.
- Rechtsstand-Datum angeben.
- Hinweis, dass die Wallet-bezogene Betrachtung (statt uebergreifend) nach
  aktueller Verwaltungsauffassung relevant sein kann.

## Beispiele

Beispiel (fiktiv): Anschaffung von 1 BTC am 1. Januar 2023 fuer 18.000 Euro
und weiteren 1 BTC am 1. Januar 2024 fuer 30.000 Euro in derselben Wallet.
Veraeusserung von 1 BTC am 1. Juni 2024 fuer 35.000 Euro. Bei FIFO wird die
Tranche vom 1. Januar 2023 zugeordnet: Gewinn von 17.000 Euro, Haltefrist
ueber ein Jahr.

## Normen und Rechtsprechung

- Paragraf 23 EStG (privates Veraeusserungsgeschaeft, Ermittlung des
  Gewinns).
- Aktuelles BMF-Schreiben zur ertragsteuerlichen Behandlung von virtuellen
  Waehrungen, insbesondere zur Verbrauchsfolgefiktion (Datum verifizieren).
