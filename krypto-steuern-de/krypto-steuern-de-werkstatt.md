# Werkstatt: krypto-steuern-de

> Keine Steuerberatung, keine Rechtsberatung. Arbeitshilfe ohne Gewaehr.
> Im Einzelfall ist eine Steuerberaterin, ein Steuerberater, eine
> Rechtsanwaeltin oder ein Rechtsanwalt zu konsultieren.

Diese Werkstatt-Seite fuehrt ausfuehrlich durch alle Skills dieses Plugins
und zeigt, wie sie kombiniert werden, um einen vollstaendigen
Krypto-Steuersachverhalt zu pruefen.

## Typischer Pruefablauf fuer eine Privatperson

1. **Transaktionshistorie aufbereiten.** Alle Anschaffungen und
   Veraeusserungen chronologisch erfassen (Datum, Menge, Preis in Euro,
   Gebuehren).
2. **Bewertungsmethode festlegen.** Skill `fifo-lifo-bewertungsmethode`
   nutzen, um die Zuordnungsmethode zu bestimmen und konsistent
   anzuwenden.
3. **Haltefristen je Tranche ermitteln.** Skill
   `haltefrist-anschaffung-veraeusserung` nutzen, um zu pruefen, welche
   Veraeusserungen innerhalb der Jahresfrist liegen.
4. **Grundpruefung Veraeusserungsgeschaeft.** Skill
   `btc-eth-einkunftsart-23-estg` fuer jede relevante Tranche anwenden.
5. **Sonderfaelle pruefen.** Je nach Sachverhalt zusaetzlich:
   - `staking-rewards-besteuerung` bei Staking-Ertraegen,
   - `mining-gewerblich-oder-privat` bei eigenem Mining,
   - `defi-lending-impermanent-loss-steuer` bei DeFi-Aktivitaeten,
   - `airdrop-hardfork-steuerliche-einordnung` bei Airdrops/Hardforks,
   - `nft-besteuerung-ust-est` bei NFT-Transaktionen,
   - `token-swap-tausch-steuerfolgen` bei direkten Krypto-Krypto-Tauschen.
6. **Verluste verrechnen.** Skill `verlustverrechnung-krypto` anwenden,
   wenn im Kalenderjahr auch Verluste entstanden sind.
7. **Unternehmensfall.** Bei bilanzierenden Unternehmen zusaetzlich Skill
   `bilanzierung-unternehmen-krypto-bewertung` anwenden.
8. **Abschluss-Check.** Skill `bmf-schreiben-krypto-checkliste` nutzen, um
   das Ergebnis gegen vom Nutzer beigebrachte Verwaltungsauffassungen
   abzugleichen.

## Typische Stolperfallen

- Unterschiedliche Wallets/Boersen ohne einheitliche
  Verbrauchsfolgefiktion fuehren zu Inkonsistenzen — vor Beginn der
  Pruefung klaeren, welche Methode angewendet wird.
- Staking- oder Lending-Nutzung kann die Haltefrist beeinflussen — dies
  immer explizit abfragen, bevor eine Haltefrist als "unter einem Jahr"
  oder "ueber einem Jahr" eingeordnet wird.
- Bei DeFi- und NFT-Sachverhalten besteht erhoehte Rechtsunsicherheit —
  dies in jeder Ausgabe transparent machen.

## Hinweis zur Aktualitaet

Vor jeder Pruefung sollte das aktuell gueltige BMF-Schreiben zur
ertragsteuerlichen Behandlung von virtuellen Waehrungen und sonstigen
Token herangezogen werden. Der Wortlaut ist vom Nutzer beizubringen, siehe
Skill `bmf-schreiben-krypto-checkliste`.
