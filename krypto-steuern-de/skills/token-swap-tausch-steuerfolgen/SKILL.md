---
name: token-swap-tausch-steuerfolgen
description: "Pruefung der Steuerfolgen eines direkten Tauschs einer Kryptowaehrung gegen eine andere ohne Zwischenschritt in Euro. Methodik Tausch als Veraeusserung und Anschaffung Bewertung zum Marktwert. Output ausformulierte Pruefung mit Gewinnermittlung."
---

> Dieser Skill ersetzt keine Steuerberatung nach Paragraf 3 StBerG und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Die Ausgabe ist
> eine Arbeitshilfe ohne Gewaehr. Im Einzelfall ist eine Steuerberaterin,
> ein Steuerberater oder eine Rechtsanwaeltin/ein Rechtsanwalt zu
> konsultieren.

# Token-Swap: Steuerfolgen eines direkten Krypto-Krypto-Tauschs

## Zweck / Anwendungsfall

Pruefung der steuerlichen Folgen, wenn eine Kryptowaehrung direkt gegen
eine andere getauscht wird (z. B. ETH gegen einen anderen Token), ohne
zwischenzeitliche Umwandlung in Euro.

## Eingaben

- Getauschte Token (hingegeben und erhalten), jeweils Menge.
- Anschaffungsdatum und Anschaffungskosten des hingegebenen Tokens.
- Marktwert beider Token zum Tauschzeitpunkt in Euro.
- Datum des Tauschs.

## Ablauf / Checkliste

1. Feststellen, dass ein Tausch einkommensteuerlich als Veraeusserung des
   hingegebenen Tokens und gleichzeitige Anschaffung des erhaltenen Tokens
   behandelt wird.
2. Veraeusserungserloes des hingegebenen Tokens zum Marktwert im
   Tauschzeitpunkt ermitteln.
3. Gewinn/Verlust aus der "Veraeusserung" des hingegebenen Tokens nach
   Paragraf 23 EStG pruefen (Haltefrist, Freigrenze wie bei
   Krypto-Euro-Verkaeufen).
4. Anschaffungskosten des neu erhaltenen Tokens auf den Marktwert im
   Tauschzeitpunkt festsetzen; neue Haltefrist beginnt mit diesem Datum.
5. Ergebnis ausformulieren.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`.

## Ausgabeformat

- Ausformulierte Pruefung mit getrennter Darstellung von "Veraeusserung"
  des hingegebenen und "Anschaffung" des erhaltenen Tokens.
- Rechtsstand-Datum angeben.

## Beispiele

Beispiel (fiktiv): Tausch von 1.000 Euro Anschaffungswert in BTC gegen ETH
mit einem Marktwert von 1.300 Euro zum Tauschzeitpunkt, Haltefrist des BTC
unter einem Jahr. Es ergibt sich ein zu pruefender Gewinn von 300 Euro aus
der "Veraeusserung" des BTC, sofern die Freigrenze ueberschritten wird;
gleichzeitig beginnt fuer den erhaltenen ETH eine neue Haltefrist mit
Anschaffungskosten von 1.300 Euro.

## Normen und Rechtsprechung

- Paragraf 23 EStG (privates Veraeusserungsgeschaeft, Tausch als
  Veraeusserungsvorgang).
- Aktuelles BMF-Schreiben zur ertragsteuerlichen Behandlung von virtuellen
  Waehrungen, insbesondere zu Tauschvorgaengen (Datum verifizieren).
