# SiegelBlick — Hilfe und Kontakt

SiegelBlick liest den Barcode einer Lebensmittelverpackung und schlägt bei der
offenen Datenbank [Open Food Facts](https://world.openfoodfacts.org) nach, ob
dort für dieses Produkt ein Nachhaltigkeitssiegel **eingetragen** ist.

## Kontakt

E-Mail: info@mzitniko.de

Ich beantworte Anfragen, so gut es neben einem privaten Projekt geht. Bei
Fehlermeldungen hilft mir: welches Gerät, welche iOS- oder Android-Version,
welcher Barcode und was Sie erwartet hätten.

## Häufige Fragen

### Die App findet kein Siegel, obwohl eines auf der Packung ist

Das ist der häufigste Fall und kein Fehler der App.

Open Food Facts wird ehrenamtlich gepflegt und ist lückenhaft. Ein Produkt
kann ein Siegel gut sichtbar tragen, ohne dass es jemand in die Datenbank
eingetragen hat. SiegelBlick sagt deshalb nie, ein Produkt sei *nicht*
zertifiziert — nur, dass *kein Eintrag vorliegt*.

**Maßgeblich ist immer die Packung**, nicht die App.

Wenn Sie möchten, können Sie den fehlenden Eintrag bei Open Food Facts selbst
ergänzen. Die Datenbank ist offen, und die Eintragung ist nach kostenloser
Registrierung möglich.

### Die App zeigt ein Siegel, das nicht auf der Packung steht

Auch das ist möglich, aus demselben Grund: Jeder kann bei Open Food Facts
eintragen, und Einträge können falsch oder veraltet sein. SiegelBlick prüft
keine Zertifizierung nach — die App zeigt ausschließlich den Datenbankeintrag.

Bitte melden Sie solche Fälle direkt bei Open Food Facts, dort lässt sich der
Datensatz korrigieren. Ich kann fremde Einträge nicht ändern.

### Das Produkt ist unbekannt

Dann gibt es zu diesem Barcode noch keinen Datensatz. Das kommt bei
Eigenmarken, regionalen Produkten und neuen Artikeln häufig vor.

### Warum wird nur Rainforest Alliance geprüft?

Voreingestellt ist nur dieses eine Siegel. In den Einstellungen können Sie
acht weitere zuschalten: UTZ, Fairtrade, Demeter, Naturland, Bioland, MSC, ASC
und Ohne Gentechnik. Zu jedem steht dort, wer es vergibt und wer prüft — mit
Quellenangabe.

### Der Barcode wird nicht erkannt

Meist hilft mehr Licht oder etwas mehr Abstand. Gelesen werden EAN-13, EAN-8,
UPC-A und UPC-E — also die üblichen Produktbarcodes. QR-Codes werden bewusst
ignoriert, damit ein Werbeaufsteller neben dem Regal keine Abfrage auslöst.

### „Die Datenbank antwortet gerade nicht"

Open Food Facts begrenzt die Zahl der Abfragen. Warten Sie einen Moment und
versuchen Sie es erneut.

## Datenschutz

Es gibt kein Konto, kein Tracking und keine Werbung. Die App überträgt nur den
gescannten Barcode an Open Food Facts. Kamerabilder verlassen das Gerät nicht.

Auf Android erkennt Googles ML Kit den Barcode. Es meldet Google technische
Nutzungs- und Diagnosedaten, darunter eine Kennung der Installation.
Kamerabild und Barcode schickt es nach Googles Angaben nicht mit.

Einzelheiten in der [Datenschutzerklärung](datenschutz.md).

## Unabhängigkeit

SiegelBlick ist ein unabhängiges, privates Projekt. Es besteht **keine
Verbindung** zu den Organisationen hinter den Siegeln und keine zu Open Food
Facts. Die Namen der Siegel sind Marken ihrer jeweiligen Inhaber und werden
hier ausschließlich beschreibend verwendet, um auf den Eintrag in der
Datenbank zu verweisen.

## Daten und Lizenz

Alle Produktangaben stammen von Open Food Facts und stehen unter der
[Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/).
Produktfotos stehen unter
[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
