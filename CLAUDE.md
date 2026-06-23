# CLAUDE.md — Verbindliches Regelwerk

Dieses Dokument gilt fuer jedes Modell und jeden Agenten (Claude, Codex,
sonstige LLM-Werkzeuge), das in diesem Repository Skills nutzt, erweitert
oder pflegt. Es ist ein eigenstaendiges Regelwerk fuer das Themenfeld
**Krypto-Steuerrecht und angrenzendes Aufsichts-/Blockchainrecht
(Deutschland)** und kein Abdruck eines fremden Regelwerks.

## 1. Geltungsbereich und Zweck

Dieses Repository stellt Claude-Code-Skills bereit, die beim **strukturierten
Pruefen** krypto-bezogener Steuer- und Aufsichtsrechtsfragen unterstuetzen.
Es ist ein technisches Experimentierfeld fuer Steuerberater, Rechtsanwaelte,
Compliance-Funktionen und informierte Privatanwender — **kein Ersatz** fuer
eine individuelle Steuerberatung oder Rechtsberatung.

## 2. Sprache

- Alle Skill-Inhalte, READMEs und Outputs sind auf **Deutsch** verfasst,
  sofern der Nutzer nicht ausdruecklich Englisch verlangt.
- Fachbegriffe (z. B. "Staking", "Airdrop", "Smart Contract") werden in der
  international gebraeuchlichen Form verwendet, aber im Kontext deutsch
  erlaeutert.

## 3. Methodik

- Jede Pruefung folgt der Methodik aus `references/methodik-krypto-steuerrecht.md`
  (Sachverhaltsaufbereitung, Token-Qualifikation, Drei-Schritte-Steuerschema
  bzw. Aufsichtsschema, Ausformulierung).
- Zwischenergebnisse werden klar als solche markiert.
- Unsicherheiten in der Sachverhaltsaufnahme werden durch konkrete
  Rueckfragen an den Nutzer aufgeloest, statt Annahmen unausgesprochen zu
  treffen.

## 4. Quellen- und Zitierpflicht

- Verbindlich ist `references/zitierweise-krypto.md`. Kein Blindzitat aus
  reinem Modellwissen — siehe dort die harten Sperren.
- Jeder Skill-Output nennt ein **Rechtsstand-Datum**.
- Themen-Anker zur Recherche-Orientierung liefert
  `references/leitentscheidungen-krypto.md` — das sind keine fertig
  geprueften Zitate, sondern Sucheinstiege.

## 5. Gliederung und Ausformulierung

- Skill-Outputs werden in vollstaendigen Saetzen ausformuliert, nicht als
  reine Stichpunktliste.
- Numerische Gliederung (1., 1.1, 1.2, ...) fuer laengere Pruefberichte;
  kurze Antworten duerfen ohne Gliederung bleiben, wenn der Sachverhalt es
  zulaesst.
- Tabellen sind erlaubt, wo sie Lesbarkeit erhoehen (z. B. FIFO-Berechnung,
  Haltefrist-Uebersicht), ersetzen aber nicht die Ausformulierung des
  Ergebnisses.

## 6. Skill-Konvention (`SKILL.md`)

Jeder Skill liegt unter `skills/<skill-name>/SKILL.md` innerhalb eines
Plugin-Ordners und hat folgendes YAML-Frontmatter:

```yaml
---
name: <kebab-case-name, max. 64 Zeichen>
description: "<Zweck in max. 1024 Zeichen, keine Kommas in Zahlen>"
---
```

Der Markdown-Koerper enthaelt mindestens folgende Abschnitte in dieser
Reihenfolge:

1. **Zweck / Anwendungsfall** — wann wird dieser Skill genutzt?
2. **Eingaben** — welche Angaben/Unterlagen muss der Nutzer mitbringen?
3. **Ablauf / Checkliste** — Schritt-fuer-Schritt-Pruefung.
4. **Quellenpflicht** — Verweis auf `../../../references/zitierweise-krypto.md`.
5. **Ausgabeformat** — Ausformulierungspflicht, Rechtsstand-Datum,
   verbotene Formate (reine Stichpunkt-Skelette als Endergebnis).
6. **Beispiele** — mindestens ein durchgerechnetes Beispiel.
7. **Normen und Rechtsprechung** — kuratierte Liste der einschlaegigen
   Normen/Verordnungen fuer dieses Thema.

## 7. Disclaimer-Pflicht

Jede `README.md` (Root und Plugin-Ebene) und jede `SKILL.md` beginnt mit
einem klar erkennbaren Hinweis:

> Dieser Skill ersetzt keine Steuerberatung nach Paragraf 3 StBerG und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Die Ausgaben
> sind Arbeitshilfen ohne Gewaehr. Im Einzelfall ist eine Steuerberaterin,
> ein Steuerberater, eine Rechtsanwaeltin oder ein Rechtsanwalt zu
> konsultieren.

Zusaetzlich wird bei aufsichtsrechtlichen Themen auf die regulatorische
Unsicherheit und Aenderungsgeschwindigkeit (MiCAR-Durchfuehrung, BaFin-
Verwaltungspraxis) sowie bei technischen Themen auf Blockchain-spezifische
Risiken (Irreversibilitaet von Transaktionen, Custody-/Verwahrungsrisiken,
Volatilitaet) hingewiesen.

## 8. Datenschutz und Mandantendaten

- Keine echten Mandanten-, Wallet- oder Kontodaten in Beispielen,
  Testakten oder Commits. Ausschliesslich fiktive, klar als solche
  gekennzeichnete Beispieldaten.
- Keine privaten Schluessel (Seed Phrases, Private Keys) in jedweder Form
  in diesem Repository — auch nicht als Beispiel.

## 9. Versionierung

- Versionsschema `MAJOR.MINOR.PATCH`, beginnend bei `001.0.0` fuer dieses
  Projekt.
- Aenderungen werden in `CHANGELOG.md` dokumentiert.

## 10. Git-Workflow

- Aussagekraeftige Commit-Nachrichten auf Deutsch.
- Kein Force-Push auf den Hauptzweig.
- Vor jedem Merge: `python scripts/validate_yaml_frontmatter.py` und
  `python scripts/validate_plugin_structure.py` fehlerfrei durchlaufen
  lassen.
