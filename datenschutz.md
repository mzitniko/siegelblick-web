# Datenschutzerklärung für SiegelBlick

Stand: 30. August 2026

## 1. Verantwortlicher

Maxim Zitnikowski
Kronprinzstraße 6
32257 Bünde
Deutschland

E-Mail: info@mzitniko.de

Ein Datenschutzbeauftragter ist nicht bestellt; die Voraussetzungen des
Art. 37 DSGVO und des § 38 BDSG liegen nicht vor.

## 2. Das Wichtigste in Kürze

SiegelBlick liest den Barcode einer Lebensmittelverpackung und fragt bei der
offenen Datenbank Open Food Facts nach, ob dort für dieses Produkt ein
Nachhaltigkeitssiegel eingetragen ist.

- Es gibt **kein Nutzerkonto** und keine Registrierung.
- Es findet **kein Tracking** statt, es werden **keine Werbe-Identifikatoren**
  verwendet und **keine Analyse- oder Absturzberichte** erhoben.
- Es wird **keine Scan-Historie** geführt — weder auf dem Gerät noch anderswo.
- **Kamerabilder verlassen das Gerät nicht.** Die Auswertung des Barcodes
  geschieht vollständig auf dem Gerät; es werden keine Fotos gespeichert oder
  übertragen.
- Auf dem Gerät werden **genau zwei Werte** gespeichert (siehe Abschnitt 3.5).

Personenbezogene Daten verlassen das Gerät nur in den unter 3.1 bis 3.3
beschriebenen Fällen — im Kern ist das die **IP-Adresse**, die bei jeder
Verbindung technisch notwendig übertragen wird.

## 3. Verarbeitungen im Einzelnen

### 3.1 Abfrage bei Open Food Facts

**Wann:** Sobald ein Barcode erkannt wurde.

**Welche Daten:**

- der **gescannte Barcode** (die Ziffernfolge der Verpackung)
- Ihre **IP-Adresse** (technisch notwendig für jede Internetverbindung)
- ein **User-Agent** mit dem Inhalt `SiegelBlick/1.0.0 (info@mzitniko.de)` —
  die enthaltene Kontaktadresse ist meine eigene, nicht Ihre; Open Food Facts
  verlangt sie, um Betreiber von Anwendungen bei technischen Problemen
  erreichen zu können

**Zweck:** Nachschlagen, ob für das Produkt ein Siegel eingetragen ist. Ohne
diese Übermittlung kann die App ihre einzige Funktion nicht erfüllen.

**Empfänger:** Open Food Facts, Association Loi 1901, 21 rue des Iles,
94100 Saint-Maur des Fossés, Frankreich.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Erfüllung des
Nutzungsverhältnisses — Sie haben die Abfrage durch das Scannen ausgelöst),
hilfsweise Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an einer
funktionsfähigen App).

**Wichtig zum Verhältnis:** Open Food Facts ist **eigenständig
Verantwortlicher**, nicht mein Auftragsverarbeiter. Die Organisation
entscheidet selbst über Zwecke und Mittel der Verarbeitung auf ihren Servern;
ich habe darauf keinen Einfluss und keinen Zugriff. Es besteht daher kein
Auftragsverarbeitungsvertrag nach Art. 28 DSGVO, sondern eine Weitergabe an
einen Dritten, über die ich Sie hiermit nach Art. 13 Abs. 1 lit. e DSGVO
unterrichte. Es gilt die Datenschutzerklärung von Open Food Facts:
<https://world.openfoodfacts.org/privacy>

Frankreich ist Mitgliedstaat der Europäischen Union. Eine Übermittlung in ein
Drittland findet durch diese Abfrage nicht statt; es gilt unmittelbar die
DSGVO.

### 3.2 Produktbild

**Wann:** Nur wenn Open Food Facts zu dem Produkt ein Bild hinterlegt hat.

**Welche Daten:** Ihre IP-Adresse gegenüber dem bildausliefernden Server.

**Zweck:** Anzeige des Produktbilds, damit Sie erkennen können, ob das
nachgeschlagene Produkt das ist, das Sie in der Hand halten.

**Begrenzung:** Die App lädt Bilder ausschließlich über `https` und
ausschließlich von Hosts unterhalb von `openfoodfacts.org`. Verweist ein
Datensatz auf eine andere Adresse, wird das Bild **nicht** geladen. Das ist
eine bewusste Schutzmaßnahme: Die Datenbank ist gemeinschaftlich gepflegt, und
ohne diese Prüfung könnte ein fremder Eintrag Ihre IP-Adresse an einen
beliebigen Dritten verraten.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO, hilfsweise lit. f DSGVO.

### 3.3 Links zu den Siegel-Quellen

**Wann:** Nur wenn Sie in den Einstellungen aktiv auf einen Quellenverweis
tippen. Ohne Ihr Zutun geschieht hier nichts.

