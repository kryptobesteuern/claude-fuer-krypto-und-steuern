# Claude Skills für Krypto & Steuern

<p align="center">
<img src="https://github.com/user-attachments/assets/40af723c-29bc-4209-83a5-46ec4cd8ddd5" />
</p>

> **Wichtiger Hinweis:** Dieses Repository ist eine experimentelle
> Sammlung von Claude-Code-Skills zu Krypto-Steuerrecht und angrenzendem
> Aufsichts-/Blockchainrecht in Deutschland. Es ersetzt **keine**
> Steuerberatung nach Paragraf 3 Steuerberatungsgesetz (StBerG) und keine
> Rechtsberatung nach dem Rechtsdienstleistungsgesetz (RDG). Alle Ausgaben
> sind Arbeitshilfen ohne Gewaehr. Jede Nutzerin und jeder Nutzer trägt die
> alleinige Verantwortung fuer die Verwendung der erzeugten Inhalte und
> sollte im Einzelfall eine Steuerberaterin, einen Steuerberater, eine
> Rechtsanwaeltin oder einen Rechtsanwalt konsultieren.

## Worum geht es?

Dieses Repository stellt zwei Claude-Code-Plugins mit Skills bereit, die
beim strukturierten Pruefen von Krypto-Sachverhalten unterstuetzen:

| Plugin | Fokus |
|---|---|
| [`krypto-steuern-de`](krypto-steuern-de/README.md) | Ertrag- und umsatzsteuerliche Behandlung von Kryptowerten (Paragraf 23 EStG, Mining, Staking, DeFi, NFTs, Bewertung, Verlustverrechnung) |
| [`krypto-aufsichtsrecht-blockchain`](krypto-aufsichtsrecht-blockchain/README.md) | Angrenzendes Aufsichts- und Blockchainrecht (MiCAR, BaFin-Erlaubnis, AML/KYC, Travel Rule, DAO, Smart-Contract-Haftung) |

Dieses Projekt ist als erste experimentelle Sammlung angelegt und wird iterativ um weitere Plugins und Skills erweitert (siehe `CHANGELOG.md`).

## Marketplace-Installation

```
/plugin marketplace add kryptobesteuern/claude-fuer-krypto-und-steuern
```

Danach einzelne Plugins aktivieren:

```
/plugin install krypto-steuern-de@krypto-steuern-skills
/plugin install krypto-aufsichtsrecht-blockchain@krypto-steuern-skills
```

Nach der Installation einen Skill direkt aufrufen, z. B.:

```
/krypto-steuern-de:btc-eth-einkunftsart-23-estg
```

Updates einspielen:

```
/plugin marketplace update krypto-steuern-skills
```

## Schnelleinstieg (ohne Marketplace)

1. `QUICKSTART.md` lesen (2 Minuten).
2. Repository in Claude Code als Projektverzeichnis oeffnen.
3. Passenden Skill aus `SKILLS.md` oder den Plugin-READMEs waehlen.
4. Fiktiven oder anonymisierten Sachverhalt eingeben.

Ausfuehrliche Installationsanleitung fuer Einsteigerinnen und Einsteiger:
`INSTALLATION_EINFACH.md`.

## Regelwerk

Alle Skills folgen dem Regelwerk in `CLAUDE.md` (vollstaendig) und
`AGENTS.md` (Kurzfassung fuer andere Werkzeuge). Zentrale Bausteine:

- `references/zitierweise-krypto.md` — Quellenpflicht, keine Blindzitate.
- `references/methodik-krypto-steuerrecht.md` — Pruefmethodik.
- `references/leitentscheidungen-krypto.md` — Themen-Anker zur Recherche.

## Rechtliche und tatsaechliche Risikohinweise

- **Schnelle Rechtsaenderung:** Krypto-Steuer- und Aufsichtsrecht
  (insbesondere MiCAR-Durchfuehrung und BMF-/BaFin-Verwaltungspraxis)
  aendert sich fortlaufend. Jede Ausgabe nennt ein Rechtsstand-Datum.
