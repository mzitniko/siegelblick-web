# Datenschutzerklärung für SiegelBlick

Stand: 30. September 2026

## 1. Verantwortlicher

Maxim Zitnikowski<br>
Kronprinzstraße 6<br>
32257 Bünde<br>
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
  verwendet, und die App selbst erhebt **keine Analyse- oder
  Absturzberichte**.
- **Nur Android:** Dort erkennt die Bibliothek ML Kit von Google den Barcode.
  Sie meldet Google technische Nutzungs- und Diagnosedaten, darunter eine
  Kennung dieser Installation. Kamerabild und Barcode schickt sie nach
  Googles Angaben nicht mit (Abschnitt 3.6).
- Es wird **keine Scan-Historie** geführt — weder auf dem Gerät noch anderswo.
- **Kamerabilder verlassen das Gerät nicht.** Die Auswertung des Barcodes
  geschieht vollständig auf dem Gerät; es werden keine Fotos gespeichert oder
  übertragen.
- Die App speichert auf dem Gerät **genau drei Werte** (siehe Abschnitt 3.5).
- Sie können **freiwillig melden**, wenn ein Siegel auf der Packung steht,
  aber kein Eintrag vorliegt. Dabei werden der Barcode und Ihre Auswahl an
  einen Server in Deutschland übertragen (Abschnitt 3.7). Ohne Ihr Tippen
  auf „Melden“ geschieht das nicht.

Personenbezogene Daten verlassen das Gerät nur in den unter 3.1 bis 3.3, 3.7
und — nur auf Android — 3.6 beschriebenen Fällen. Im Kern ist das die
**IP-Adresse**, die bei jeder Verbindung technisch notwendig übertragen wird,
auf Android zusätzlich die Kennung aus Abschnitt 3.6.

## 3. Verarbeitungen im Einzelnen

### 3.1 Abfrage bei Open Food Facts

**Wann:** Sobald ein Barcode erkannt wurde.

**Welche Daten:**

- der **gescannte Barcode** (die Ziffernfolge der Verpackung)
- Ihre **IP-Adresse** (technisch notwendig für jede Internetverbindung)
- ein **User-Agent** aus App-Name, Versionsnummer und Kontaktadresse, etwa
  `SiegelBlick/1.0.7 (info@mzitniko.de)` — die enthaltene Kontaktadresse ist
  meine eigene, nicht Ihre; Open Food Facts verlangt sie, um Betreiber von
  Anwendungen bei technischen Problemen erreichen zu können

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

**Die Auswertung geschieht vollständig auf Ihrem Gerät** — auf iOS mit Apples
Vision, auf Android mit Googles ML Kit (siehe 3.6). Es werden keine Fotos,
keine Videos und keine Vorschaubilder gespeichert oder übertragen. An Open
Food Facts geht ausschließlich die erkannte Ziffernfolge, nicht das Bild.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO.

### 3.5 Auf dem Gerät gespeicherte Daten

Die App speichert lokal auf Ihrem Gerät **genau drei Werte**:

1. **Die Auswahl der beobachteten Siegel** — welche der neun Siegel
   nachgeschlagen werden sollen (Schlüssel `enabled_seal_ids`).
2. **Ein Schalter, ob die Einführung bereits gelaufen ist** — damit sie nicht
   bei jedem Start erscheint (Schlüssel `onboarding_seen`).
3. **Ein Zähler der heutigen Meldungen** — das heutige Datum und die Anzahl
   der Meldungen, die Sie heute abgeschickt haben, in der Form `2026-09-30:3`
   (Schlüssel `meldung_kontingent`). Er begrenzt die Meldungen auf 25 am Tag
   und verhindert, dass versehentlich in einer Schleife gemeldet wird.

Mehr wird nicht gespeichert. Insbesondere keine Scan-Historie, keine Barcodes,
keine Produktdaten und keine Kennungen. **Auch die Barcodes, die Sie gemeldet
haben, werden nicht gespeichert** — die App merkt sie sich nur, solange sie
läuft, und vergisst sie beim Beenden.

