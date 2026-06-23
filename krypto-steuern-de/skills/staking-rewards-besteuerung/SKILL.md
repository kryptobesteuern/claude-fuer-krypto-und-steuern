---
name: staking-rewards-besteuerung
description: "Pruefung der ertragsteuerlichen Behandlung von Staking-Rewards im Privatvermoegen. Methodik Zuflusszeitpunkt Bewertung in Euro Einkunftsart Abgrenzung gewerblich. Output ausformulierte Einordnung je Reward-Zufluss mit Wertansatz."
---

> Dieser Skill ersetzt keine Steuerberatung nach Paragraf 3 StBerG und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Die Ausgabe ist
> eine Arbeitshilfe ohne Gewaehr. Im Einzelfall ist eine Steuerberaterin,
> ein Steuerberater oder eine Rechtsanwaeltin/ein Rechtsanwalt zu
> konsultieren.

# Besteuerung von Staking-Rewards

## Zweck / Anwendungsfall

Pruefung, wie Staking-Rewards (Belohnungen fuer das Bereitstellen von
Kryptowerten zur Validierung in Proof-of-Stake-Netzwerken) im
Privatvermoegen steuerlich zu behandeln sind.

## Eingaben

- Zeitpunkt jedes einzelnen Reward-Zuflusses.
- Menge und Art des erhaltenen Tokens je Zufluss.
- Marktwert des Tokens in Euro zum jeweiligen Zuflusszeitpunkt.
- Umfang der Staking-Taetigkeit (Eigenbetrieb eines Validators,
  Delegation, Nutzung eines Staking-Dienstleisters).
- Angabe zu Umfang und Regelmaessigkeit (fuer Abgrenzung privat/gewerblich).

## Ablauf / Checkliste

1. Zuflusszeitpunkt jedes Rewards feststellen (massgeblich fuer Bewertung
   und spaetere Haltefristberechnung bei Weiterverausserung).
2. Marktwert in Euro zum Zuflusszeitpunkt ermitteln.
3. Einkunftsart pruefen: in der Regel sonstige Einkuenfte nach Paragraf 22
   Nr. 3 EStG, soweit keine gewerbliche Taetigkeit vorliegt.
4. Abgrenzung zur gewerblichen Taetigkeit pruefen (siehe Skill
   `mining-gewerblich-oder-privat` fuer das Abgrenzungsschema, analog auf
   Staking anwendbar bei nachhaltigem, planmaessigem Betrieb).
5. Pruefen, ob die Freigrenze fuer sonstige Leistungen nach Paragraf 22
   Nr. 3 Satz 2 EStG erreicht ist.
6. Spaetere Veraeusserung der erhaltenen Reward-Token gesondert nach
   Paragraf 23 EStG pruefen (neue Haltefrist ab Zuflusszeitpunkt).
7. Ergebnis ausformulieren.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`.

## Ausgabeformat

- Ausformulierte Pruefung je Zuflussart, Tabelle fuer Reward-Uebersicht
  zulaessig.
- Rechtsstand-Datum angeben.
- Hinweis auf Bewertungsunsicherheiten bei volatilen Kursen.

## Beispiele

Beispiel (fiktiv): Privatperson delegiert ETH an einen Validator und
erhaelt monatlich kleine Reward-Betraege. Bewertung jedes Rewards zum
Marktwert im Zuflusszeitpunkt, Einordnung als sonstige Einkuenfte nach
Paragraf 22 Nr. 3 EStG, sofern keine gewerbliche Struktur vorliegt.

## Normen und Rechtsprechung

- Paragraf 22 Nr. 3 EStG (sonstige Einkuenfte).
- Paragraf 23 EStG (bei Weiterverausserung der Reward-Token).
- Aktuelles BMF-Schreiben zur ertragsteuerlichen Behandlung von Staking
  (Datum verifizieren).