- **Keine Code-Audit-Garantie:** Aussagen zu Smart Contracts sind
  rechtliche, keine technischen Sicherheitsbewertungen.
- **Blockchain-Irreversibilitaet und Custody-Risiken:** Transaktionen sind
  in der Regel nicht rueckholbar; Verwahrungsrisiken bei Drittanbietern
  sind gesondert zu pruefen (siehe Skill `wallet-verwahrung-haftungsfragen`).
- **Berufsrecht:** Die Nutzung der Skills durch Steuerberaterinnen/
  Steuerberater oder Rechtsanwaeltinnen/Rechtsanwaelte entbindet nicht von
  den jeweiligen berufsrechtlichen Sorgfaltspflichten.

## Lizenz

Apache-2.0 OR MIT — siehe `LICENSE`, `LICENSE-APACHE`, `LICENSE-MIT`.

## Weitere Dokumente

- `CONTRIBUTING.md` — Beitragsrichtlinien und PR-Checkliste.
- `CODE_OF_CONDUCT.md` — Verhaltenskodex.
- `CODEX.md` / `CODEX_INSTRUCTIONS_SKILL_VEREDELUNG.md` — Hinweise fuer
  andere LLM-Werkzeuge und zur Skill-Ueberarbeitung.
- `CONNECTORS.md` — Typische externe Datenquellen.
- `PROMPTLISTE.md` — Kuratierte Beispiel-Prompts.
- `EVAL_RESULTS.md` — Stand der Qualitaetsevaluation.
- `CHANGELOG.md` — Versionshistorie.
- `SKILLS.md` — Flacher Index aller Skills.

## 📚 Empfehlenswerte Leitfaeden

Wer sich vertiefend mit Krypto-Steuern beschaeftigen moechte, findet hier
zwei weiterfuehrende Buchempfehlungen (Amazon-Partnerlinks — bei einem
Kauf ueber diese Links erhaelt der Autor ggf. eine kleine Provision, ohne
Mehrkosten fuer Sie):

<table>
<tr>
<td align="center" width="50%">
<a href="https://amzn.to/3TwalFp" target="_blank">
<img src="assets/images/krypto_steuern_leitfaden.webp" alt="Krypto-Steuern Leitfaden" width="200" />
</a>
<br />
<a href="https://amzn.to/3TwalFp" target="_blank">Leitfaden zu <br />Krypto und Steuern</a>
</td>
<td align="center" width="50%">
<a href="https://amzn.to/3MYvmbI" target="_blank">
<img src="assets/images/krypto_steuern_leitfaden_bilanzierung_von_kryptowerten.webp" alt="Bilanzierung von Kryptowerten" width="200" />
</a>
<br />
<a href="https://amzn.to/3MYvmbI" target="_blank">Bilanzierung von Kryptowerten</a>
</td>
</tr>
</table>

## 🙋‍♂️ Mitwirken

Bei Fragen oder Problemen:
- 🐛 [Fehler melden](https://github.com/kryptobesteuern/claude-fuer-krypto-und-steuern/issues)
- 💡 [Feature vorschlagen](https://github.com/kryptobesteuern/claude-fuer-krypto-und-steuern/issues)
- ⭐ Gerne einen Stern geben, wenn das Projekt nuetzlich ist!

## ☕ Projekt unterstuetzen

Wer das Projekt nuetzlich findet, kann die Weiterentwicklung mit einem
Repost oder einem Kaffee unterstuetzen:

<a href="https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/kryptobesteuern/claude-fuer-krypto-und-steuern" target="_blank"> <img src="https://img.shields.io/badge/💼-Auf%20LinkedIn%20teilen-blue" /> </a>

[![Buy Me a Coffee](https://img.shields.io/badge/☕-Kaffee%20spendieren-yellow)](https://paypal.me/MarkusBegerow?country.x=DE&locale.x=de_DE)

## 📬 Kontakt

- 🧑‍💻 [Markus Begerow](https://linkedin.com/in/markusbegerow)
- 💾 [GitHub](https://github.com/markusbegerow)
- ✉️ [Twitter](https://x.com/markusbegerow)
