# Konnektoren / Datenquellen

Dieses Repository selbst stellt keine Live-Datenintegration bereit. Die
folgende Liste beschreibt, welche externen Datenquellen typischerweise als
**Eingabe** fuer die Skills dieses Repositories dienen und worauf beim
Import zu achten ist.

| Quelle | Typischer Export | Hinweis |
|---|---|---|
| Krypto-Boersen (z. B. Kraken, Binance, Coinbase) | CSV/Excel-Transaktionshistorie | Zeitzonen und Gebuehrenfelder pruefen, bevor sie in eine Skill-Eingabe uebernommen werden. |
| Steuer-Tools fuer Krypto (z. B. CoinTracking, Blockpit, Accointing) | CSV/PDF-Steuerreport | Ersetzt keine eigene Pruefung der Einkunftsart; Reports koennen Klassifizierungsfehler enthalten. |
| DATEV (Kanzleisoftware) | Mandantendaten, Buchungsstapel | Keine echten Mandantendaten in dieses Repository einspielen; nur fiktive Beispieldaten verwenden. |
| Block-Explorer (z. B. Etherscan, Blockchair) | On-Chain-Transaktionsdaten | Fuer Verifikation einzelner Transaktionen, nicht fuer automatisierten Massenimport vorgesehen. |
| Wallets (Hardware/Software) | Transaktionsexport | Niemals private Schluessel oder Seed Phrases exportieren oder in Beispiele uebernehmen. |

## Hinweis

Die Skills in diesem Repository sind textbasierte Pruefhilfen fuer Claude
Code und vergleichbare Werkzeuge. Eine automatisierte API-Anbindung an die
oben genannten Quellen ist nicht Teil dieses Repositories.