Auf Android legt die Barcode-Erkennung von Google zusätzlich eine eigene
Kennung dieser Installation an (Abschnitt 3.6). Die App selbst liest sie
nicht und hat keinen Einfluss auf sie.

Diese Werte verlassen das Gerät nicht. Sie werden über die
Systemschnittstelle für App-Einstellungen abgelegt und mit der Deinstallation
der App gelöscht.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO. Nach § 25 Abs. 2 Nr. 2 TDDDG
ist für diese Speicherung keine Einwilligung erforderlich, da sie zur
Bereitstellung der von Ihnen ausdrücklich gewünschten Funktion unbedingt
erforderlich ist: Ohne den ersten Wert wüsste die App bei jedem Start nicht,
wonach sie suchen soll, ohne den zweiten liefe die Einführung endlos erneut,
und ohne den dritten ließe sich die Meldegrenze nicht einhalten, die Sie und
meinen Server vor versehentlichen Mehrfachmeldungen schützt.

### 3.6 Barcode-Erkennung auf Android (Google ML Kit)

**Betrifft nur die Android-Fassung.** Auf iOS erkennt das Betriebssystem den
Barcode selbst (Apple Vision); dort findet das Folgende nicht statt.

Auf Android erkennt die Bibliothek **ML Kit** von Google den Barcode, direkt
auf dem Gerät. Kamerabild und erkannte Ziffernfolge schickt ML Kit nach den
Bedingungen von Google **nicht** an Google.

ML Kit meldet Google jedoch von sich aus Nutzungs- und Diagnosedaten. Nach
Googles eigener Offenlegung sind das:

- Geräteangaben: Hersteller, Modell, Android-Version und Build, vorhandene
  Beschleuniger für maschinelles Lernen
- App-Angaben: Paketname und App-Version
- eine **Kennung dieser Installation**, die nach Googles Angaben nicht dazu
  bestimmt ist, Sie oder Ihr Gerät eindeutig zu identifizieren
- Angaben zur Erkennung selbst: Dauer, Bildformat und Auflösung, Größe von
  Ein- und Ausgabe, Version, Art des Ereignisses und Fehlercodes
- technisch bedingt Ihre **IP-Adresse**

**Zweck:** Google nutzt diese Daten nach eigenen Angaben, um die Leistung von
ML Kit zu messen, Fehler zu beheben, ML Kit zu warten und zu verbessern und
Missbrauch zu erkennen.

**Empfänger:** Google LLC, 1600 Amphitheatre Parkway, Mountain View,
CA 94043, USA. Google verarbeitet diese Daten in eigener Verantwortung. Ich
erhalte sie nicht und habe keinen Zugriff darauf. Nach Googles Angaben werden
sie verschlüsselt übertragen und nicht an Dritte weitergegeben.

