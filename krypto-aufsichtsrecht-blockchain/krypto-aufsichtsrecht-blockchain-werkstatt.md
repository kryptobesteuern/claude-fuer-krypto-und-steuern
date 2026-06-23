# Werkstatt: krypto-aufsichtsrecht-blockchain

> Keine Rechtsberatung. Arbeitshilfe ohne Gewaehr. Im Einzelfall ist eine
> Rechtsanwaeltin oder ein Rechtsanwalt zu konsultieren.

Diese Werkstatt-Seite fuehrt ausfuehrlich durch alle Skills dieses Plugins
und zeigt, wie sie kombiniert werden, um ein Blockchain-/Token-Projekt
aufsichtsrechtlich zu pruefen.

## Typischer Pruefablauf fuer ein neues Token-Projekt

1. **Token-Klassifizierung.** Skill `token-klassifizierung-mica` nutzen,
   um den Token als E-Geld-Token, vermoegenswertreferenzierten Token oder
   sonstigen Kryptowert einzuordnen.
2. **Emittentenpflichten.** Bei stabilisierten Token zusaetzlich Skill
   `stablecoin-emittenten-pflichten-mica` anwenden.
3. **Erlaubnispflicht der Dienstleistung.** Skill
   `bafin-erlaubnispflicht-kryptowerte` nutzen, um zu pruefen, ob die
   geplante Taetigkeit (Handel, Verwahrung, Vermittlung) eine
   BaFin-Erlaubnis erfordert.
4. **AML/KYC.** Skill `aml-kyc-kryptodienstleister` nutzen, um die
   Sorgfalts- und Meldepflichten zu klaeren.
5. **Travel Rule.** Bei Kryptowerteuebertragungen zusaetzlich Skill
   `travel-rule-kryptotransfers` anwenden.
6. **Vertragsgestaltung.** Bei Einsatz von Smart Contracts Skill
   `smart-contract-haftung-zivilrecht` nutzen, um Haftungsfragen zu
   klaeren.
7. **Governance-Struktur.** Bei DAO-aehnlicher Organisation Skill
   `dao-rechtsform-einordnung` nutzen, um Haftungsrisiken der Mitglieder
   zu klaeren.
8. **Verwahrung.** Bei Custody-Angeboten Skill
   `wallet-verwahrung-haftungsfragen` nutzen.

## Typische Stolperfallen

- Die Token-Klassifizierung beeinflusst praktisch alle nachfolgenden
  Pruefungen — sie sollte immer am Anfang stehen.
- MiCAR-Durchfuehrungsstandards sind teilweise noch nicht final
  ausgearbeitet — dies in jeder Ausgabe transparent machen.
- DAO- und Smart-Contract-Haftungsfragen sind besonders
  rechtsunsicher — keine abschliessenden Aussagen ohne entsprechenden
  Vorbehalt treffen.

## Hinweis zur Aktualitaet

Vor jeder Pruefung sollten aktuelle BaFin-Merkblaetter und der Stand der
MiCAR-Durchfuehrung herangezogen werden. Fundstellen sind vor Verwendung
zu verifizieren, siehe `../references/zitierweise-krypto.md`.
