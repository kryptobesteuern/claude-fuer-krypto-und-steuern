---
name: defi-lending-impermanent-loss-steuer
description: "Steuerliche Einordnung von DeFi-Lending-Ertraegen und Verlusten aus Liquidity-Pools einschliesslich Impermanent Loss. Methodik Ertragszufluss Pool-Einlage als Tausch Verlustberechnung. Output ausformulierte Pruefung mit Hinweis auf ungeklaerte Einzelfragen."
---

> Dieser Skill ersetzt keine Steuerberatung nach Paragraf 3 StBerG und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Die Ausgabe ist
> eine Arbeitshilfe ohne Gewaehr. Im Einzelfall ist eine Steuerberaterin,
> ein Steuerberater oder eine Rechtsanwaeltin/ein Rechtsanwalt zu
> konsultieren.

# DeFi-Lending und Liquidity-Pools: Ertraege und Impermanent Loss

## Zweck / Anwendungsfall

Pruefung der steuerlichen Behandlung von Ertraegen aus DeFi-Lending
(Verleihen von Kryptowerten gegen Zinsen) und aus der Bereitstellung von
Liquiditaet in Liquidity-Pools, einschliesslich der Frage, wie ein
sogenannter Impermanent Loss steuerlich zu behandeln ist.

## Eingaben

- Art der DeFi-Aktivitaet (Lending, Liquidity-Pool-Einlage, Yield
  Farming).
- Eingesetzte Token, Mengen, Zeitpunkte der Ein- und Auszahlung.
- Erhaltene Ertraege (Zinsen, Pool-Anteile, Governance-Token) mit
  Zuflusszeitpunkt und Marktwert.
- Wertentwicklung der eingesetzten Token waehrend der Pool-Teilnahme.

## Ablauf / Checkliste

1. Pruefen, ob die Einlage in einen Liquidity-Pool einen tauschaehnlichen
   Vorgang darstellt (Token gegen Pool-Anteil/LP-Token) — Einzelfallfrage,
   zu der die Verwaltungsauffassung zu pruefen ist.
2. Laufende Ertraege (Zinsen, Pool-Gebuehrenanteile) nach Zuflusszeitpunkt
   und Marktwert erfassen; Einkunftsart pruefen (i. d. R. Paragraf 22 Nr. 3
   EStG, Abgrenzung zur Gewerblichkeit beachten).
3. Ruecktausch aus dem Pool pruefen: Vergleich der zurueckerhaltenen
   Tokenmenge/-werte mit der ursprünglichen Einlage.
4. Impermanent Loss (wertmaessige Differenz durch Pool-Mechanik gegenueber
   blossem Halten) als moeglichen Verlust einordnen — Einordnung als
   Bewertungsfrage innerhalb eines etwaigen Veraeusserungsgeschaefts nach
   Paragraf 23 EStG pruefen, nicht als separate Verlustkategorie.
5. Governance-Token-Ausschuettungen gesondert nach den Regeln fuer Airdrops
   pruefen (siehe Skill `airdrop-hardfork-steuerliche-einordnung`).
6. Ergebnis ausformulieren, ungeklaerte Rechtsfragen explizit benennen.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`. Zur DeFi-
Besteuerung existiert noch keine vollstaendig gefestigte Verwaltungs- und
Rechtsprechungspraxis — entsprechende Unsicherheiten sind im Output offen
zu benennen statt mit erfundenen Fundstellen zu ueberdecken.

## Ausgabeformat

- Ausformulierte Pruefung mit klar getrennten Abschnitten fuer Ertraege und
  fuer den Ruecktausch/Impermanent Loss.
- Rechtsstand-Datum angeben.
- Ausdruecklicher Hinweis auf bestehende Rechtsunsicherheit in diesem
  Bereich.

## Beispiele

Beispiel (fiktiv): Einlage von ETH und einem Stablecoin in einen
Liquidity-Pool, laufende Gebuehrenertraege in Form von LP-Token, Ruecktausch
nach sechs Monaten mit geringerem ETH-Anteil als eingelegt (Impermanent
Loss). Laufende Ertraege werden als sonstige Einkuenfte erfasst; der
Ruecktausch wird auf einen moeglichen Veraeusserungsvorgang nach Paragraf 23
EStG hin geprueft.

## Normen und Rechtsprechung

- Paragraf 22 Nr. 3 EStG (sonstige Einkuenfte).
- Paragraf 23 EStG (privates Veraeusserungsgeschaeft).
- Aktuelles BMF-Schreiben zur ertragsteuerlichen Behandlung von virtuellen
  Waehrungen, soweit es DeFi-Sachverhalte adressiert (Datum verifizieren).
