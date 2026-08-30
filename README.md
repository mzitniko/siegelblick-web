# docs/ — Texte für die Veröffentlichung

Diese Dateien gehören **nicht** in die App, sondern auf die öffentlichen
Seiten unter `mzitniko.de`. App Store Connect verlangt zwei davon als URL,
bevor die App eingereicht werden kann.

| Datei | Wofür | Pflicht |
|---|---|---|
| [datenschutz.md](datenschutz.md) | Privacy Policy URL in App Store Connect | ja — Guideline 5.1.1(i) |
| [support.md](support.md) | Support URL in App Store Connect | ja |
| [impressum.md](impressum.md) | Anbieterkennzeichnung | ja — § 18 Abs. 1 MStV |

## Veröffentlichung über GitHub Pages

Dieser Ordner ist als Quelle für GitHub Pages eingerichtet:

1. Im Repository **Settings → Pages**
2. *Source*: **Deploy from a branch**
3. *Branch*: `main`, Ordner **`/docs`**, dann *Save*

Nach ein bis zwei Minuten liegt die Seite unter
`https://<benutzername>.github.io/siegelblick/`. Die Markdown-Dateien werden
dabei automatisch zu HTML — `datenschutz.md` wird zu `…/siegelblick/datenschutz`.

`index.md` ist die Startseite. **Ohne sie nähme GitHub Pages `README.md`** —
also diese Arbeitsnotizen — als Startseite. `_config.yml` schließt die Datei
deshalb zusätzlich von der Auslieferung aus; im Repository bleibt sie sichtbar.

**Eigene Domain (optional):** Eine Datei `docs/CNAME` mit dem Inhalt
`siegelblick.mzitniko.de` (oder einer anderen Subdomain) anlegen und beim
DNS-Anbieter einen CNAME-Eintrag auf `<benutzername>.github.io` setzen. Danach
in den Pages-Einstellungen *Enforce HTTPS* aktivieren. Die URLs in App Store
Connect sollten erst eingetragen werden, wenn die Domain steht — ein
nachträglicher Wechsel ist möglich, aber jede Änderung an den Metadaten kann
eine erneute Prüfung auslösen.

## Vor der Veröffentlichung

**Alle Platzhalter ersetzen.** Sie sind mit spitzen Doppelklammern markiert und
lassen sich so finden:

```bash
grep -rn "«PLATZHALTER" docs/
```

Offen sind durchgehend dieselben Angaben: Name, ladungsfähige Anschrift,
Aufsichtsbehörde des Bundeslandes, Datum, und die URL der Datenschutzerklärung
für die Verlinkung aus `support.md`.

**Den Hinweisblock in `impressum.md` entfernen.** Er steht unter einer
Trennlinie am Ende und ist als Arbeitsnotiz gedacht, nicht zur
Veröffentlichung.

## Was auch in die App muss

Zwei Dinge stehen doppelt — auf der Webseite **und** im Info-Screen der App:

1. **Der Link zur Datenschutzerklärung.** Guideline 5.1.1(i) verlangt ihn im
   Metadatenfeld *und* „within the app in an easily accessible manner". Der
   Link fehlt in `info_screen.dart` bisher vollständig.
2. **Name und Anschrift** aus dem Impressum.

Beim Einbau in den Info-Screen gilt **Regel 4**: Der Screen ist symbolfrei,
ein Test verbietet dort jedes `Icon` und `Image`. Ein Kettensymbol oder ein
Pfeil nach außen scheidet also aus — der Link muss sich über Wortlaut und
Farbe zu erkennen geben.

## Woher die Angaben stammen

Der Datenfluss in `datenschutz.md` ist nicht geschätzt, sondern aus dem Code
abgelesen:

| Angabe | Quelle im Code |
|---|---|
| Endpunkt und `fields`-Filter | `app/lib/lookup/off_client.dart` |
| User-Agent `SiegelBlick/1.0.0 (info@mzitniko.de)` | `off_client.dart`, `kUserAgent` |
| Bild nur `https` und nur unter `openfoodfacts.org` | `lookup_result.dart`, `Product._imageUrl` |
| die elf Quell-Hosts der Siegel | `app/lib/lookup/seals.dart` |
| die zwei gespeicherten Schlüssel | `settings.dart` (`enabled_seal_ids`), `onboarding.dart` (`onboarding_seen`) |

**Ändert sich einer dieser Werte, muss die Datenschutzerklärung mit.** Das
gilt besonders für die beiden gespeicherten Werte: Ihre Aufzählung steht
wörtlich an vier Stellen — hier, im Info-Screen, im README und in `CLAUDE.md`.

## Vorbehalt

Die Texte sind sorgfältig und anhand des tatsächlichen Codeverhaltens
geschrieben, aber sie sind keine Rechtsberatung. Zwei Punkte gehören vor der
Veröffentlichung zu jemandem vom Fach:

- ob eine c/o-Adresse oder ein Impressumsservice als ladungsfähige Anschrift
  genügt (siehe Hinweisblock in `impressum.md`)
- die DSA-Trader-Erklärung in App Store Connect, die davon getrennt zu
  entscheiden ist
