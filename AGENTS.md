# AGENTS.md — Kurzregeln fuer alle Werkzeuge

Dieses Dokument ist ein Auszug aus `CLAUDE.md` fuer Werkzeuge (z. B. Codex),
die nicht das volle Regelwerk einlesen. Es gilt zusaetzlich, nicht
ersatzweise zu `CLAUDE.md`.

## Pflichtregeln

1. **Sprache:** Deutsch, sofern nicht ausdruecklich anders gewuenscht.
2. **Gliederung:** Numerisch (1., 1.1, 1.2, ...) bei laengeren Pruefungen;
   keine reinen Stichpunkt-Endergebnisse.
3. **Quellen:** Keine Blindzitate. Siehe `references/zitierweise-krypto.md`.
4. **Disclaimer:** Jeder Output mit Steuer- oder Rechtsbezug erhaelt den
   Hinweis aus `CLAUDE.md` Abschnitt 7 (keine Steuer-/Rechtsberatung).
5. **Skill-Frontmatter:** `name` (kebab-case, max. 64 Zeichen) und
   `description` (max. 1024 Zeichen, keine Kommas in Zahlen) — keine
   weiteren Frontmatter-Felder.
6. **Keine echten Mandanten-/Wallet-/Kontodaten und keine privaten
   Schluessel** in Beispielen oder Commits.
7. **Rechtsstand-Datum** in jedem inhaltlichen Output angeben.

## Vor jedem Commit

- `python scripts/validate_yaml_frontmatter.py`
- `python scripts/validate_plugin_structure.py`

Beide Skripte muessen fehlerfrei durchlaufen, bevor ein Commit oder PR
erstellt wird.
