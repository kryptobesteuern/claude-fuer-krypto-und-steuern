---
name: smart-contract-haftung-zivilrecht
description: "Prueft die zivilrechtliche Einordnung und Haftungsfragen bei der Ausfuehrung von Smart Contracts. Methodik Vertragsschluss durch Code Willensmaengel Fehlerhafte Ausfuehrung. Output ausformulierte Pruefung mit Haftungsergebnis und Beweisfragen."
---

> Dieser Skill ersetzt keine Rechtsberatung nach dem
> Rechtsdienstleistungsgesetz (RDG) und keine technische Sicherheits-
> oder Code-Audit-Garantie. Die Ausgabe ist eine Arbeitshilfe ohne
> Gewaehr. Im Einzelfall ist eine Rechtsanwaeltin oder ein Rechtsanwalt zu
> konsultieren.

# Smart Contracts: Zivilrechtliche Einordnung und Haftung

## Zweck / Anwendungsfall

Pruefung, wie die automatisierte Ausfuehrung eines Smart Contracts
zivilrechtlich einzuordnen ist und wer bei einer fehlerhaften oder
unerwuenschten Ausfuehrung haftet.

## Eingaben

- Funktionsweise des Smart Contracts (Beschreibung der ausgefuehrten
  Logik, beteiligte Parteien).
- Angabe, ob der Smart Contract eine bereits bestehende vertragliche
  Vereinbarung lediglich automatisiert oder selbst den Vertragsschluss
  herbeifuehrt.
- Beschreibung des eingetretenen Fehlers oder unerwuenschten Ergebnisses
  (z. B. Bug im Code, externe Manipulation, Orakel-Fehler).
- Beteiligte Akteure (Entwicklerin/Entwickler, Betreiberin/Betreiber,
  Nutzerin/Nutzer).

## Ablauf / Checkliste

1. Pruefen, ob durch die Interaktion mit dem Smart Contract ein
   Vertragsschluss im Sinne der Paragraf 145 ff. BGB vorliegt (Angebot und
   Annahme durch automatisierte Erklaerung).
2. Pruefen, ob Willensmaengel (z. B. Irrtum, arglistige Taeuschung) bei
   einer der Parteien vorliegen und wie sich diese gegenueber einer
   bereits automatisiert ausgefuehrten Transaktion auswirken — insbe-
   sondere die faktische Irreversibilitaet der Blockchain-Transaktion
   beachten.
3. Verantwortlichkeit fuer Programmierfehler pruefen: Vertragliche oder
   ausservertragliche Haftung der Entwicklerin/des Entwicklers oder
   Betreiberin/Betreibers nach allgemeinen Grundsaetzen (z. B.
   Paragraf 280 Abs. 1 BGB, Paragraf 823 BGB).
4. Haftungsausschluesse in zugrunde liegenden Nutzungsbedingungen auf
   Wirksamkeit pruefen (insb. AGB-Kontrolle nach Paragraf 305 ff. BGB).
5. Beweisfragen benennen (On-Chain-Daten als Beweismittel, Nachweis der
   tatsaechlichen Code-Ausfuehrung).
6. Ergebnis ausformulieren.

## Quellenpflicht

Verbindlich: `../../../references/zitierweise-krypto.md`. Zur
zivilrechtlichen Einordnung von Smart Contracts existiert noch keine
gefestigte hoechstrichterliche Rechtsprechung — dies ist im Output offen
zu benennen.

## Ausgabeformat

- Ausformulierte Pruefung mit klarer Trennung zwischen Vertragsschluss-
  frage und Haftungsfrage.
- Rechtsstand-Datum angeben.
- Ausdruecklicher Hinweis auf bestehende Rechtsunsicherheit.

## Beispiele

Beispiel (fiktiv): Ein Smart Contract fuer einen Token-Tausch fuehrt
aufgrund eines Programmierfehlers zu einem fuer eine Partei nachteiligen
Tauschverhaeltnis. Pruefung, ob ein wirksamer Vertrag zustande gekommen
ist und ob die Entwicklerin/der Entwickler des Contracts fuer den Fehler
haftet.

## Normen und Rechtsprechung

- Paragraf 145 ff. BGB (Vertragsschluss).
- Paragraf 280 Abs. 1 BGB, Paragraf 823 BGB (vertragliche/ausser-
  vertragliche Haftung).
- Paragraf 305 ff. BGB (AGB-Kontrolle).
- Einschlaegige Literatur und Rechtsprechung zu Smart Contracts (Fundstelle
  vor Verwendung verifizieren).