**Übermittlung in die USA:** Google LLC ist unter dem EU-U.S. Data Privacy
Framework zertifiziert (einsehbar unter
<https://www.dataprivacyframework.gov/>). Für die USA besteht damit ein
Angemessenheitsbeschluss der Europäischen Kommission.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO. Mein berechtigtes Interesse
liegt in einer zuverlässigen Barcode-Erkennung, die vollständig auf dem Gerät
arbeitet und kein Kamerabild übermittelt. Eine Möglichkeit, die Meldung an
Google abzuschalten, sieht Google nicht vor.

**Speicherdauer und Widerspruch:** Wie lange Google die Daten aufbewahrt,
entscheidet Google; ich habe darauf keinen Einfluss. Sie können der
Verarbeitung nach Art. 21 DSGVO widersprechen. Praktisch endet sie, wenn Sie
die App auf Android nicht mehr verwenden oder deinstallieren.

Einzelheiten bei Google:
<https://developers.google.com/ml-kit/android-data-disclosure> und in der
Datenschutzerklärung von Google: <https://policies.google.com/privacy>

### 3.7 Meldung eines fehlenden Eintrags (freiwillig)

**Wann:** Nur wenn Sie auf dem Ergebnis-Bildschirm auf „Melden" tippen, im
Meldeblatt Siegel ankreuzen und dort erneut auf „Melden" tippen. **Ohne diese
beiden Handlungen wird nichts übertragen.** Die Funktion ist freiwillig; die
App ist ohne sie vollständig nutzbar.

**Welche Daten:**

- der **gescannte Barcode**
- die **von Ihnen angekreuzten Siegel** (eine bis neun der bekannten
  Kennungen)
- das **Betriebssystem** in der Form `android` oder `ios`
- die **Version der App**, etwa `1.0.7`
- Ihre **IP-Adresse** (technisch notwendig für jede Internetverbindung)

**Was nicht übertragen wird:** kein Name, keine E-Mail-Adresse, kein Konto,
keine Kennung Ihres Geräts, kein Kamerabild, kein Freitext.

**Was gespeichert wird:** Die ersten vier Angaben sowie der Zeitpunkt der
Meldung. **Ihre IP-Adresse wird nicht gespeichert.** Sie wird für die
Verbindung benötigt und danach verworfen.

**Zweck:** Open Food Facts wird ehrenamtlich gepflegt und ist lückenhaft. Ihre
Meldung sagt mir, wo ich nachsehen soll. Ob daraus ein Eintrag wird, prüfe ich
selbst an der Verpackung; Ihre Meldung wird nicht ungeprüft übernommen.

**Empfänger:** Microsoft Ireland Operations Limited, One Microsoft Place,
South County Business Park, Leopardstown, Dublin 18, Irland, als mein
**Auftragsverarbeiter** nach Art. 28 DSGVO. Grundlage ist der
Datenschutznachtrag von Microsoft für Produkte und Dienste
(<https://www.microsoft.com/licensing/docs/view/Microsoft-Products-and-Services-Data-Protection-Addendum-DPA>).

Anders als bei Open Food Facts (Abschnitt 3.1) bin **ich** hier der
Verantwortliche: Die Daten liegen in meinem Speicherkonto, und nur ich lese
sie.

**Serverstandort:** Deutschland (Azure-Region Germany West Central, Frankfurt
am Main). Die Daten werden dort gespeichert. Microsoft kann im Rahmen des
Supports aus Drittländern zugreifen; die Microsoft Corporation ist unter dem
EU-U.S. Data Privacy Framework zertifiziert, und der Datenschutznachtrag
enthält zusätzlich die Standardvertragsklauseln.

**Fehlerprotokollierung:** Zur Fehlersuche protokolliert der Dienst technische
Angaben zu jeder Anfrage (Zeitpunkt, Ergebnis, Laufzeit, Fehlermeldungen).
Die IP-Adresse wird dabei **nicht gespeichert**; aus ihr werden nur Land und
Stadt abgeleitet und diese grobe Ortsangabe protokolliert. Die Protokolle
werden nach 90 Tagen automatisch gelöscht.

**Speicherdauer:** Eine Meldung bleibt gespeichert, bis ich sie bearbeitet
habe, längstens **zwölf Monate**. Danach lösche ich sie.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Erfüllung des
Nutzungsverhältnisses — Sie haben die Übermittlung durch das Tippen auf
„Melden" ausgelöst), hilfsweise Art. 6 Abs. 1 lit. f DSGVO (berechtigtes
Interesse an der Verbesserung der Datengrundlage, auf der die App beruht).

**Widerspruch und Löschung:** Da die Meldung keine Kennung enthält, kann ich
sie Ihnen nachträglich nicht zuordnen (Art. 11 DSGVO). Schreiben Sie mir den
Barcode und den ungefähren Zeitpunkt, lösche ich den Eintrag.

## 4. Was nicht stattfindet

Damit kein Zweifel bleibt — die App verarbeitet **nicht**:

- Name, E-Mail-Adresse oder sonstige Kontaktdaten von Ihnen
- Standortdaten
- Werbe-Identifikatoren (IDFA/AAID) oder sonstige geräteübergreifende Kennungen
- Nutzungsstatistiken, Analyse- oder Absturzberichte — mit der in
  Abschnitt 3.6 beschriebenen Ausnahme auf Android
- Kontakte, Kalender, Fotos oder andere Gerätedaten
- eine Historie Ihrer Scans — auch nicht der Produkte, die Sie gemeldet haben

Es findet **kein App-übergreifendes Tracking** statt. Es sind **keine
Werbe-, Analyse- oder Social-Media-SDKs** eingebunden. Die einzige eingebundene
Bibliothek, die selbst Daten an ihren Hersteller meldet, ist ML Kit in der
Android-Fassung (Abschnitt 3.6).

## 5. Speicherdauer und Löschung

**Auf Ihrem Gerät:** Die drei Werte aus Abschnitt 3.5 bleiben gespeichert,
bis Sie die App deinstallieren. Danach werden sie vom Betriebssystem
zusammen mit der App entfernt. Ein Zurücksetzen ohne Deinstallation ist über
die Einstellungen der App möglich, indem Sie die Siegel-Auswahl wieder auf den
Ausgangszustand bringen.

**Bei mir:** Gespeichert werden ausschließlich die Meldungen aus Abschnitt 3.7 —
und auch die nur, wenn Sie ausdrücklich gemeldet haben. Sie bleiben, bis ich sie
bearbeitet habe, längstens zwölf Monate. Darüber hinaus erhebe ich keine Daten von
Ihnen: kein Analysewerkzeug, keine Nutzungsstatistik, keine Absturzberichte.

Schreiben Sie mir eine E-Mail, verarbeite ich diese natürlich, um sie zu
beantworten; sie wird gelöscht, sobald der Vorgang abgeschlossen ist und keine
Aufbewahrungspflichten entgegenstehen.

**Bei Open Food Facts:** Über Aufbewahrungsfristen auf den Servern von Open
Food Facts entscheidet die Organisation selbst. Ich habe darauf keinen
Zugriff. Wenden Sie sich für Auskunft oder Löschung dorthin — die Kontaktdaten
stehen in deren Datenschutzerklärung (siehe 3.1).

**Bei Microsoft:** Die Meldungen liegen in meinem Speicherkonto in Deutschland;
Microsoft verarbeitet sie nur in meinem Auftrag und löscht sie auf meine Weisung.
Die Fehlerprotokolle löscht der Dienst nach 90 Tagen von selbst (Abschnitt 3.7).

**Bei Google (nur Android):** siehe Abschnitt 3.6.

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
Verarbeitung nicht darauf beruht — es gibt daher nichts zu widerrufen. Die
Abfragen bei Open Food Facts beenden Sie, indem Sie keinen Barcode mehr
scannen oder den Kamerazugriff in den Systemeinstellungen entziehen; jede
Verarbeitung, auch die Meldungen von ML Kit auf Android, indem Sie die App
nicht mehr verwenden oder deinstallieren.

**Beschwerderecht:** Sie können sich bei einer Datenschutz-Aufsichtsbehörde
beschweren, insbesondere in dem Mitgliedstaat Ihres Aufenthaltsorts, Ihres
Arbeitsplatzes oder des Orts des mutmaßlichen Verstoßes (Art. 77 DSGVO). Für
mich zuständig ist die Landesbeauftragte für Datenschutz und
Informationsfreiheit Nordrhein-Westfalen, Kavalleriestr. 2–4,
40213 Düsseldorf (Postfach 20 04 44, 40102 Düsseldorf),
<https://www.ldi.nrw.de>.

## 7. Bezug der App über App Store und Google Play

Der Bezug der App erfolgt über den App Store von Apple oder über Google Play.
Dabei verarbeitet der jeweilige Anbieter Daten in eigener Verantwortung —
etwa Ihre Account-Kennung, den Zeitpunkt des Downloads und Ihr Gerät. Auf
diese Verarbeitung habe ich keinen Einfluss; es gelten die
Datenschutzerklärungen von Apple:
<https://www.apple.com/legal/privacy/de-ww/> und von Google:
<https://policies.google.com/privacy>

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