**Was passiert:** Die Adresse wird an den Browser Ihres Geräts übergeben und
dort geöffnet. Ab diesem Moment befinden Sie sich nicht mehr in der App, und
es gilt die Datenschutzerklärung des jeweiligen Anbieters. Dieser erfährt
insbesondere Ihre IP-Adresse.

Betroffen sind folgende Anbieter:

| Siegel | Ziel |
|---|---|
| Rainforest Alliance | `rainforest-alliance.org`, `knowledge.rainforest-alliance.org` |
| Fairtrade | `fairtrade.net` |
| Demeter | `demeter.de` |
| Naturland | `naturland.de` |
| Bioland | `bioland.de` |
| MSC | `msc.org` |
| ASC | `de.asc-aqua.org` |
| Ohne Gentechnik | `ohnegentechnik.org` |
| Datenquelle / Lizenz | `world.openfoodfacts.org`, `opendatacommons.org` |

**Hinweis zum Drittlandbezug:** Ein Teil dieser Anbieter sitzt außerhalb der
EU oder betreibt seine Seiten über Dienstleister außerhalb der EU. Da der
Aufruf ausschließlich durch Ihre bewusste Handlung im externen Browser
erfolgt, findet insoweit keine Übermittlung durch mich statt.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Sie haben den Aufruf
ausgelöst).

### 3.4 Kamera

Die App benötigt Zugriff auf die Kamera, um den Barcode zu lesen. Das System
fragt Sie vor dem ersten Zugriff um Erlaubnis; Sie können sie jederzeit in den
Systemeinstellungen widerrufen.

**Die Auswertung geschieht vollständig auf Ihrem Gerät.** Es werden keine
Fotos, keine Videos und keine Vorschaubilder gespeichert oder übertragen. An
Open Food Facts geht ausschließlich die erkannte Ziffernfolge, nicht das Bild.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO.

### 3.5 Auf dem Gerät gespeicherte Daten

Die App speichert lokal auf Ihrem Gerät **genau zwei Werte**:

1. **Die Auswahl der beobachteten Siegel** — welche der neun Siegel
   nachgeschlagen werden sollen (Schlüssel `enabled_seal_ids`).
2. **Ein Schalter, ob die Einführung bereits gelaufen ist** — damit sie nicht
   bei jedem Start erscheint (Schlüssel `onboarding_seen`).

Mehr wird nicht gespeichert. Insbesondere keine Scan-Historie, keine Barcodes,
keine Produktdaten und keine Kennungen.

Beide Werte verlassen das Gerät nicht. Sie werden über die
Systemschnittstelle für App-Einstellungen abgelegt und mit der Deinstallation
der App gelöscht.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO. Nach § 25 Abs. 2 Nr. 2 TDDDG
ist für diese Speicherung keine Einwilligung erforderlich, da sie zur
Bereitstellung der von Ihnen ausdrücklich gewünschten Funktion unbedingt
erforderlich ist: Ohne den ersten Wert wüsste die App bei jedem Start nicht,
wonach sie suchen soll, ohne den zweiten liefe die Einführung endlos erneut.

## 4. Was nicht stattfindet

Damit kein Zweifel bleibt — die App verarbeitet **nicht**:

- Name, E-Mail-Adresse oder sonstige Kontaktdaten von Ihnen
- Standortdaten
- Werbe-Identifikatoren (IDFA/AAID) oder sonstige geräteübergreifende Kennungen
- Nutzungsstatistiken, Analyse- oder Absturzberichte
- Kontakte, Kalender, Fotos oder andere Gerätedaten
- eine Historie Ihrer Scans

Es findet **kein App-übergreifendes Tracking** statt. Es sind **keine
Werbe-, Analyse- oder Social-Media-SDKs** eingebunden.

## 5. Speicherdauer und Löschung

**Auf Ihrem Gerät:** Die beiden Werte aus Abschnitt 3.5 bleiben gespeichert,
bis Sie die App deinstallieren. Danach werden sie vom Betriebssystem
zusammen mit der App entfernt. Ein Zurücksetzen ohne Deinstallation ist über
die Einstellungen der App möglich, indem Sie die Siegel-Auswahl wieder auf den
Ausgangszustand bringen.

**Bei mir:** Es werden **keine** Daten von Ihnen gespeichert. Ich betreibe
keinen Server, keine Datenbank und kein Analysewerkzeug. Es gibt daher auch
keine Datensätze, die gelöscht werden könnten. Schreiben Sie mir eine E-Mail,
verarbeite ich diese natürlich, um sie zu beantworten; sie wird gelöscht,
sobald der Vorgang abgeschlossen ist und keine Aufbewahrungspflichten
entgegenstehen.

**Bei Open Food Facts:** Über Aufbewahrungsfristen auf den Servern von Open
Food Facts entscheidet die Organisation selbst. Ich habe darauf keinen
Zugriff. Wenden Sie sich für Auskunft oder Löschung dorthin — die Kontaktdaten
stehen in deren Datenschutzerklärung (siehe 3.1).

