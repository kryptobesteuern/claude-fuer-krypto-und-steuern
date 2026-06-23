---
name: token-klassifizierung-mica
description: "Klassifiziert einen Token nach der MiCAR-Verordnung als E-Geld-Token vermoegenswertreferenzierten Token oder sonstigen Kryptowert und grenzt zu Finanzinstrumenten ab. Methodik Drei-Stufen-Pruefung anhand Funktion und Wertbindung. Output ausformulierte Klassifizierung mit Pflichtenfolgen."
---

> Dieser Skill ersetzt keine Rechtsberatung nach dem
> Rechtsdienstleistungsgesetz (RDG) und keine aufsichtsrechtliche
> Einzelfallauskunft der BaFin. Die Ausgabe ist eine Arbeitshilfe ohne
> Gewaehr. Im Einzelfall ist eine Rechtsanwaeltin oder ein Rechtsanwalt mit
> Schwerpunkt Bank-/Kapitalmarktrecht zu konsultieren.

# Token-Klassifizierung nach MiCAR

## Zweck / Anwendungsfall

Einordnung eines Tokens nach der Verordnung (EU) 2023/1114 (Markets in
Crypto-Assets Regulation, MiCAR) als E-Geld-Token, vermoegenswert-
referenzierter Token oder sonstiger Kryptowert, sowie Abgrenzung zu
Finanzinstrumenten im Sinne der MiFID II/des WpHG.

## Eingaben

- Funktionsbeschreibung des Tokens (Zahlungsmittel, Werterhalt,
  Beteiligungsrecht, Nutzungsrecht innerhalb einer Plattform).
- Angabe, ob der Token an eine Waehrung oder einen Waehrungskorb gebunden
  ist (E-Geld-Token-Indiz) oder an mehrere Vermoegenswerte/Rechte
  referenziert (vermoegenswertreferenzierter Token).
- Emittentenstruktur (zentraler Emittent, dezentrales Protokoll).
- Handelbarkeit und Uebertragbarkeit des Tokens.

## Ablauf / Checkliste

1. Pruefen, ob der Token unter eine der MiCAR-Ausnahmen faellt
   (z. B. reine Finanzinstrumente, die bereits unter MiFID II fallen).
2. Pruefen, ob der Token ein E-Geld-Token im Sinne von Art. 3 Abs. 1 Nr. 7
   MiCAR ist (Bindung an eine einzige Fiat-Waehrung, Werterhalt-Funktion).
3. Pruefen, ob der Token ein vermoegenswertreferenzierter Token im Sinne
   von Art. 3 Abs. 1 Nr. 6 MiCAR ist (Referenzierung auf mehrere
   Vermoegenswerte, Waehrungen oder Rechte).
4. Pruefen, ob der Token ein "sonstiger Kryptowert" im Sinne von Art. 3
   Abs. 1 Nr. 5 MiCAR ist (Auffangkategorie).
5. Abgrenzung zu Finanzinstrumenten nach Art. 2 Abs. 4 MiCAR pruefen
   (insbesondere bei Token mit Beteiligungs- oder Gewinnbezugsrechten).
6. Pflichtenfolgen je Klassifizierung benennen (Whitepaper-Pflicht,
   Zulassungspflicht, laufende Informationspflichten).
7. Ergebnis ausformulieren.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`. Artikelangaben
zur MiCAR sind mit Verordnungsnummer (EU) 2023/1114 zu versehen; bei
Unsicherheit ueber die genaue Artikelnummer ist dies offen zu benennen.

## Ausgabeformat

- Ausformulierte Drei-Stufen-Pruefung mit klarem Klassifizierungsergebnis.
- Rechtsstand-Datum angeben.
- Hinweis auf laufende Durchfuehrungsstandards (technische
  Regulierungsstandards), die die Einordnung praezisieren koennen.

## Beispiele

Beispiel (fiktiv): Ein Token, der 1:1 an den Euro gebunden ist und als
Zahlungsmittel innerhalb einer Handelsplattform genutzt wird, spricht fuer
eine Einordnung als E-Geld-Token nach Art. 3 Abs. 1 Nr. 7 MiCAR mit
entsprechenden Zulassungs- und Informationspflichten fuer den Emittenten.

## Normen und Rechtsprechung

- Verordnung (EU) 2023/1114 (MiCAR), insbesondere Art. 2, Art. 3.
- WpHG/MiFID II zur Abgrenzung von Finanzinstrumenten.
- BaFin-Merkblaetter zur Token-Klassifizierung (Fundstelle und Datum
  verifizieren).
