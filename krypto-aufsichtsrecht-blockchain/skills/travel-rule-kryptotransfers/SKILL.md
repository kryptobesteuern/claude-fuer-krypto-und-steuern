---
name: travel-rule-kryptotransfers
description: "Prueft die Pflichten zur Uebermittlung von Auftraggeber und Beguenstigtendaten bei Kryptowerteuebertragungen nach der Travel Rule Verordnung. Methodik Schwellenwerte Datenfelder Pruefpflicht. Output ausformulierte Pruefung mit konkretem Datenkatalog."
---

> Dieser Skill ersetzt keine Rechtsberatung nach dem
> Rechtsdienstleistungsgesetz (RDG). Die Ausgabe ist eine Arbeitshilfe
> ohne Gewaehr.

# Travel Rule bei Kryptowerteuebertragungen

## Zweck / Anwendungsfall

Pruefung, welche Angaben zu Auftraggeber und Beguenstigtem bei einer
Kryptowerteuebertragung nach der Verordnung (EU) 2023/1113 (Travel Rule)
zu erheben und zu uebermitteln sind.

## Eingaben

- Art der Uebertragung (zwischen zwei Kryptowertedienstleistern,
  von/zu einer Self-Hosted-Wallet).
- Beteiligte Parteien (Auftraggeber, Beguenstigter) und deren Sitz/
  Wohnsitz.
- Transaktionsbetrag.
- Vorhandene Identifizierungsdaten der Beteiligten.

## Ablauf / Checkliste

1. Pruefen, ob die Uebertragung in den Anwendungsbereich der Verordnung
   (EU) 2023/1113 faellt (Uebertragung unter Beteiligung mindestens eines
   Kryptowertedienstleisters).
2. Erforderliche Datenfelder fuer den Auftraggeber bestimmen (Name,
   Kontonummer/Wallet-Adresse, Anschrift bzw. alternative Identifikatoren).
3. Erforderliche Datenfelder fuer den Beguenstigten bestimmen.
4. Besonderheiten bei Uebertragungen an oder von Self-Hosted-Wallets
   pruefen (zusaetzliche Sorgfaltspflichten ab bestimmten Schwellenwerten).
5. Pruefpflichten des empfangenden Kryptowertedienstleisters hinsichtlich
   Vollstaendigkeit und Plausibilitaet der erhaltenen Daten benennen.
6. Ergebnis mit konkretem Datenkatalog ausformulieren.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`.

## Ausgabeformat

- Ausformulierte Pruefung mit tabellarischer Auflistung der erforderlichen
  Datenfelder.
- Rechtsstand-Datum angeben.

## Beispiele

Beispiel (fiktiv): Ein Kryptowertedienstleister fuehrt eine Uebertragung
von 5.000 Euro Gegenwert an eine Self-Hosted-Wallet eines Kunden durch.
Dies aktiviert zusaetzliche Sorgfaltspflichten zur Verifizierung, dass der
Kunde tatsaechlich Inhaber der Self-Hosted-Wallet ist.

## Normen und Rechtsprechung

- Verordnung (EU) 2023/1113 (Geldtransferverordnung, Travel Rule fuer
  Kryptowerte).
- Geldwaeschegesetz (GwG) in Verbindung mit Skill
  `aml-kyc-kryptodienstleister`.
- BaFin-Hinweise zur Umsetzung der Travel Rule (Fundstelle und Datum
  verifizieren).