## 6. Ihre Rechte

Ihnen stehen gegenüber dem Verantwortlichen folgende Rechte zu:

- **Auskunft** über die zu Ihnen verarbeiteten Daten (Art. 15 DSGVO)
- **Berichtigung** unrichtiger Daten (Art. 16 DSGVO)
- **Löschung** (Art. 17 DSGVO)
- **Einschränkung der Verarbeitung** (Art. 18 DSGVO)
- **Datenübertragbarkeit** (Art. 20 DSGVO)
- **Widerspruch** gegen Verarbeitungen auf Grundlage berechtigter Interessen
  (Art. 21 DSGVO)

Wenden Sie sich dafür an die oben genannte Adresse oder an info@mzitniko.de.

**Bitte beachten Sie:** Da ich keine Daten über Sie speichere und Sie mir
gegenüber nicht identifizierbar sind, kann ich Auskunfts- und Löschbegehren
meist nur mit dem Hinweis beantworten, dass keine Daten vorliegen
(Art. 11 Abs. 2 DSGVO). Das ist kein Ausweichen, sondern die Folge davon, dass
die App ohne Konto arbeitet.

**Widerruf und Beendigung:** Eine Einwilligung wird nicht eingeholt, weil die
Verarbeitung nicht darauf beruht — es gibt daher nichts zu widerrufen. Sie
beenden jede Verarbeitung, indem Sie keinen Barcode mehr scannen, den
Kamerazugriff in den Systemeinstellungen entziehen oder die App
deinstallieren.

**Beschwerderecht:** Sie können sich bei einer Datenschutz-Aufsichtsbehörde
beschweren, insbesondere in dem Mitgliedstaat Ihres Aufenthaltsorts, Ihres
Arbeitsplatzes oder des Orts des mutmaßlichen Verstoßes (Art. 77 DSGVO). Für
mich zuständig ist die Landesbeauftragte für Datenschutz und
Informationsfreiheit Nordrhein-Westfalen, Kavalleriestr. 2–4,
40213 Düsseldorf (Postfach 20 04 44, 40102 Düsseldorf),
<https://www.ldi.nrw.de>.

## 7. Bezug der App über den App Store

Der Bezug der App erfolgt über den App Store von Apple. Dabei verarbeitet
Apple Daten in eigener Verantwortung — etwa Ihre Apple-Account-Kennung, den
Zeitpunkt des Downloads und Ihr Gerät. Auf diese Verarbeitung habe ich keinen
Einfluss; es gilt die Datenschutzerklärung von Apple:
<https://www.apple.com/legal/privacy/de-ww/>

## 8. Diese Webseite

Die Abschnitte 1 bis 7 beschreiben die **App**. Für die Seiten, auf denen Sie
diesen Text gerade lesen, gilt zusätzlich Folgendes.

Die Seiten werden über **GitHub Pages** bereitgestellt, einen Dienst der
GitHub, Inc., 88 Colin P. Kelly Jr. St., San Francisco, CA 94107, USA. Beim
Aufruf überträgt Ihr Browser technisch notwendige Daten an GitHub,
insbesondere Ihre **IP-Adresse**, Datum und Uhrzeit, die aufgerufene Adresse
sowie Browser- und Betriebssystemangaben. GitHub verarbeitet diese Daten in
eigener Verantwortung, um die Seiten auszuliefern und deren Sicherheit zu
gewährleisten. Ich habe darauf keinen Zugriff und werte nichts aus.

Es werden **keine Cookies** gesetzt, keine Zählpixel eingebunden, keine
Schriften oder Skripte von Dritten nachgeladen und keine
Reichweitenmessung betrieben.

**Übermittlung in die USA:** GitHub ist unter dem EU-U.S. Data Privacy
Framework zertifiziert (einsehbar unter
<https://www.dataprivacyframework.gov/>) und stützt Übermittlungen ergänzend
auf die Standardvertragsklauseln der EU-Kommission nach dem
Durchführungsbeschluss 2021/914. Für die USA besteht damit ein
Angemessenheitsbeschluss der Europäischen Kommission.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse an
einer kostengünstigen, zuverlässigen Bereitstellung dieser Pflichtangaben.

Einzelheiten zur Verarbeitung durch GitHub:
<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>

## 9. Sicherheit

Die Abfrage bei Open Food Facts erfolgt ausschließlich über eine
verschlüsselte Verbindung (`https`). Produktbilder werden ebenfalls nur über
`https` und nur von Hosts unterhalb von `openfoodfacts.org` geladen.

## 10. Änderungen dieser Erklärung

Ändert sich die App, ändert sich diese Erklärung mit. Maßgeblich ist die
jeweils unter dieser Adresse abrufbare Fassung; das Datum oben zeigt den
Stand.
